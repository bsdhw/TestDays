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

Total: 89

| Vendor        | Model                       | Form-Factor | Probe                                                     | Date         |
|---------------|-----------------------------|-------------|-----------------------------------------------------------|--------------|
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
| NetBSD 9.2        | 13        | 18.31%  |
| NetBSD 9.1        | 11        | 15.49%  |
| NetBSD 9.0_STABLE | 8         | 11.27%  |
| NetBSD 9.0        | 6         | 8.45%   |
| NetBSD 9.3        | 5         | 7.04%   |
| NetBSD 10.0_BETA  | 4         | 5.63%   |
| NetBSD 9.99.94    | 3         | 4.23%   |
| NetBSD 9.99.93    | 3         | 4.23%   |
| NetBSD 9.1_STABLE | 3         | 4.23%   |
| NetBSD 9.99.77    | 2         | 2.82%   |
| NetBSD 9.2_STABLE | 2         | 2.82%   |
| NetBSD 9.99.85    | 1         | 1.41%   |
| NetBSD 9.99.81    | 1         | 1.41%   |
| NetBSD 9.99.74    | 1         | 1.41%   |
| NetBSD 9.99.71    | 1         | 1.41%   |
| NetBSD 9.99.61    | 1         | 1.41%   |
| NetBSD 9.99.23    | 1         | 1.41%   |
| NetBSD 9.99.107   | 1         | 1.41%   |
| NetBSD 9.3_STABLE | 1         | 1.41%   |
| NetBSD 8.99.51    | 1         | 1.41%   |
| NetBSD 7.2        | 1         | 1.41%   |
| NetBSD 10.99.1    | 1         | 1.41%   |

OS Family
---------

OS without a version

![OS Family](./All/images/pie_chart_bsd/os_family.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| NetBSD | 62        | 100%    |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart_bsd/os_arch.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| amd64  | 50        | 80.65%  |
| i386   | 6         | 9.68%   |
| evbarm | 6         | 9.68%   |

DE
--

Desktop Environment

![DE](./All/images/pie_chart_bsd/os_de.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| Console      | 24        | 37.5%   |
| XFCE         | 13        | 20.31%  |
| helloDesktop | 9         | 14.06%  |
| Fluxbox      | 4         | 6.25%   |
| ctwm         | 4         | 6.25%   |
| MATE         | 2         | 3.13%   |
| DWM          | 2         | 3.13%   |
| Xfwm4        | 1         | 1.56%   |
| sdorfehs     | 1         | 1.56%   |
| Ratpoison    | 1         | 1.56%   |
| PekWM        | 1         | 1.56%   |
| LXQt         | 1         | 1.56%   |
| Awesome      | 1         | 1.56%   |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart_bsd/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 45        | 72.58%  |
| Console | 17        | 27.42%  |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart_bsd/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Console | 56        | 90.32%  |
| XDM     | 2         | 3.23%   |
| GDM     | 2         | 3.23%   |
| SLiM    | 1         | 1.61%   |
| LightDM | 1         | 1.61%   |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart_bsd/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 47        | 71.21%  |
| en_US   | 11        | 16.67%  |
| ru_RU   | 3         | 4.55%   |
| fi_FI   | 2         | 3.03%   |
| hu_HU   | 1         | 1.52%   |
| en_GB   | 1         | 1.52%   |
| C       | 1         | 1.52%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart_bsd/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| BIOS | 60        | 96.77%  |
| EFI  | 2         | 3.23%   |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart_bsd/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ufs     | 61        | 98.39%  |
| Unknown | 1         | 1.61%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart_bsd/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| GPT     | 40        | 64.52%  |
| Unknown | 22        | 35.48%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart_bsd/node_vendor.svg)


| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| Unknown                 | 18        | 29.03%  |
| ASUSTek Computer        | 8         | 12.9%   |
| Lenovo                  | 7         | 11.29%  |
| Gigabyte Technology     | 5         | 8.06%   |
| ASRock                  | 3         | 4.84%   |
| Acer                    | 3         | 4.84%   |
| MSI                     | 2         | 3.23%   |
| Intel                   | 2         | 3.23%   |
| Hewlett-Packard         | 2         | 3.23%   |
| Dell                    | 2         | 3.23%   |
| Toshiba                 | 1         | 1.61%   |
| Sony                    | 1         | 1.61%   |
| Samsung Electronics     | 1         | 1.61%   |
| Raspberry Pi Foundation | 1         | 1.61%   |
| MiTAC                   | 1         | 1.61%   |
| KLLISRE                 | 1         | 1.61%   |
| IBM                     | 1         | 1.61%   |
| Fujitsu Siemens         | 1         | 1.61%   |
| eMachines               | 1         | 1.61%   |
| Apple                   | 1         | 1.61%   |

Model
-----

Motherboard model

![Model](./All/images/pie_chart_bsd/node_model.svg)


| Name                                        | Computers | Percent |
|---------------------------------------------|-----------|---------|
| Unknown                                     | 18        | 29.03%  |
| ASUS PRIME A320M-K                          | 2         | 3.23%   |
| Toshiba Satellite A100                      | 1         | 1.61%   |
| Sony SVF1421DSGW                            | 1         | 1.61%   |
| Samsung DP700A3D/DM700A3D/DB701A3D/DP700A7D | 1         | 1.61%   |
| RPi Raspberry Pi 4 Model B                  | 1         | 1.61%   |
| MSI MS-7B86                                 | 1         | 1.61%   |
| MSI MS-7551                                 | 1         | 1.61%   |
| MiTAC 5033                                  | 1         | 1.61%   |
| Lenovo ThinkPad X240 20AMS0J01N             | 1         | 1.61%   |
| Lenovo ThinkPad T510 4313CTO                | 1         | 1.61%   |
| Lenovo ThinkPad T460s 20FAS3L002            | 1         | 1.61%   |
| Lenovo ThinkPad T430s 23564H3               | 1         | 1.61%   |
| Lenovo ThinkPad T420 4236D26                | 1         | 1.61%   |
| Lenovo ThinkPad 13 20GJCTO1WW               | 1         | 1.61%   |
| Lenovo G500 20236                           | 1         | 1.61%   |
| KLLISRE X99-B5 V1.0                         | 1         | 1.61%   |
| Intel NUC5PPYB H76558-102                   | 1         | 1.61%   |
| Intel DN2820FYK H24582-203                  | 1         | 1.61%   |
| IBM ThinkPad R51 2887AVG                    | 1         | 1.61%   |
| HP Vectra                                   | 1         | 1.61%   |
| HP Pavilion 17                              | 1         | 1.61%   |
| Gigabyte Z170X-Gaming 3                     | 1         | 1.61%   |
| Gigabyte X570 AORUS PRO                     | 1         | 1.61%   |
| Gigabyte P75-D3                             | 1         | 1.61%   |
| Gigabyte H61M-S2PV                          | 1         | 1.61%   |
| Gigabyte 970A-D3P                           | 1         | 1.61%   |
| Fujitsu Siemens AMILO L7310                 | 1         | 1.61%   |
| eMachines eME642G                           | 1         | 1.61%   |
| Dell Precision M4500                        | 1         | 1.61%   |
| Dell PowerEdge T320                         | 1         | 1.61%   |
| ASUS X555LJ                                 | 1         | 1.61%   |
| ASUS TUF B450-PLUS GAMING                   | 1         | 1.61%   |
| ASUS E45M1-I DELUXE                         | 1         | 1.61%   |
| ASUS B150M-K                                | 1         | 1.61%   |
| ASUS All Series                             | 1         | 1.61%   |
| ASUS A3L                                    | 1         | 1.61%   |
| ASRock X470 Gaming-ITX/ac                   | 1         | 1.61%   |
| ASRock N68-VS3 UCC                          | 1         | 1.61%   |
| ASRock 970 Extreme3                         | 1         | 1.61%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart_bsd/node_model_family.svg)


| Name                  | Computers | Percent |
|-----------------------|-----------|---------|
| Unknown               | 18        | 29.03%  |
| Lenovo ThinkPad       | 6         | 9.68%   |
| ASUS PRIME            | 2         | 3.23%   |
| Acer Aspire           | 2         | 3.23%   |
| Toshiba Satellite     | 1         | 1.61%   |
| Sony SVF1421DSGW      | 1         | 1.61%   |
| Samsung DP700A3D      | 1         | 1.61%   |
| RPi Raspberry         | 1         | 1.61%   |
| MSI MS-7B86           | 1         | 1.61%   |
| MSI MS-7551           | 1         | 1.61%   |
| MiTAC 5033            | 1         | 1.61%   |
| Lenovo G500           | 1         | 1.61%   |
| KLLISRE X99-B5        | 1         | 1.61%   |
| Intel NUC5PPYB        | 1         | 1.61%   |
| Intel DN2820FYK       | 1         | 1.61%   |
| IBM ThinkPad          | 1         | 1.61%   |
| HP Vectra             | 1         | 1.61%   |
| HP Pavilion           | 1         | 1.61%   |
| Gigabyte Z170X-Gaming | 1         | 1.61%   |
| Gigabyte X570         | 1         | 1.61%   |
| Gigabyte P75-D3       | 1         | 1.61%   |
| Gigabyte H61M-S2PV    | 1         | 1.61%   |
| Gigabyte 970A-D3P     | 1         | 1.61%   |
| Fujitsu Siemens AMILO | 1         | 1.61%   |
| eMachines eME642G     | 1         | 1.61%   |
| Dell Precision        | 1         | 1.61%   |
| Dell PowerEdge        | 1         | 1.61%   |
| ASUS X555LJ           | 1         | 1.61%   |
| ASUS TUF              | 1         | 1.61%   |
| ASUS E45M1-I          | 1         | 1.61%   |
| ASUS B150M-K          | 1         | 1.61%   |
| ASUS All              | 1         | 1.61%   |
| ASUS A3L              | 1         | 1.61%   |
| ASRock X470           | 1         | 1.61%   |
| ASRock N68-VS3        | 1         | 1.61%   |
| ASRock 970            | 1         | 1.61%   |
| Apple MacBook2        | 1         | 1.61%   |
| Acer Revo             | 1         | 1.61%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart_bsd/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 17        | 27.42%  |
| 2020    | 7         | 11.29%  |
| 2013    | 7         | 11.29%  |
| 2014    | 4         | 6.45%   |
| 2021    | 3         | 4.84%   |
| 2017    | 3         | 4.84%   |
| 2016    | 3         | 4.84%   |
| 2011    | 3         | 4.84%   |
| 2010    | 3         | 4.84%   |
| 2019    | 2         | 3.23%   |
| 2018    | 2         | 3.23%   |
| 2005    | 2         | 3.23%   |
| 2022    | 1         | 1.61%   |
| 2015    | 1         | 1.61%   |
| 2012    | 1         | 1.61%   |
| 2007    | 1         | 1.61%   |
| 2006    | 1         | 1.61%   |
| 2001    | 1         | 1.61%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart_bsd/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Desktop        | 38        | 61.29%  |
| Notebook       | 20        | 32.26%  |
| System on chip | 1         | 1.61%   |
| Mini pc        | 1         | 1.61%   |
| All in one     | 1         | 1.61%   |
| Server         | 1         | 1.61%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart_bsd/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 61        | 98.39%  |
| Yes  | 1         | 1.61%   |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart_bsd/node_ram_total.svg)


| Size in GB  | Computers | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 19        | 30.65%  |
| 3.01-4.0    | 10        | 16.13%  |
| 16.01-24.0  | 9         | 14.52%  |
| 8.01-16.0   | 7         | 11.29%  |
| 0.51-1.0    | 4         | 6.45%   |
| 32.01-64.0  | 3         | 4.84%   |
| 1.01-2.0    | 3         | 4.84%   |
| 0.01-0.5    | 3         | 4.84%   |
| 24.01-32.0  | 1         | 1.61%   |
| 64.01-256.0 | 1         | 1.61%   |
| 0           | 1         | 1.61%   |
| Unknown     | 1         | 1.61%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart_bsd/node_ram_used.svg)


| Used GB | Computers | Percent |
|---------|-----------|---------|
| Unknown | 62        | 100%    |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart_bsd/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 0      | 28        | 42.42%  |
| 1      | 25        | 37.88%  |
| 2      | 10        | 15.15%  |
| 3      | 2         | 3.03%   |
| 4      | 1         | 1.52%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart_bsd/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 60        | 96.77%  |
| Yes       | 2         | 3.23%   |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart_bsd/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 52        | 83.87%  |
| No        | 10        | 16.13%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart_bsd/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 35        | 56.45%  |
| No        | 27        | 43.55%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart_bsd/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 41        | 66.13%  |
| Yes       | 21        | 33.87%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart_bsd/node_location.svg)


| Country      | Computers | Percent |
|--------------|-----------|---------|
| Russia       | 12        | 19.35%  |
| USA          | 7         | 11.29%  |
| Italy        | 7         | 11.29%  |
| UK           | 5         | 8.06%   |
| Germany      | 5         | 8.06%   |
| Hungary      | 4         | 6.45%   |
| France       | 4         | 6.45%   |
| Saudi Arabia | 3         | 4.84%   |
| Finland      | 3         | 4.84%   |
| Romania      | 2         | 3.23%   |
| Vietnam      | 1         | 1.61%   |
| Spain        | 1         | 1.61%   |
| Poland       | 1         | 1.61%   |
| Netherlands  | 1         | 1.61%   |
| Latvia       | 1         | 1.61%   |
| India        | 1         | 1.61%   |
| Czechia      | 1         | 1.61%   |
| Canada       | 1         | 1.61%   |
| Brazil       | 1         | 1.61%   |
| Australia    | 1         | 1.61%   |

City
----

Geographic location (city)

![City](./All/images/pie_chart_bsd/node_city.svg)


| City                  | Computers | Percent |
|-----------------------|-----------|---------|
| Ozersk                | 7         | 11.11%  |
| Rome                  | 6         | 9.52%   |
| Moscow                | 4         | 6.35%   |
| Riyadh                | 3         | 4.76%   |
| Lille                 | 3         | 4.76%   |
| Gardony               | 3         | 4.76%   |
| Tampere               | 2         | 3.17%   |
| Bucharest             | 2         | 3.17%   |
| Washington            | 1         | 1.59%   |
| Urupes                | 1         | 1.59%   |
| Unterhaching          | 1         | 1.59%   |
| Ulan-Ude              | 1         | 1.59%   |
| Turin                 | 1         | 1.59%   |
| Turenki               | 1         | 1.59%   |
| Sydney                | 1         | 1.59%   |
| Surrey                | 1         | 1.59%   |
| Sun Prairie           | 1         | 1.59%   |
| Stourbridge           | 1         | 1.59%   |
| Sopron                | 1         | 1.59%   |
| Royal Tunbridge Wells | 1         | 1.59%   |
| Riga                  | 1         | 1.59%   |
| Reno                  | 1         | 1.59%   |
| Prague                | 1         | 1.59%   |
| Poznan                | 1         | 1.59%   |
| Portland              | 1         | 1.59%   |
| Murcia                | 1         | 1.59%   |
| London                | 1         | 1.59%   |
| Lohr a. Main          | 1         | 1.59%   |
| Ladbergen             | 1         | 1.59%   |
| Kalispell             | 1         | 1.59%   |
| Ho Chi Minh City      | 1         | 1.59%   |
| Hamilton              | 1         | 1.59%   |
| Genzano di Roma       | 1         | 1.59%   |
| Fort Wayne            | 1         | 1.59%   |
| Carry-le-Rouet        | 1         | 1.59%   |
| Bridgwater            | 1         | 1.59%   |
| Bloomsbury            | 1         | 1.59%   |
| Berlin                | 1         | 1.59%   |
| Amersfoort            | 1         | 1.59%   |
| Ahmedabad             | 1         | 1.59%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart_bsd/drive_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 9         | 12     | 18.37%  |
| Seagate             | 5         | 5      | 10.2%   |
| Samsung Electronics | 5         | 5      | 10.2%   |
| Kingston            | 5         | 5      | 10.2%   |
| Toshiba             | 4         | 6      | 8.16%   |
| SanDisk             | 4         | 5      | 8.16%   |
| Intel               | 3         | 3      | 6.12%   |
| Maxtor              | 2         | 2      | 4.08%   |
| Hitachi             | 2         | 3      | 4.08%   |
| SK hynix            | 1         | 2      | 2.04%   |
| Lexar               | 1         | 1      | 2.04%   |
| JetFlash            | 1         | 1      | 2.04%   |
| Intenso             | 1         | 1      | 2.04%   |
| HGST                | 1         | 1      | 2.04%   |
| Hewlett-Packard     | 1         | 1      | 2.04%   |
| Generic             | 1         | 1      | 2.04%   |
| Dell                | 1         | 2      | 2.04%   |
| Crucial             | 1         | 2      | 2.04%   |
| China               | 1         | 1      | 2.04%   |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart_bsd/drive_model.svg)


| Model                               | Computers | Percent |
|-------------------------------------|-----------|---------|
| Toshiba DT01ACA100 1TB              | 3         | 6%      |
| SanDisk Extreme SSD 500GB           | 2         | 4%      |
| Samsung SSD 860 EVO 500GB           | 2         | 4%      |
| Samsung HD103UJ 1TB                 | 2         | 4%      |
| Maxtor STM3250310AS 250GB           | 2         | 4%      |
| Kingston DataTraveler 3.0 32GB      | 2         | 4%      |
| WDC WDS240G2G0A-00JH30 240GB        | 1         | 2%      |
| WDC WDS120G2G0A-00JH30 120GB        | 1         | 2%      |
| WDC WD5003AZEX-00K3CA0 500GB        | 1         | 2%      |
| WDC WD5000AAKX-753CA1 500GB         | 1         | 2%      |
| WDC WD5000AACS-00ZUB0 500GB         | 1         | 2%      |
| WDC WD2502ABYS-01B7A0 256GB         | 1         | 2%      |
| WDC WD20EFRX-68EUZN0 2TB            | 1         | 2%      |
| WDC WD200EB-00BHF0 20GB             | 1         | 2%      |
| WDC WD1600BEVT-00A23T0 160GB        | 1         | 2%      |
| WDC WD10EZEX-60WN4A0 1TB            | 1         | 2%      |
| Toshiba DT01ACA200 2TB              | 1         | 2%      |
| SK hynix HFS128G39TND-N210A 128GB   | 1         | 2%      |
| Seagate ST750LM022 HN-M750MBB 752GB | 1         | 2%      |
| Seagate ST500VT000-1DK142 500GB     | 1         | 2%      |
| Seagate ST500LT012-9WS142 500GB     | 1         | 2%      |
| Seagate ST380011A 80GB              | 1         | 2%      |
| Seagate ST2000DL003-9VT166 2TB      | 1         | 2%      |
| SanDisk SDSSDH3512G 512GB           | 1         | 2%      |
| SanDisk Cruzer Glide 16GB           | 1         | 2%      |
| Samsung HM080HC 80GB                | 1         | 2%      |
| Lexar USB Flash Drive 64GB          | 1         | 2%      |
| Kingston SA400S37480G 480GB         | 1         | 2%      |
| Kingston SA400S37240G 240GB         | 1         | 2%      |
| Kingston SA400S37120G 120GB         | 1         | 2%      |
| JetFlash Transcend 16GB             | 1         | 2%      |
| Intenso Rainbow Line 8GB            | 1         | 2%      |
| Intel SSDSC2KW120H6 120GB           | 1         | 2%      |
| Intel SSDSC2CW120A3 120GB           | 1         | 2%      |
| Intel SSDSC2BF180A4L 180GB          | 1         | 2%      |
| Hitachi HTS721060G9AT00 64GB        | 1         | 2%      |
| Hitachi HTS548040M9AT00 37GB        | 1         | 2%      |
| HGST HTS545050A7E680 500GB          | 1         | 2%      |
| HP v100w 8GB                        | 1         | 2%      |
| Generic Flash Disk 2GB              | 1         | 2%      |

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
| Kingston            | 5         | 5      | 26.32%  |
| SanDisk             | 4         | 5      | 21.05%  |
| Intel               | 3         | 3      | 15.79%  |
| WDC                 | 2         | 2      | 10.53%  |
| Samsung Electronics | 2         | 2      | 10.53%  |
| SK hynix            | 1         | 2      | 5.26%   |
| Crucial             | 1         | 2      | 5.26%   |
| China               | 1         | 1      | 5.26%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart_bsd/drive_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 25        | 37     | 58.14%  |
| SSD  | 18        | 22     | 41.86%  |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart_bsd/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 37        | 59     | 100%    |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart_bsd/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 34        | 41     | 73.91%  |
| 0.51-1.0   | 9         | 12     | 19.57%  |
| 1.01-2.0   | 2         | 4      | 4.35%   |
| 4.01-10.0  | 1         | 2      | 2.17%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart_bsd/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 19        | 30.65%  |
| 251-500        | 11        | 17.74%  |
| 501-1000       | 9         | 14.52%  |
| 51-100         | 8         | 12.9%   |
| 1-20           | 7         | 11.29%  |
| 2001-3000      | 3         | 4.84%   |
| 21-50          | 2         | 3.23%   |
| 1001-2000      | 2         | 3.23%   |
| More than 3000 | 1         | 1.61%   |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart_bsd/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 45        | 66.18%  |
| 21-50          | 10        | 14.71%  |
| 51-100         | 6         | 8.82%   |
| 101-250        | 2         | 2.94%   |
| 1001-2000      | 2         | 2.94%   |
| More than 3000 | 1         | 1.47%   |
| 251-500        | 1         | 1.47%   |
| 501-1000       | 1         | 1.47%   |

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
| Works    | 21        | 36     | 50%     |
| Malfunc  | 12        | 13     | 28.57%  |
| Detected | 9         | 10     | 21.43%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart_bsd/storage_vendor.svg)


| Vendor                    | Computers | Percent |
|---------------------------|-----------|---------|
| Intel                     | 41        | 58.57%  |
| AMD                       | 15        | 21.43%  |
| Silicon Motion            | 3         | 4.29%   |
| SanDisk                   | 2         | 2.86%   |
| Samsung Electronics       | 2         | 2.86%   |
| Phison Electronics        | 2         | 2.86%   |
| VIA Technologies          | 1         | 1.43%   |
| Nvidia                    | 1         | 1.43%   |
| Micron/Crucial Technology | 1         | 1.43%   |
| Broadcom / LSI            | 1         | 1.43%   |
| ASMedia Technology        | 1         | 1.43%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart_bsd/storage_model.svg)


| Model                                                                            | Computers | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                              | 8         | 10%     |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                | 6         | 7.5%    |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 5         | 6.25%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]    | 4         | 5%      |
| AMD 400 Series Chipset SATA Controller                                           | 4         | 5%      |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                  | 3         | 3.75%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]     | 3         | 3.75%   |
| SanDisk WD Blue SN550 NVMe SSD                                                   | 2         | 2.5%    |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 2         | 2.5%    |
| Intel Jasper Lake SATA AHCI Controller                                           | 2         | 2.5%    |
| Intel Cannon Lake PCH SATA AHCI Controller                                       | 2         | 2.5%    |
| Intel 82801DBM (ICH4-M) IDE Controller                                           | 2         | 2.5%    |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 2         | 2.5%    |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller    | 2         | 2.5%    |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                   | 2         | 2.5%    |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                             | 2         | 2.5%    |
| AMD FCH SATA Controller D                                                        | 2         | 2.5%    |
| VIA VT82C586A/B/VT82C686/A/B/VT823x/A/C PIPC Bus Master IDE                      | 1         | 1.25%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 1         | 1.25%   |
| Samsung NVMe SSD Controller 980                                                  | 1         | 1.25%   |
| Phison E16 PCIe4 NVMe Controller                                                 | 1         | 1.25%   |
| Phison E12 NVMe Controller                                                       | 1         | 1.25%   |
| Nvidia MCP61 SATA Controller                                                     | 1         | 1.25%   |
| Nvidia MCP61 IDE                                                                 | 1         | 1.25%   |
| Micron/Crucial P2 NVMe PCIe SSD                                                  | 1         | 1.25%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 1         | 1.25%   |
| Intel product 54d3                                                               | 1         | 1.25%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                           | 1         | 1.25%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller         | 1         | 1.25%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                | 1         | 1.25%   |
| Intel C600/X79 series chipset 6-Port SATA AHCI Controller                        | 1         | 1.25%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 1         | 1.25%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                           | 1         | 1.25%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [IDE mode]                    | 1         | 1.25%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [AHCI mode]                   | 1         | 1.25%   |
| Intel 82801G (ICH7 Family) IDE Controller                                        | 1         | 1.25%   |
| Intel 82801AA IDE Controller                                                     | 1         | 1.25%   |
| Intel 82371AB/EB/MB PIIX4 IDE                                                    | 1         | 1.25%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 1         | 1.25%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 1         | 1.25%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart_bsd/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 51        | 68.92%  |
| IDE  | 12        | 16.22%  |
| NVMe | 10        | 13.51%  |
| RAID | 1         | 1.35%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart_bsd/cpu_vendor.svg)


| Vendor       | Computers | Percent |
|--------------|-----------|---------|
| Intel        | 39        | 62.9%   |
| AMD          | 16        | 25.81%  |
| Unknown      | 3         | 4.84%   |
| Arm          | 2         | 3.23%   |
| Broadcom     | 1         | 1.61%   |
| 123456789ABC | 1         | 1.61%   |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart_bsd/cpu_model.svg)


| Model                                       | Computers | Percent |
|---------------------------------------------|-----------|---------|
| Intel 686-class                             | 14        | 21.88%  |
|                                             | 3         | 4.69%   |
| Arm Cortex-A53 r0p4 (v8-A)                  | 2         | 3.13%   |
| AMD 686-class                               | 2         | 3.13%   |
| Intel Xeon CPU E5-2630L v3 @ 1.80GHz        | 1         | 1.56%   |
| Intel Xeon CPU E5-2450L 0 @ 1.80GHz         | 1         | 1.56%   |
| Intel Pentium M processor 1.60GHz           | 1         | 1.56%   |
| Intel Pentium M processor                   | 1         | 1.56%   |
| Intel Pentium III                           | 1         | 1.56%   |
| Intel Pentium CPU 2020M @ 2.40GHz           | 1         | 1.56%   |
| Intel N100                                  | 1         | 1.56%   |
| Intel Core i7-6700K CPU @ 4.00GHz           | 1         | 1.56%   |
| Intel Core i7-5500U CPU @ 2.40GHz           | 1         | 1.56%   |
| Intel Core i7-3770 CPU @ 3.40GHz            | 1         | 1.56%   |
| Intel Core i7-2640M CPU @ 2.80GHz           | 1         | 1.56%   |
| Intel Core i5-9400T CPU @ 1.80GHz           | 1         | 1.56%   |
| Intel Core i5-7400 CPU @ 3.00GHz            | 1         | 1.56%   |
| Intel Core i5-6300U CPU @ 2.40GHz           | 1         | 1.56%   |
| Intel Core i5-6200U CPU @ 2.30GHz           | 1         | 1.56%   |
| Intel Core i5-4310M CPU @ 2.70GHz           | 1         | 1.56%   |
| Intel Core i5-4300U CPU @ 1.90GHz           | 1         | 1.56%   |
| Intel Core i5-3320M CPU @ 2.60GHz           | 1         | 1.56%   |
| Intel Core i5-2320 CPU @ 3.00GHz            | 1         | 1.56%   |
| Intel Core i5 CPU M 560 @ 2.67GH            | 1         | 1.56%   |
| Intel Core i5 CPU M 540 @ 2.53GHz           | 1         | 1.56%   |
| Intel Core i3-4150 CPU @ 3.50GHz            | 1         | 1.56%   |
| Intel Core i3-3220T CPU @ 2.80GHz           | 1         | 1.56%   |
| Intel Core i3-3217U CPU @ 1.80GHz           | 1         | 1.56%   |
| Intel Core 2 CPU T7200 @ 2.00GHz            | 1         | 1.56%   |
| Intel Core 2 CPU T7                         | 1         | 1.56%   |
| Intel Celeron CPU N2830 @ 2.16GHz           | 1         | 1.56%   |
| Broadcom BCM2711 (ARM Cortex-A72)           | 1         | 1.56%   |
| AMD Tillamook                               | 1         | 1.56%   |
| AMD Sempron 145 Processor                   | 1         | 1.56%   |
| AMD Ryzen 9 3900X 12-Core Processor         | 1         | 1.56%   |
| AMD Ryzen 7 2700 Eight-Core Processor       | 1         | 1.56%   |
| AMD Ryzen 5 3600 6-Core Processor           | 1         | 1.56%   |
| AMD Ryzen 5 2600 Six-Core Processor         | 1         | 1.56%   |
| AMD Ryzen 3 2200G with Radeon Vega Graphics | 1         | 1.56%   |
| AMD Ryzen 3 1200 Quad-Core Processor        | 1         | 1.56%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart_bsd/cpu_family.svg)


| Model             | Computers | Percent |
|-------------------|-----------|---------|
| Intel 686-class   | 14        | 21.88%  |
| Intel Core i5     | 10        | 15.63%  |
| Other             | 9         | 14.06%  |
| Intel Core i7     | 4         | 6.25%   |
| Intel Core i3     | 3         | 4.69%   |
| Intel Xeon        | 2         | 3.13%   |
| Intel Pentium M   | 2         | 3.13%   |
| Intel Core 2      | 2         | 3.13%   |
| AMD Ryzen 5       | 2         | 3.13%   |
| AMD Ryzen 3       | 2         | 3.13%   |
| AMD 686-class     | 2         | 3.13%   |
| Intel Pentium III | 1         | 1.56%   |
| Intel Pentium     | 1         | 1.56%   |
| Intel Celeron     | 1         | 1.56%   |
| AMD Sempron       | 1         | 1.56%   |
| AMD Ryzen 9       | 1         | 1.56%   |
| AMD Ryzen 7       | 1         | 1.56%   |
| AMD Phenom II X6  | 1         | 1.56%   |
| AMD Phenom II X4  | 1         | 1.56%   |
| AMD FX            | 1         | 1.56%   |
| AMD E             | 1         | 1.56%   |
| AMD Athlon II     | 1         | 1.56%   |
| AMD A10           | 1         | 1.56%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart_bsd/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| Unknown | 33        | 51.56%  |
| 2       | 14        | 21.88%  |
| 4       | 9         | 14.06%  |
| 8       | 4         | 6.25%   |
| 6       | 3         | 4.69%   |
| 12      | 1         | 1.56%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart_bsd/cpu_sockets.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 42        | 65.63%  |
| Unknown | 22        | 34.38%  |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart_bsd/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| Unknown | 33        | 51.56%  |
| 2       | 18        | 28.13%  |
| 1       | 13        | 20.31%  |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart_bsd/cpu_microarch.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| Unknown     | 27        | 42.19%  |
| IvyBridge   | 5         | 7.81%   |
| Skylake     | 3         | 4.69%   |
| SandyBridge | 3         | 4.69%   |
| P6          | 3         | 4.69%   |
| K10         | 3         | 4.69%   |
| Haswell     | 3         | 4.69%   |
| Zen+        | 2         | 3.13%   |
| Zen 2       | 2         | 3.13%   |
| Zen         | 2         | 3.13%   |
| Piledriver  | 2         | 3.13%   |
| KabyLake    | 2         | 3.13%   |
| Core        | 2         | 3.13%   |
| Westmere    | 1         | 1.56%   |
| Silvermont  | 1         | 1.56%   |
| Geode       | 1         | 1.56%   |
| Broadwell   | 1         | 1.56%   |
| Bobcat      | 1         | 1.56%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart_bsd/gpu_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Intel                      | 33        | 52.38%  |
| AMD                        | 16        | 25.4%   |
| Nvidia                     | 11        | 17.46%  |
| VIA Technologies           | 1         | 1.59%   |
| Trident Microsystems       | 1         | 1.59%   |
| Matrox Electronics Systems | 1         | 1.59%   |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart_bsd/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 3rd Gen Core processor Graphics Controller                                         | 4         | 6.06%   |
| Intel HD Graphics 530                                                                    | 3         | 4.55%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 3         | 4.55%   |
| Nvidia GF114 [GeForce GTX 560]                                                           | 2         | 3.03%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 2         | 3.03%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 2         | 3.03%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 2         | 3.03%   |
| Intel Mobile 945GM/GMS, 943/940GML Express Integrated Graphics Controller                | 2         | 3.03%   |
| Intel JasperLake [UHD Graphics]                                                          | 2         | 3.03%   |
| Intel 82852/855GM Integrated Graphics Device                                             | 2         | 3.03%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 2         | 3.03%   |
| VIA Technologies CN400/PM800/PM880/PN800/PN880 [S3 UniChrome Pro]                        | 1         | 1.52%   |
| Trident Microsystems TGUI 9660/938x/968x                                                 | 1         | 1.52%   |
| Nvidia NV18 [GeForce4 MX 440 AGP 8x]                                                     | 1         | 1.52%   |
| Nvidia GT218M [NVS 3100M]                                                                | 1         | 1.52%   |
| Nvidia GT216GLM [Quadro FX 880M]                                                         | 1         | 1.52%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 1         | 1.52%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 1         | 1.52%   |
| Nvidia GM204 [GeForce GTX 970]                                                           | 1         | 1.52%   |
| Nvidia GK208BM [GeForce 920M]                                                            | 1         | 1.52%   |
| Nvidia G86 [GeForce 8500 GT]                                                             | 1         | 1.52%   |
| Nvidia C61 [GeForce 7025 / nForce 630a]                                                  | 1         | 1.52%   |
| Matrox Electronics Systems G200eR2                                                       | 1         | 1.52%   |
| Intel IvyBridge GT2 [HD Graphics 4000]                                                   | 1         | 1.52%   |
| Intel Iris Graphics 6100                                                                 | 1         | 1.52%   |
| Intel HD Graphics 630                                                                    | 1         | 1.52%   |
| Intel HD Graphics 5500                                                                   | 1         | 1.52%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 1         | 1.52%   |
| Intel GeminiLake [UHD Graphics 605]                                                      | 1         | 1.52%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                                 | 1         | 1.52%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 1         | 1.52%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 1         | 1.52%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 1         | 1.52%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 1         | 1.52%   |
| Intel Apollo Lake [HD Graphics 505]                                                      | 1         | 1.52%   |
| Intel Alder Lake-N [UHD Graphics]                                                        | 1         | 1.52%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 1         | 1.52%   |
| AMD Wrestler [Radeon HD 6320]                                                            | 1         | 1.52%   |
| AMD Wrestler [Radeon HD 6250]                                                            | 1         | 1.52%   |
| AMD Tonga PRO [Radeon R9 285/380]                                                        | 1         | 1.52%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart_bsd/gpu_combo.svg)


| Name                     | Computers | Percent |
|--------------------------|-----------|---------|
| 1 x Intel                | 26        | 41.94%  |
| 1 x AMD                  | 13        | 20.97%  |
| 1 x Nvidia               | 8         | 12.9%   |
| Other                    | 6         | 9.68%   |
| 2 x Intel                | 2         | 3.23%   |
| Intel + Nvidia           | 2         | 3.23%   |
| 2 x AMD                  | 1         | 1.61%   |
| 1 x VIA                  | 1         | 1.61%   |
| 1 x Trident Microsystems | 1         | 1.61%   |
| 1 x Matrox               | 1         | 1.61%   |
| Intel + AMD              | 1         | 1.61%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart_bsd/gpu_driver.svg)


| Driver  | Computers | Percent |
|---------|-----------|---------|
| Free    | 46        | 71.88%  |
| Unknown | 18        | 28.13%  |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart_bsd/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 30        | 47.62%  |
| 1.01-2.0   | 11        | 17.46%  |
| 0.01-0.5   | 10        | 15.87%  |
| 3.01-4.0   | 6         | 9.52%   |
| 0.51-1.0   | 5         | 7.94%   |
| 7.01-8.0   | 1         | 1.59%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart_bsd/mon_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 6         | 23.08%  |
| LG Display          | 6         | 23.08%  |
| Goldstar            | 4         | 15.38%  |
| Chimei Innolux      | 2         | 7.69%   |
| Apple               | 2         | 7.69%   |
| ViewSonic           | 1         | 3.85%   |
| Unknown (CDD)       | 1         | 3.85%   |
| LG Philips          | 1         | 3.85%   |
| Lenovo              | 1         | 3.85%   |
| Impression          | 1         | 3.85%   |
| Acer                | 1         | 3.85%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart_bsd/mon_model.svg)


| Model                                                                 | Computers | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| Samsung Electronics LCD Monitor SAM0C39 1920x1080 890x500mm 40.2-inch | 2         | 7.69%   |
| ViewSonic VG2439 Series VSCD22B 1920x1080 520x290mm 23.4-inch         | 1         | 3.85%   |
| Unknown (CDD) VGA CDD0030 1920x1080 1150x650mm 52.0-inch              | 1         | 3.85%   |
| Samsung Electronics SyncMaster SAM01AE 1600x1200 410x310mm 20.2-inch  | 1         | 3.85%   |
| Samsung Electronics SMS27A350H SAM07CE 1920x1080 600x340mm 27.2-inch  | 1         | 3.85%   |
| Samsung Electronics S23C570 SAM0A56 1920x1080 510x290mm 23.1-inch     | 1         | 3.85%   |
| Samsung Electronics LCD Monitor SDC4752 1366x768 340x190mm 15.3-inch  | 1         | 3.85%   |
| LG Philips LCD Monitor LPLDD00 1280x800 330x210mm 15.4-inch           | 1         | 3.85%   |
| LG Display LCD Monitor LGD40A0 1366x768 310x170mm 13.9-inch           | 1         | 3.85%   |
| LG Display LCD Monitor LGD0521 1920x1080 310x170mm 13.9-inch          | 1         | 3.85%   |
| LG Display LCD Monitor LGD045E 1366x768 310x170mm 13.9-inch           | 1         | 3.85%   |
| LG Display LCD Monitor LGD03CD 1366x768 280x160mm 12.7-inch           | 1         | 3.85%   |
| LG Display LCD Monitor LGD0335 1366x768 310x170mm 13.9-inch           | 1         | 3.85%   |
| LG Display LCD Monitor LGD029E 1600x900 340x190mm 15.3-inch           | 1         | 3.85%   |
| Lenovo LCD Monitor LEN40B1 1600x900 340x190mm 15.3-inch               | 1         | 3.85%   |
| Impression R19W11 IMP1911 1440x900 410x260mm 19.1-inch                | 1         | 3.85%   |
| Goldstar W1952 GSM4B78 1440x900 410x260mm 19.1-inch                   | 1         | 3.85%   |
| Goldstar LG ULTRAWIDE GSM59F1 2560x1080 800x340mm 34.2-inch           | 1         | 3.85%   |
| Goldstar LCD Monitor GSM5AB6 1920x1080 480x270mm 21.7-inch            | 1         | 3.85%   |
| Goldstar L194WT GSM4B05 1440x900 410x260mm 19.1-inch                  | 1         | 3.85%   |
| Chimei Innolux LCD Monitor CMN15AB 1366x768 340x190mm 15.3-inch       | 1         | 3.85%   |
| Chimei Innolux LCD Monitor CMN1472 1366x768 310x170mm 13.9-inch       | 1         | 3.85%   |
| Apple LCD Monitor APP9C5F 1280x800 290x180mm 13.4-inch                | 1         | 3.85%   |
| Apple Color LCD APPA029 2560x1600 290x180mm 13.4-inch                 | 1         | 3.85%   |
| Acer SB220Q ACR06AB 1920x1080 480x270mm 21.7-inch                     | 1         | 3.85%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart_bsd/mon_resolution.svg)


| Resolution       | Computers | Percent |
|------------------|-----------|---------|
| 1920x1080 (FHD)  | 9         | 34.62%  |
| 1366x768 (WXGA)  | 7         | 26.92%  |
| 1440x900 (WXGA+) | 3         | 11.54%  |
| 1600x900 (HD+)   | 2         | 7.69%   |
| 1280x800 (WXGA)  | 2         | 7.69%   |
| 2560x1600        | 1         | 3.85%   |
| 2560x1080        | 1         | 3.85%   |
| 1600x1200        | 1         | 3.85%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart_bsd/mon_diagonal.svg)


| Inches | Computers | Percent |
|--------|-----------|---------|
| 13     | 7         | 26.92%  |
| 15     | 5         | 19.23%  |
| 19     | 3         | 11.54%  |
| 40     | 2         | 7.69%   |
| 23     | 2         | 7.69%   |
| 21     | 2         | 7.69%   |
| 52     | 1         | 3.85%   |
| 34     | 1         | 3.85%   |
| 27     | 1         | 3.85%   |
| 20     | 1         | 3.85%   |
| 12     | 1         | 3.85%   |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart_bsd/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 10        | 38.46%  |
| 401-500     | 6         | 23.08%  |
| 501-600     | 3         | 11.54%  |
| 201-300     | 3         | 11.54%  |
| 801-900     | 2         | 7.69%   |
| 701-800     | 1         | 3.85%   |
| 1001-1500   | 1         | 3.85%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart_bsd/mon_ratio.svg)


| Ratio | Computers | Percent |
|-------|-----------|---------|
| 16/9  | 18        | 69.23%  |
| 16/10 | 6         | 23.08%  |
| 4/3   | 1         | 3.85%   |
| 21/9  | 1         | 3.85%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart_bsd/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 81-90          | 7         | 26.92%  |
| 201-250        | 4         | 15.38%  |
| 151-200        | 4         | 15.38%  |
| 101-110        | 3         | 11.54%  |
| 501-1000       | 2         | 7.69%   |
| 91-100         | 2         | 7.69%   |
| More than 1000 | 1         | 3.85%   |
| 61-70          | 1         | 3.85%   |
| 351-500        | 1         | 3.85%   |
| 301-350        | 1         | 3.85%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart_bsd/mon_density.svg)


| Density | Computers | Percent |
|---------|-----------|---------|
| 51-100  | 12        | 46.15%  |
| 101-120 | 10        | 38.46%  |
| 121-160 | 2         | 7.69%   |
| 1-50    | 1         | 3.85%   |
| 161-240 | 1         | 3.85%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart_bsd/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 35        | 55.56%  |
| 0     | 27        | 42.86%  |
| 2     | 1         | 1.59%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart_bsd/net_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 31        | 36.47%  |
| Intel                    | 26        | 30.59%  |
| Qualcomm Atheros         | 12        | 14.12%  |
| Broadcom                 | 5         | 5.88%   |
| Huawei Technologies      | 3         | 3.53%   |
| VIA Technologies         | 1         | 1.18%   |
| TP-Link                  | 1         | 1.18%   |
| Oculus VR                | 1         | 1.18%   |
| Netchip Technology       | 1         | 1.18%   |
| Mercucys                 | 1         | 1.18%   |
| Marvell Technology Group | 1         | 1.18%   |
| D-Link                   | 1         | 1.18%   |
| 3Com                     | 1         | 1.18%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart_bsd/net_model.svg)


| Model                                                                                 | Computers | Percent |
|---------------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller                     | 28        | 26.17%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)                                 | 5         | 4.67%   |
| Intel I211 Gigabit Network Connection                                                 | 3         | 2.8%    |
| Huawei USB Device                                                                     | 3         | 2.8%    |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                                 | 2         | 1.87%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                            | 2         | 1.87%   |
| Qualcomm Atheros AR2413/AR2414 Wireless Network Adapter [AR5005G(S) 802.11bg]         | 2         | 1.87%   |
| Intel Wireless-AC 9260                                                                | 2         | 1.87%   |
| Intel Wireless 8260                                                                   | 2         | 1.87%   |
| Intel Wi-Fi 6 AX201 160MHz                                                            | 2         | 1.87%   |
| Intel Ethernet Connection (2) I219-LM                                                 | 2         | 1.87%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                                          | 2         | 1.87%   |
| Intel Cannon Lake PCH CNVi WiFi                                                       | 2         | 1.87%   |
| VIA VT6102/VT6103 [Rhine-II]                                                          | 1         | 0.93%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                                          | 1         | 0.93%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter                              | 1         | 0.93%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                                       | 1         | 0.93%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                                                | 1         | 0.93%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                                   | 1         | 0.93%   |
| Realtek RTL8188EE Wireless Network Adapter                                            | 1         | 0.93%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                                               | 1         | 0.93%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                                 | 1         | 0.93%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                                                | 1         | 0.93%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller                             | 1         | 0.93%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                                      | 1         | 0.93%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                                      | 1         | 0.93%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)                        | 1         | 0.93%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                        | 1         | 0.93%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                         | 1         | 0.93%   |
| Qualcomm Atheros AR5418 Wireless Network Adapter [AR5008E 802.11(a)bgn] (PCI-Express) | 1         | 0.93%   |
| Oculus VR Rift S                                                                      | 1         | 0.93%   |
| Netchip Linux-USB Serial Gadget (CDC ACM mode)                                        | 1         | 0.93%   |
| Mercucys MERCUSYS Wireless USB Adapter                                                | 1         | 0.93%   |
| Marvell Group 88E8053 PCI-E Gigabit Ethernet Controller                               | 1         | 0.93%   |
| Intel Wireless 7265                                                                   | 1         | 0.93%   |
| Intel Wireless 7260                                                                   | 1         | 0.93%   |
| Intel Wi-Fi 6 AX200                                                                   | 1         | 0.93%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                                 | 1         | 0.93%   |
| Intel PRO/Wireless 2200BG [Calexico2] Network Connection                              | 1         | 0.93%   |
| Intel PRO/100 VE Network Connection                                                   | 1         | 0.93%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart_bsd/net_wireless_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Intel                 | 20        | 50%     |
| Qualcomm Atheros      | 9         | 22.5%   |
| Realtek Semiconductor | 5         | 12.5%   |
| Broadcom              | 3         | 7.5%    |
| TP-Link               | 1         | 2.5%    |
| Mercucys              | 1         | 2.5%    |
| D-Link                | 1         | 2.5%    |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart_bsd/net_wireless_model.svg)


| Model                                                                                 | Computers | Percent |
|---------------------------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                            | 2         | 4.88%   |
| Qualcomm Atheros AR2413/AR2414 Wireless Network Adapter [AR5005G(S) 802.11bg]         | 2         | 4.88%   |
| Intel Wireless-AC 9260                                                                | 2         | 4.88%   |
| Intel Wireless 8260                                                                   | 2         | 4.88%   |
| Intel Wi-Fi 6 AX201 160MHz                                                            | 2         | 4.88%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                                          | 2         | 4.88%   |
| Intel Cannon Lake PCH CNVi WiFi                                                       | 2         | 4.88%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                                          | 1         | 2.44%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter                              | 1         | 2.44%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                                       | 1         | 2.44%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                                                | 1         | 2.44%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                                   | 1         | 2.44%   |
| Realtek RTL8188EE Wireless Network Adapter                                            | 1         | 2.44%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                                               | 1         | 2.44%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                                      | 1         | 2.44%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                                      | 1         | 2.44%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)                        | 1         | 2.44%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                        | 1         | 2.44%   |
| Qualcomm Atheros AR5418 Wireless Network Adapter [AR5008E 802.11(a)bgn] (PCI-Express) | 1         | 2.44%   |
| Mercucys MERCUSYS Wireless USB Adapter                                                | 1         | 2.44%   |
| Intel Wireless 7265                                                                   | 1         | 2.44%   |
| Intel Wireless 7260                                                                   | 1         | 2.44%   |
| Intel Wi-Fi 6 AX200                                                                   | 1         | 2.44%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                                 | 1         | 2.44%   |
| Intel PRO/Wireless 2200BG [Calexico2] Network Connection                              | 1         | 2.44%   |
| Intel Gemini Lake PCH CNVi WiFi                                                       | 1         | 2.44%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                                      | 1         | 2.44%   |
| Intel Centrino Wireless-N 135                                                         | 1         | 2.44%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                                          | 1         | 2.44%   |
| Intel Alder Lake-N Wireless-AC                                                        | 1         | 2.44%   |
| D-Link DWA-131 Wireless N Nano Adapter (Rev. E1) [Realtek RTL8192EU]                  | 1         | 2.44%   |
| Broadcom BCM43602 802.11ac Wireless LAN SoC                                           | 1         | 2.44%   |
| Broadcom BCM4331 802.11a/b/g/n                                                        | 1         | 2.44%   |
| Broadcom BCM43142 802.11b/g/n                                                         | 1         | 2.44%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart_bsd/net_ethernet_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 31        | 50.82%  |
| Intel                    | 18        | 29.51%  |
| Qualcomm Atheros         | 3         | 4.92%   |
| Huawei Technologies      | 3         | 4.92%   |
| Broadcom                 | 3         | 4.92%   |
| VIA Technologies         | 1         | 1.64%   |
| Marvell Technology Group | 1         | 1.64%   |
| 3Com                     | 1         | 1.64%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart_bsd/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 28        | 45.16%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 5         | 8.06%   |
| Intel I211 Gigabit Network Connection                             | 3         | 4.84%   |
| Huawei USB Device                                                 | 3         | 4.84%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 2         | 3.23%   |
| Intel Ethernet Connection (2) I219-LM                             | 2         | 3.23%   |
| VIA VT6102/VT6103 [Rhine-II]                                      | 1         | 1.61%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 1         | 1.61%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                            | 1         | 1.61%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 1         | 1.61%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 1         | 1.61%   |
| Marvell Group 88E8053 PCI-E Gigabit Ethernet Controller           | 1         | 1.61%   |
| Intel PRO/100 VE Network Connection                               | 1         | 1.61%   |
| Intel Ethernet Controller I225-V                                  | 1         | 1.61%   |
| Intel Ethernet Connection I219-V                                  | 1         | 1.61%   |
| Intel Ethernet Connection I219-LM                                 | 1         | 1.61%   |
| Intel Ethernet Connection I218-LM                                 | 1         | 1.61%   |
| Intel Ethernet Connection I217-V                                  | 1         | 1.61%   |
| Intel 82801DB PRO/100 VE (MOB) Ethernet Controller                | 1         | 1.61%   |
| Intel 82577LM Gigabit Network Connection                          | 1         | 1.61%   |
| Intel 82574L Gigabit Network Connection                           | 1         | 1.61%   |
| Broadcom NetXtreme BCM57766 Gigabit Ethernet PCIe                 | 1         | 1.61%   |
| Broadcom NetXtreme BCM5720 Gigabit Ethernet PCIe                  | 1         | 1.61%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 1         | 1.61%   |
| 3Com 3c905C-TX/TX-M [Tornado]                                     | 1         | 1.61%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart_bsd/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 56        | 57.73%  |
| WiFi     | 37        | 38.14%  |
| Modem    | 3         | 3.09%   |
| Unknown  | 1         | 1.03%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart_bsd/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 46        | 70.77%  |
| WiFi     | 19        | 29.23%  |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart_bsd/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 30        | 48.39%  |
| 1     | 19        | 30.65%  |
| 0     | 9         | 14.52%  |
| 3     | 4         | 6.45%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart_bsd/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 51        | 80.95%  |
| Yes  | 12        | 19.05%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart_bsd/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 12        | 54.55%  |
| Apple                           | 3         | 13.64%  |
| Realtek Semiconductor           | 2         | 9.09%   |
| Qualcomm Atheros Communications | 1         | 4.55%   |
| Lite-On Technology              | 1         | 4.55%   |
| IMC Networks                    | 1         | 4.55%   |
| Cambridge Silicon Radio         | 1         | 4.55%   |
| Broadcom                        | 1         | 4.55%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart_bsd/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 4         | 18.18%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 4         | 18.18%  |
| Realtek Bluetooth Adapter                           | 1         | 4.55%   |
| Realtek Bluetooth 4.0 Adapter                       | 1         | 4.55%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 1         | 4.55%   |
| Lite-On Atheros AR3012 Bluetooth                    | 1         | 4.55%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 1         | 4.55%   |
| Intel Wireless-AC 3168 Bluetooth                    | 1         | 4.55%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 1         | 4.55%   |
| Intel AX201 Bluetooth                               | 1         | 4.55%   |
| IMC Networks Qualcomm Atheros Bluetooth 4.0 + HS    | 1         | 4.55%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 1         | 4.55%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 1         | 4.55%   |
| Apple Built-in iSight (no firmware loaded)          | 1         | 4.55%   |
| Apple Broadcom Built-in Bluetooth                   | 1         | 4.55%   |
| Apple Bluetooth Host Controller                     | 1         | 4.55%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart_bsd/snd_vendor.svg)


| Vendor                                       | Computers | Percent |
|----------------------------------------------|-----------|---------|
| Intel                                        | 40        | 55.56%  |
| AMD                                          | 18        | 25%     |
| Nvidia                                       | 7         | 9.72%   |
| Zoran Co. Personal Media Division (Nogatech) | 1         | 1.39%   |
| Yamaha                                       | 1         | 1.39%   |
| VIA Technologies                             | 1         | 1.39%   |
| Samsung Electronics                          | 1         | 1.39%   |
| Native Instruments                           | 1         | 1.39%   |
| Logitech                                     | 1         | 1.39%   |
| ESS Technology                               | 1         | 1.39%   |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart_bsd/snd_model.svg)


| Model                                                                                             | Computers | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 7         | 7.87%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 6         | 6.74%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 4         | 4.49%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                                               | 4         | 4.49%   |
| Intel Cannon Lake PCH cAVS                                                                        | 3         | 3.37%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 3         | 3.37%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 3         | 3.37%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                                        | 3         | 3.37%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 2         | 2.25%   |
| Nvidia GF114 HDMI Audio Controller                                                                | 2         | 2.25%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 2         | 2.25%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 2         | 2.25%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 2         | 2.25%   |
| Intel Jasper Lake HD Audio                                                                        | 2         | 2.25%   |
| Intel Broadwell-U Audio Controller                                                                | 2         | 2.25%   |
| Intel 82801DB/DBL/DBM (ICH4/ICH4-L/ICH4-M) AC'97 Audio Controller                                 | 2         | 2.25%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 2         | 2.25%   |
| AMD Wrestler HDMI Audio                                                                           | 2         | 2.25%   |
| AMD Starship/Matisse HD Audio Controller                                                          | 2         | 2.25%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]                           | 2         | 2.25%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                                            | 2         | 2.25%   |
| AMD Caicos HDMI Audio [Radeon HD 6450 / 7450/8450/8490 OEM / R5 230/235/235X OEM]                 | 2         | 2.25%   |
| Zoran Co. Personal Media Division (Nogatech) USB Audio and HID                                    | 1         | 1.12%   |
| Yamaha AG06/AG03                                                                                  | 1         | 1.12%   |
| VIA Technologies VT8233/A/8235/8237 AC97 Audio Controller                                         | 1         | 1.12%   |
| Samsung Electronics Samsung Type-C to 3.5pi gender adapter                                        | 1         | 1.12%   |
| Nvidia High Definition Audio Controller                                                           | 1         | 1.12%   |
| Nvidia GT216 HDMI Audio Controller                                                                | 1         | 1.12%   |
| Nvidia GM204 High Definition Audio Controller                                                     | 1         | 1.12%   |
| Native Instruments Komplete Audio 1                                                               | 1         | 1.12%   |
| Logitech Zone Wired Earbuds                                                                       | 1         | 1.12%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 1         | 1.12%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 1         | 1.12%   |
| Intel Comet Lake PCH-V cAVS                                                                       | 1         | 1.12%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 1         | 1.12%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 1         | 1.12%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 1         | 1.12%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 1         | 1.12%   |
| Intel Alder Lake-N HD Graphics SGPC                                                               | 1         | 1.12%   |
| Intel 82801AA AC'97 Audio Controller                                                              | 1         | 1.12%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart_bsd/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Unknown             | 8         | 16.67%  |
| Kingston            | 8         | 16.67%  |
| Samsung Electronics | 5         | 10.42%  |
| Crucial             | 5         | 10.42%  |
| Micron Technology   | 4         | 8.33%   |
| SK hynix            | 3         | 6.25%   |
| G.Skill             | 3         | 6.25%   |
| A-DATA Technology   | 3         | 6.25%   |
| Ramaxel Technology  | 2         | 4.17%   |
| Patriot             | 2         | 4.17%   |
| Corsair             | 2         | 4.17%   |
| SHARETRONIC         | 1         | 2.08%   |
| Nanya Technology    | 1         | 2.08%   |
| Unknown             | 1         | 2.08%   |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart_bsd/memory_model.svg)


| Model                                                      | Computers | Percent |
|------------------------------------------------------------|-----------|---------|
| Unknown RAM Module 8192MB DIMM 400MT/s                     | 1         | 1.92%   |
| Unknown RAM Module 512MB SODIMM DRAM 166MT/s               | 1         | 1.92%   |
| Unknown RAM Module 512MB SODIMM DDR2 533MT/s               | 1         | 1.92%   |
| Unknown RAM Module 2GB SODIMM DDR3                         | 1         | 1.92%   |
| Unknown RAM Module 256MB SODIMM DDR                        | 1         | 1.92%   |
| Unknown RAM Module 2048MB DIMM DDR2 800MT/s                | 1         | 1.92%   |
| Unknown RAM Module 2048MB DIMM 400MT/s                     | 1         | 1.92%   |
| Unknown RAM Module 128MB DIMM DRAM                         | 1         | 1.92%   |
| Unknown RAM Module 1024MB SODIMM SDRAM 266MT/s             | 1         | 1.92%   |
| SK hynix RAM HMT351S6BFR8C-H9 4GB SODIMM DDR3 1334MT/s     | 1         | 1.92%   |
| SK hynix RAM HMT351S6BFR8C-H9 4GB SODIMM DDR3 1333MT/s     | 1         | 1.92%   |
| SK hynix RAM HMT325S6EFR8A-PB 2GB SODIMM DDR3 1600MT/s     | 1         | 1.92%   |
| SHARETRONIC RAM Module 2048MB SODIMM DDR3 1600MT/s         | 1         | 1.92%   |
| Samsung RAM M471B5673FH0-CF8 2GB SODIMM DDR3 1067MT/s      | 1         | 1.92%   |
| Samsung RAM M471B5273EB0-CK0 4GB SODIMM DDR3 1600MT/s      | 1         | 1.92%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s      | 1         | 1.92%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1867MT/s      | 1         | 1.92%   |
| Samsung RAM M386B4G70DM0-YK04 32GB DIMM DDR3 1600MT/s      | 1         | 1.92%   |
| Samsung RAM M386B4G70DM0-YK03 32GB DIMM DDR3 1600MT/s      | 1         | 1.92%   |
| Ramaxel RAM RMT3160ED58E9W1600 4GB SODIMM DDR3 1600MT/s    | 1         | 1.92%   |
| Ramaxel RAM RMSA3230KB78HAF2133 8GB SODIMM DDR4 2133MT/s   | 1         | 1.92%   |
| Patriot RAM PSD44G213382 4096MB DIMM DDR4 2133MT/s         | 1         | 1.92%   |
| Patriot RAM PSD34G13332 4GB DIMM DDR3 1333MT/s             | 1         | 1.92%   |
| Nanya RAM NT2GC64B88B0NS-CG 2GB SODIMM DDR3 1334MT/s       | 1         | 1.92%   |
| Micron RAM Module 8GB Chip LPDDR4                          | 1         | 1.92%   |
| Micron RAM 8KTF51264HZ-1G6N1 4GB SODIMM DDR3 1600MT/s      | 1         | 1.92%   |
| Micron RAM 36ASF2G72PZ-2G1A2 16GB DIMM DDR4 2133MT/s       | 1         | 1.92%   |
| Micron RAM 16JSF51264HZ-1G1D1 4GB SODIMM DDR3 1067MT/s     | 1         | 1.92%   |
| Kingston RAM KHX2400C15/8G 8GB DIMM DDR4 2400MT/s          | 1         | 1.92%   |
| Kingston RAM KHX1600C9D3/4GX 4GB DIMM DDR3 1600MT/s        | 1         | 1.92%   |
| Kingston RAM ACR26D4S9S8ME-8 8GB SODIMM DDR4 2667MT/s      | 1         | 1.92%   |
| Kingston RAM ACR16D3LS1KFG/4G 4GB DIMM DDR3 1600MT/s       | 1         | 1.92%   |
| Kingston RAM ACR16D3LFS1KBG/2G 2GB SODIMM DDR3 1600MT/s    | 1         | 1.92%   |
| Kingston RAM 99U5701-077.A00G 16GB DIMM DDR4 2667MT/s      | 1         | 1.92%   |
| Kingston RAM 99U5471-028.A00LF 4GB DIMM DDR3 667MT/s       | 1         | 1.92%   |
| Kingston RAM 9905471-011.A00LF 4GB DIMM DDR3 1333MT/s      | 1         | 1.92%   |
| Kingston RAM 9905428-026.A02LF 2048MB SODIMM DDR3 1066MT/s | 1         | 1.92%   |
| G.Skill RAM F4-3200C16-16GVK 16GB DIMM DDR4 3200MT/s       | 1         | 1.92%   |
| G.Skill RAM F4-2800C17-8GVR 8192MB DIMM DDR4 2133MT/s      | 1         | 1.92%   |
| G.Skill RAM F3-1600C11-8G 8GB DIMM DDR3 1600MT/s           | 1         | 1.92%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart_bsd/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR3    | 19        | 46.34%  |
| DDR4    | 14        | 34.15%  |
| DRAM    | 2         | 4.88%   |
| DDR2    | 2         | 4.88%   |
| SDRAM   | 1         | 2.44%   |
| LPDDR4  | 1         | 2.44%   |
| DDR     | 1         | 2.44%   |
| Unknown | 1         | 2.44%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart_bsd/memory_formfactor.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| DIMM   | 21        | 51.22%  |
| SODIMM | 18        | 43.9%   |
| Chip   | 2         | 4.88%   |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart_bsd/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 13        | 30.23%  |
| 4096  | 13        | 30.23%  |
| 2048  | 7         | 16.28%  |
| 16384 | 4         | 9.3%    |
| 512   | 2         | 4.65%   |
| 32768 | 1         | 2.33%   |
| 1024  | 1         | 2.33%   |
| 256   | 1         | 2.33%   |
| 128   | 1         | 2.33%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart_bsd/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 11        | 23.4%   |
| 2133    | 5         | 10.64%  |
| 1333    | 4         | 8.51%   |
| Unknown | 4         | 8.51%   |
| 3200    | 3         | 6.38%   |
| 2667    | 2         | 4.26%   |
| 2400    | 2         | 4.26%   |
| 1334    | 2         | 4.26%   |
| 1067    | 2         | 4.26%   |
| 800     | 2         | 4.26%   |
| 3000    | 1         | 2.13%   |
| 2933    | 1         | 2.13%   |
| 2666    | 1         | 2.13%   |
| 1867    | 1         | 2.13%   |
| 1066    | 1         | 2.13%   |
| 667     | 1         | 2.13%   |
| 533     | 1         | 2.13%   |
| 400     | 1         | 2.13%   |
| 266     | 1         | 2.13%   |
| 166     | 1         | 2.13%   |

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
| Chicony Electronics           | 6         | 35.29%  |
| Silicon Motion                | 2         | 11.76%  |
| Realtek Semiconductor         | 2         | 11.76%  |
| Syntek                        | 1         | 5.88%   |
| Sunplus Innovation Technology | 1         | 5.88%   |
| Quanta                        | 1         | 5.88%   |
| Lenovo                        | 1         | 5.88%   |
| Bison Electronics             | 1         | 5.88%   |
| ARC International             | 1         | 5.88%   |
| ALi                           | 1         | 5.88%   |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart_bsd/camera_model.svg)


| Model                                | Computers | Percent |
|--------------------------------------|-----------|---------|
| Chicony Integrated Camera            | 3         | 17.65%  |
| Syntek Lenovo EasyCamera             | 1         | 5.88%   |
| Sunplus Integrated Camera            | 1         | 5.88%   |
| Silicon Motion WebCam SC-10IRQ12340N | 1         | 5.88%   |
| Silicon Motion 300k Pixel Camera     | 1         | 5.88%   |
| Realtek USB Camera                   | 1         | 5.88%   |
| Realtek Acer 640 x 480 laptop camera | 1         | 5.88%   |
| Quanta VGA WebCam                    | 1         | 5.88%   |
| Lenovo Integrated Webcam [R5U877]    | 1         | 5.88%   |
| Chicony USB2.0 VGA UVC WebCam        | 1         | 5.88%   |
| Chicony HP HD Webcam [Fixed]         | 1         | 5.88%   |
| Chicony Front Camera                 | 1         | 5.88%   |
| Bison Integrated Camera              | 1         | 5.88%   |
| ARC International Camera             | 1         | 5.88%   |
| ALi Gateway Webcam                   | 1         | 5.88%   |

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
| 0     | 22        | 34.92%  |
| 1     | 19        | 30.16%  |
| 2     | 12        | 19.05%  |
| 3     | 6         | 9.52%   |
| 5     | 2         | 3.17%   |
| 4     | 2         | 3.17%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart_bsd/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Communication controller | 33        | 46.48%  |
| Net/wireless             | 19        | 26.76%  |
| Card reader              | 7         | 9.86%   |
| Graphics card            | 5         | 7.04%   |
| Storage                  | 2         | 2.82%   |
| Net/ethernet             | 2         | 2.82%   |
| Wireless                 | 1         | 1.41%   |
| Modem                    | 1         | 1.41%   |
| Bluetooth                | 1         | 1.41%   |

