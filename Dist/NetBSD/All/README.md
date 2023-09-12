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

Total: 95

| Vendor        | Model                       | Form-Factor | Probe                                                     | Date         |
|---------------|-----------------------------|-------------|-----------------------------------------------------------|--------------|
| Unknown       | Unknown                     | Desktop     | [9c1891cda7](https://bsd-hardware.info/?probe=9c1891cda7) | Sep 03, 2023 |
| Raspberry ... | Raspberry Pi 4 Model B      | Soc         | [2beb3e34d8](https://bsd-hardware.info/?probe=2beb3e34d8) | Aug 20, 2023 |
| Unknown       | Unknown                     | Desktop     | [29fc7f6f45](https://bsd-hardware.info/?probe=29fc7f6f45) | Aug 19, 2023 |
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

![OS](./images/pie_chart_bsd/os_name.svg)


| Name              | Computers | Percent |
|-------------------|-----------|---------|
| NetBSD 9.2        | 13        | 16.88%  |
| NetBSD 9.1        | 11        | 14.29%  |
| NetBSD 9.3        | 10        | 12.99%  |
| NetBSD 9.0_STABLE | 8         | 10.39%  |
| NetBSD 9.0        | 6         | 7.79%   |
| NetBSD 10.0_BETA  | 4         | 5.19%   |
| NetBSD 9.99.94    | 3         | 3.9%    |
| NetBSD 9.99.93    | 3         | 3.9%    |
| NetBSD 9.1_STABLE | 3         | 3.9%    |
| NetBSD 9.99.77    | 2         | 2.6%    |
| NetBSD 9.2_STABLE | 2         | 2.6%    |
| NetBSD 9.99.85    | 1         | 1.3%    |
| NetBSD 9.99.81    | 1         | 1.3%    |
| NetBSD 9.99.74    | 1         | 1.3%    |
| NetBSD 9.99.71    | 1         | 1.3%    |
| NetBSD 9.99.61    | 1         | 1.3%    |
| NetBSD 9.99.23    | 1         | 1.3%    |
| NetBSD 9.99.107   | 1         | 1.3%    |
| NetBSD 9.3_STABLE | 1         | 1.3%    |
| NetBSD 8.99.51    | 1         | 1.3%    |
| NetBSD 7.2        | 1         | 1.3%    |
| NetBSD 10.99.7    | 1         | 1.3%    |
| NetBSD 10.99.1    | 1         | 1.3%    |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart_bsd/os_family.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| NetBSD | 68        | 100%    |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart_bsd/os_arch.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| amd64  | 55        | 80.88%  |
| evbarm | 7         | 10.29%  |
| i386   | 6         | 8.82%   |

DE
--

Desktop Environment

![DE](./images/pie_chart_bsd/os_de.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| Console      | 29        | 41.43%  |
| XFCE         | 14        | 20%     |
| helloDesktop | 9         | 12.86%  |
| Fluxbox      | 4         | 5.71%   |
| ctwm         | 4         | 5.71%   |
| MATE         | 2         | 2.86%   |
| DWM          | 2         | 2.86%   |
| Xfwm4        | 1         | 1.43%   |
| sdorfehs     | 1         | 1.43%   |
| Ratpoison    | 1         | 1.43%   |
| PekWM        | 1         | 1.43%   |
| LXQt         | 1         | 1.43%   |
| Awesome      | 1         | 1.43%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart_bsd/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 50        | 73.53%  |
| Console | 18        | 26.47%  |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart_bsd/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Console | 61        | 89.71%  |
| XDM     | 3         | 4.41%   |
| GDM     | 2         | 2.94%   |
| SLiM    | 1         | 1.47%   |
| LightDM | 1         | 1.47%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart_bsd/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 52        | 72.22%  |
| en_US   | 12        | 16.67%  |
| ru_RU   | 3         | 4.17%   |
| fi_FI   | 2         | 2.78%   |
| hu_HU   | 1         | 1.39%   |
| en_GB   | 1         | 1.39%   |
| C       | 1         | 1.39%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart_bsd/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| BIOS | 65        | 95.59%  |
| EFI  | 3         | 4.41%   |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart_bsd/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ufs     | 67        | 98.53%  |
| Unknown | 1         | 1.47%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart_bsd/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| GPT     | 44        | 64.71%  |
| Unknown | 24        | 35.29%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart_bsd/node_vendor.svg)


| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| Unknown                 | 20        | 29.41%  |
| Lenovo                  | 8         | 11.76%  |
| ASUSTek Computer        | 8         | 11.76%  |
| Gigabyte Technology     | 6         | 8.82%   |
| Intel                   | 3         | 4.41%   |
| ASRock                  | 3         | 4.41%   |
| Acer                    | 3         | 4.41%   |
| Raspberry Pi Foundation | 2         | 2.94%   |
| MSI                     | 2         | 2.94%   |
| Hewlett-Packard         | 2         | 2.94%   |
| Dell                    | 2         | 2.94%   |
| Toshiba                 | 1         | 1.47%   |
| Sony                    | 1         | 1.47%   |
| Samsung Electronics     | 1         | 1.47%   |
| MiTAC                   | 1         | 1.47%   |
| KLLISRE                 | 1         | 1.47%   |
| IBM                     | 1         | 1.47%   |
| Fujitsu Siemens         | 1         | 1.47%   |
| eMachines               | 1         | 1.47%   |
| Apple                   | 1         | 1.47%   |

Model
-----

Motherboard model

![Model](./images/pie_chart_bsd/node_model.svg)


| Name                                        | Computers | Percent |
|---------------------------------------------|-----------|---------|
| Unknown                                     | 20        | 29.41%  |
| RPi Raspberry Pi 4 Model B                  | 2         | 2.94%   |
| ASUS PRIME A320M-K                          | 2         | 2.94%   |
| Toshiba Satellite A100                      | 1         | 1.47%   |
| Sony SVF1421DSGW                            | 1         | 1.47%   |
| Samsung DP700A3D/DM700A3D/DB701A3D/DP700A7D | 1         | 1.47%   |
| MSI MS-7B86                                 | 1         | 1.47%   |
| MSI MS-7551                                 | 1         | 1.47%   |
| MiTAC 5033                                  | 1         | 1.47%   |
| Lenovo ThinkPad X240 20AMS0J01N             | 1         | 1.47%   |
| Lenovo ThinkPad T510 4313CTO                | 1         | 1.47%   |
| Lenovo ThinkPad T460s 20FAS3L002            | 1         | 1.47%   |
| Lenovo ThinkPad T430s 23564H3               | 1         | 1.47%   |
| Lenovo ThinkPad T430 2347A45                | 1         | 1.47%   |
| Lenovo ThinkPad T420 4236D26                | 1         | 1.47%   |
| Lenovo ThinkPad 13 20GJCTO1WW               | 1         | 1.47%   |
| Lenovo G500 20236                           | 1         | 1.47%   |
| KLLISRE X99-B5 V1.0                         | 1         | 1.47%   |
| Intel NUC5PPYB H76558-102                   | 1         | 1.47%   |
| Intel NUC5i7RYB H73774-102                  | 1         | 1.47%   |
| Intel DN2820FYK H24582-203                  | 1         | 1.47%   |
| IBM ThinkPad R51 2887AVG                    | 1         | 1.47%   |
| HP Vectra                                   | 1         | 1.47%   |
| HP Pavilion 17                              | 1         | 1.47%   |
| Gigabyte Z170X-Gaming 3                     | 1         | 1.47%   |
| Gigabyte X570 AORUS PRO                     | 1         | 1.47%   |
| Gigabyte P75-D3                             | 1         | 1.47%   |
| Gigabyte H61M-S2PV                          | 1         | 1.47%   |
| Gigabyte A320M-H                            | 1         | 1.47%   |
| Gigabyte 970A-D3P                           | 1         | 1.47%   |
| Fujitsu Siemens AMILO L7310                 | 1         | 1.47%   |
| eMachines eME642G                           | 1         | 1.47%   |
| Dell Precision M4500                        | 1         | 1.47%   |
| Dell PowerEdge T320                         | 1         | 1.47%   |
| ASUS X555LJ                                 | 1         | 1.47%   |
| ASUS TUF B450-PLUS GAMING                   | 1         | 1.47%   |
| ASUS E45M1-I DELUXE                         | 1         | 1.47%   |
| ASUS B150M-K                                | 1         | 1.47%   |
| ASUS All Series                             | 1         | 1.47%   |
| ASUS A3L                                    | 1         | 1.47%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart_bsd/node_model_family.svg)


| Name                  | Computers | Percent |
|-----------------------|-----------|---------|
| Unknown               | 20        | 29.41%  |
| Lenovo ThinkPad       | 7         | 10.29%  |
| RPi Raspberry         | 2         | 2.94%   |
| ASUS PRIME            | 2         | 2.94%   |
| Acer Aspire           | 2         | 2.94%   |
| Toshiba Satellite     | 1         | 1.47%   |
| Sony SVF1421DSGW      | 1         | 1.47%   |
| Samsung DP700A3D      | 1         | 1.47%   |
| MSI MS-7B86           | 1         | 1.47%   |
| MSI MS-7551           | 1         | 1.47%   |
| MiTAC 5033            | 1         | 1.47%   |
| Lenovo G500           | 1         | 1.47%   |
| KLLISRE X99-B5        | 1         | 1.47%   |
| Intel NUC5PPYB        | 1         | 1.47%   |
| Intel NUC5i7RYB       | 1         | 1.47%   |
| Intel DN2820FYK       | 1         | 1.47%   |
| IBM ThinkPad          | 1         | 1.47%   |
| HP Vectra             | 1         | 1.47%   |
| HP Pavilion           | 1         | 1.47%   |
| Gigabyte Z170X-Gaming | 1         | 1.47%   |
| Gigabyte X570         | 1         | 1.47%   |
| Gigabyte P75-D3       | 1         | 1.47%   |
| Gigabyte H61M-S2PV    | 1         | 1.47%   |
| Gigabyte A320M-H      | 1         | 1.47%   |
| Gigabyte 970A-D3P     | 1         | 1.47%   |
| Fujitsu Siemens AMILO | 1         | 1.47%   |
| eMachines eME642G     | 1         | 1.47%   |
| Dell Precision        | 1         | 1.47%   |
| Dell PowerEdge        | 1         | 1.47%   |
| ASUS X555LJ           | 1         | 1.47%   |
| ASUS TUF              | 1         | 1.47%   |
| ASUS E45M1-I          | 1         | 1.47%   |
| ASUS B150M-K          | 1         | 1.47%   |
| ASUS All              | 1         | 1.47%   |
| ASUS A3L              | 1         | 1.47%   |
| ASRock X470           | 1         | 1.47%   |
| ASRock N68-VS3        | 1         | 1.47%   |
| ASRock 970            | 1         | 1.47%   |
| Apple MacBook2        | 1         | 1.47%   |
| Acer Revo             | 1         | 1.47%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart_bsd/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 19        | 27.94%  |
| 2020    | 9         | 13.24%  |
| 2013    | 8         | 11.76%  |
| 2014    | 4         | 5.88%   |
| 2018    | 3         | 4.41%   |
| 2017    | 3         | 4.41%   |
| 2011    | 3         | 4.41%   |
| 2010    | 3         | 4.41%   |
| 2021    | 2         | 2.94%   |
| 2019    | 2         | 2.94%   |
| 2016    | 2         | 2.94%   |
| 2015    | 2         | 2.94%   |
| 2007    | 2         | 2.94%   |
| 2005    | 2         | 2.94%   |
| 2022    | 1         | 1.47%   |
| 2012    | 1         | 1.47%   |
| 2006    | 1         | 1.47%   |
| 2001    | 1         | 1.47%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart_bsd/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Desktop        | 41        | 60.29%  |
| Notebook       | 21        | 30.88%  |
| System on chip | 2         | 2.94%   |
| Mini pc        | 2         | 2.94%   |
| All in one     | 1         | 1.47%   |
| Server         | 1         | 1.47%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart_bsd/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 67        | 98.53%  |
| Yes  | 1         | 1.47%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart_bsd/node_ram_total.svg)


| Size in GB  | Computers | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 21        | 30.88%  |
| 3.01-4.0    | 10        | 14.71%  |
| 16.01-24.0  | 10        | 14.71%  |
| 8.01-16.0   | 9         | 13.24%  |
| 32.01-64.0  | 4         | 5.88%   |
| 0.51-1.0    | 4         | 5.88%   |
| 1.01-2.0    | 3         | 4.41%   |
| 0.01-0.5    | 3         | 4.41%   |
| 24.01-32.0  | 1         | 1.47%   |
| 64.01-256.0 | 1         | 1.47%   |
| 0           | 1         | 1.47%   |
| Unknown     | 1         | 1.47%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart_bsd/node_ram_used.svg)


| Used GB | Computers | Percent |
|---------|-----------|---------|
| Unknown | 68        | 100%    |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart_bsd/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 0      | 31        | 43.06%  |
| 1      | 28        | 38.89%  |
| 2      | 10        | 13.89%  |
| 3      | 2         | 2.78%   |
| 4      | 1         | 1.39%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart_bsd/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 65        | 95.59%  |
| Yes       | 3         | 4.41%   |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart_bsd/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 57        | 83.82%  |
| No        | 11        | 16.18%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart_bsd/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 39        | 57.35%  |
| No        | 29        | 42.65%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart_bsd/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 43        | 63.24%  |
| Yes       | 25        | 36.76%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart_bsd/node_location.svg)


| Country      | Computers | Percent |
|--------------|-----------|---------|
| Russia       | 12        | 17.65%  |
| USA          | 9         | 13.24%  |
| Italy        | 7         | 10.29%  |
| Germany      | 6         | 8.82%   |
| UK           | 5         | 7.35%   |
| Hungary      | 4         | 5.88%   |
| France       | 4         | 5.88%   |
| Saudi Arabia | 3         | 4.41%   |
| Finland      | 3         | 4.41%   |
| Spain        | 2         | 2.94%   |
| Romania      | 2         | 2.94%   |
| India        | 2         | 2.94%   |
| Vietnam      | 1         | 1.47%   |
| Poland       | 1         | 1.47%   |
| Norway       | 1         | 1.47%   |
| Netherlands  | 1         | 1.47%   |
| Latvia       | 1         | 1.47%   |
| Czechia      | 1         | 1.47%   |
| Canada       | 1         | 1.47%   |
| Brazil       | 1         | 1.47%   |
| Australia    | 1         | 1.47%   |

City
----

Geographic location (city)

![City](./images/pie_chart_bsd/node_city.svg)


| City                  | Computers | Percent |
|-----------------------|-----------|---------|
| Ozersk                | 7         | 10.14%  |
| Rome                  | 6         | 8.7%    |
| Moscow                | 4         | 5.8%    |
| Riyadh                | 3         | 4.35%   |
| Lille                 | 3         | 4.35%   |
| Gardony               | 3         | 4.35%   |
| Tampere               | 2         | 2.9%    |
| Hayward               | 2         | 2.9%    |
| Bucharest             | 2         | 2.9%    |
| Berlin                | 2         | 2.9%    |
| Washington            | 1         | 1.45%   |
| Urupes                | 1         | 1.45%   |
| Unterhaching          | 1         | 1.45%   |
| Ulan-Ude              | 1         | 1.45%   |
| Turin                 | 1         | 1.45%   |
| Turenki               | 1         | 1.45%   |
| Sydney                | 1         | 1.45%   |
| Surrey                | 1         | 1.45%   |
| Sun Prairie           | 1         | 1.45%   |
| Stourbridge           | 1         | 1.45%   |
| Sopron                | 1         | 1.45%   |
| Sandnes               | 1         | 1.45%   |
| Royal Tunbridge Wells | 1         | 1.45%   |
| Riga                  | 1         | 1.45%   |
| Reno                  | 1         | 1.45%   |
| Prague                | 1         | 1.45%   |
| Poznan                | 1         | 1.45%   |
| Portland              | 1         | 1.45%   |
| Murcia                | 1         | 1.45%   |
| London                | 1         | 1.45%   |
| Lohr a. Main          | 1         | 1.45%   |
| Ladbergen             | 1         | 1.45%   |
| Kalispell             | 1         | 1.45%   |
| Ho Chi Minh City      | 1         | 1.45%   |
| Hamilton              | 1         | 1.45%   |
| Genzano di Roma       | 1         | 1.45%   |
| Fort Wayne            | 1         | 1.45%   |
| Chennai               | 1         | 1.45%   |
| Carry-le-Rouet        | 1         | 1.45%   |
| Bridgwater            | 1         | 1.45%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart_bsd/drive_vendor.svg)


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

![Drive Model](./images/pie_chart_bsd/drive_model.svg)


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

![HDD Vendor](./images/pie_chart_bsd/drive_hdd_vendor.svg)


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

![SSD Vendor](./images/pie_chart_bsd/drive_ssd_vendor.svg)


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

![Drive Kind](./images/pie_chart_bsd/drive_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 25        | 37     | 55.56%  |
| SSD  | 20        | 24     | 44.44%  |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart_bsd/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 39        | 61     | 100%    |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart_bsd/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 36        | 43     | 75%     |
| 0.51-1.0   | 9         | 12     | 18.75%  |
| 1.01-2.0   | 2         | 4      | 4.17%   |
| 4.01-10.0  | 1         | 2      | 2.08%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart_bsd/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 20        | 29.41%  |
| 251-500        | 13        | 19.12%  |
| 501-1000       | 11        | 16.18%  |
| 51-100         | 8         | 11.76%  |
| 1-20           | 7         | 10.29%  |
| 21-50          | 3         | 4.41%   |
| 2001-3000      | 3         | 4.41%   |
| 1001-2000      | 2         | 2.94%   |
| More than 3000 | 1         | 1.47%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart_bsd/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 49        | 66.22%  |
| 21-50          | 10        | 13.51%  |
| 51-100         | 6         | 8.11%   |
| 101-250        | 3         | 4.05%   |
| 1001-2000      | 2         | 2.7%    |
| 501-1000       | 2         | 2.7%    |
| More than 3000 | 1         | 1.35%   |
| 251-500        | 1         | 1.35%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart_bsd/drive_malfunc.svg)


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

![Malfunc. Drive Vendor](./images/pie_chart_bsd/drive_malfunc_vendor.svg)


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

![Malfunc. HDD Vendor](./images/pie_chart_bsd/drive_malfunc_hdd_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 4         | 4      | 57.14%  |
| Hitachi | 2         | 3      | 28.57%  |
| WDC     | 1         | 1      | 14.29%  |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart_bsd/drive_malfunc_kind.svg)


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

![Drive Status](./images/pie_chart_bsd/drive_status.svg)


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

![Storage Vendor](./images/pie_chart_bsd/storage_vendor.svg)


| Vendor                    | Computers | Percent |
|---------------------------|-----------|---------|
| Intel                     | 44        | 57.89%  |
| AMD                       | 16        | 21.05%  |
| Samsung Electronics       | 4         | 5.26%   |
| Silicon Motion            | 3         | 3.95%   |
| SanDisk                   | 2         | 2.63%   |
| Phison Electronics        | 2         | 2.63%   |
| VIA Technologies          | 1         | 1.32%   |
| Nvidia                    | 1         | 1.32%   |
| Micron/Crucial Technology | 1         | 1.32%   |
| Broadcom / LSI            | 1         | 1.32%   |
| ASMedia Technology        | 1         | 1.32%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart_bsd/storage_model.svg)


| Model                                                                            | Computers | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                              | 8         | 9.3%    |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 6         | 6.98%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                | 6         | 6.98%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]    | 4         | 4.65%   |
| AMD 400 Series Chipset SATA Controller                                           | 4         | 4.65%   |
| Silicon Motion SM2263EN/SM2263XT (DRAM-less) NVMe SSD Controllers                | 3         | 3.49%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]     | 3         | 3.49%   |
| AMD FCH SATA Controller D                                                        | 3         | 3.49%   |
| SanDisk WD Blue SN550 NVMe SSD                                                   | 2         | 2.33%   |
| Samsung NVMe SSD Controller 980                                                  | 2         | 2.33%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 2         | 2.33%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 2         | 2.33%   |
| Intel product 54d3                                                               | 2         | 2.33%   |
| Intel Jasper Lake SATA AHCI Controller                                           | 2         | 2.33%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                       | 2         | 2.33%   |
| Intel 82801DBM (ICH4-M) IDE Controller                                           | 2         | 2.33%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 2         | 2.33%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller    | 2         | 2.33%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                   | 2         | 2.33%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                             | 2         | 2.33%   |
| VIA VT82C586A/B/VT82C686/A/B/VT823x/A/C PIPC Bus Master IDE                      | 1         | 1.16%   |
| Samsung S4LN058A01[SSUBX] AHCI SSD Controller (Apple slot)                       | 1         | 1.16%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 1         | 1.16%   |
| Phison E16 PCIe4 NVMe Controller                                                 | 1         | 1.16%   |
| Phison E12 NVMe Controller                                                       | 1         | 1.16%   |
| Nvidia MCP61 SATA Controller                                                     | 1         | 1.16%   |
| Nvidia MCP61 IDE                                                                 | 1         | 1.16%   |
| Micron/Crucial P2 [Nick P2] / P3 / P3 Plus NVMe PCIe SSD (DRAM-less)             | 1         | 1.16%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                           | 1         | 1.16%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller         | 1         | 1.16%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                | 1         | 1.16%   |
| Intel C600/X79 series chipset 6-Port SATA AHCI Controller                        | 1         | 1.16%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 1         | 1.16%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                           | 1         | 1.16%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [IDE mode]                    | 1         | 1.16%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [AHCI mode]                   | 1         | 1.16%   |
| Intel 82801G (ICH7 Family) IDE Controller                                        | 1         | 1.16%   |
| Intel 82801AA IDE Controller                                                     | 1         | 1.16%   |
| Intel 82371AB/EB/MB PIIX4 IDE                                                    | 1         | 1.16%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 1         | 1.16%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart_bsd/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 56        | 70%     |
| IDE  | 12        | 15%     |
| NVMe | 11        | 13.75%  |
| RAID | 1         | 1.25%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart_bsd/cpu_vendor.svg)


| Vendor       | Computers | Percent |
|--------------|-----------|---------|
| Intel        | 43        | 63.24%  |
| AMD          | 17        | 25%     |
| Unknown      | 3         | 4.41%   |
| Broadcom     | 2         | 2.94%   |
| Arm          | 2         | 2.94%   |
| 123456789ABC | 1         | 1.47%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart_bsd/cpu_model.svg)


| Model                                 | Computers | Percent |
|---------------------------------------|-----------|---------|
| Intel 686-class                       | 16        | 22.86%  |
|                                       | 3         | 4.29%   |
| Broadcom BCM2711 (ARM Cortex-A72)     | 2         | 2.86%   |
| Arm Cortex-A53 r0p4 (v8-A)            | 2         | 2.86%   |
| AMD 686-class                         | 2         | 2.86%   |
| Intel Xeon CPU E5-2630L v3 @ 1.80GHz  | 1         | 1.43%   |
| Intel Xeon CPU E5-2450L 0 @ 1.80GHz   | 1         | 1.43%   |
| Intel Pentium M processor 1.60GHz     | 1         | 1.43%   |
| Intel Pentium M processor             | 1         | 1.43%   |
| Intel Pentium III                     | 1         | 1.43%   |
| Intel Pentium CPU 2020M @ 2.40GHz     | 1         | 1.43%   |
| Intel N100                            | 1         | 1.43%   |
| Intel Core i7-6700K CPU @ 4.00GHz     | 1         | 1.43%   |
| Intel Core i7-5557U CPU @ 3.10GHz     | 1         | 1.43%   |
| Intel Core i7-5500U CPU @ 2.40GHz     | 1         | 1.43%   |
| Intel Core i7-3770 CPU @ 3.40GHz      | 1         | 1.43%   |
| Intel Core i7-3520M CPU @ 2.90GHz     | 1         | 1.43%   |
| Intel Core i7-2640M CPU @ 2.80GHz     | 1         | 1.43%   |
| Intel Core i5-9400T CPU @ 1.80GHz     | 1         | 1.43%   |
| Intel Core i5-7400 CPU @ 3.00GHz      | 1         | 1.43%   |
| Intel Core i5-6300U CPU @ 2.40GHz     | 1         | 1.43%   |
| Intel Core i5-6200U CPU @ 2.30GHz     | 1         | 1.43%   |
| Intel Core i5-4310M CPU @ 2.70GHz     | 1         | 1.43%   |
| Intel Core i5-4300U CPU @ 1.90GHz     | 1         | 1.43%   |
| Intel Core i5-3320M CPU @ 2.60GHz     | 1         | 1.43%   |
| Intel Core i5-2320 CPU @ 3.00GHz      | 1         | 1.43%   |
| Intel Core i5 CPU M 560 @ 2.67GH      | 1         | 1.43%   |
| Intel Core i5 CPU M 540 @ 2.53GHz     | 1         | 1.43%   |
| Intel Core i3-4150 CPU @ 3.50GHz      | 1         | 1.43%   |
| Intel Core i3-3220T CPU @ 2.80GHz     | 1         | 1.43%   |
| Intel Core i3-3217U CPU @ 1.80GHz     | 1         | 1.43%   |
| Intel Core 2 CPU T7200 @ 2.00GHz      | 1         | 1.43%   |
| Intel Core 2 CPU T7                   | 1         | 1.43%   |
| Intel Celeron CPU N2830 @ 2.16GHz     | 1         | 1.43%   |
| AMD Tillamook                         | 1         | 1.43%   |
| AMD Sempron 145 Processor             | 1         | 1.43%   |
| AMD Ryzen 9 3900X 12-Core Processor   | 1         | 1.43%   |
| AMD Ryzen 7 2700 Eight-Core Processor | 1         | 1.43%   |
| AMD Ryzen 5 3600 6-Core Processor     | 1         | 1.43%   |
| AMD Ryzen 5 2600 Six-Core Processor   | 1         | 1.43%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart_bsd/cpu_family.svg)


| Model             | Computers | Percent |
|-------------------|-----------|---------|
| Intel 686-class   | 16        | 22.86%  |
| Other             | 10        | 14.29%  |
| Intel Core i5     | 10        | 14.29%  |
| Intel Core i7     | 6         | 8.57%   |
| Intel Core i3     | 3         | 4.29%   |
| AMD Ryzen 3       | 3         | 4.29%   |
| Intel Xeon        | 2         | 2.86%   |
| Intel Pentium M   | 2         | 2.86%   |
| Intel Core 2      | 2         | 2.86%   |
| AMD Ryzen 5       | 2         | 2.86%   |
| AMD 686-class     | 2         | 2.86%   |
| Intel Pentium III | 1         | 1.43%   |
| Intel Pentium     | 1         | 1.43%   |
| Intel Celeron     | 1         | 1.43%   |
| AMD Sempron       | 1         | 1.43%   |
| AMD Ryzen 9       | 1         | 1.43%   |
| AMD Ryzen 7       | 1         | 1.43%   |
| AMD Phenom II X6  | 1         | 1.43%   |
| AMD Phenom II X4  | 1         | 1.43%   |
| AMD FX            | 1         | 1.43%   |
| AMD E             | 1         | 1.43%   |
| AMD Athlon II     | 1         | 1.43%   |
| AMD A10           | 1         | 1.43%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart_bsd/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| Unknown | 35        | 50%     |
| 2       | 16        | 22.86%  |
| 4       | 11        | 15.71%  |
| 8       | 4         | 5.71%   |
| 6       | 3         | 4.29%   |
| 12      | 1         | 1.43%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart_bsd/cpu_sockets.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 46        | 65.71%  |
| Unknown | 24        | 34.29%  |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart_bsd/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| Unknown | 35        | 50%     |
| 2       | 20        | 28.57%  |
| 1       | 15        | 21.43%  |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart_bsd/cpu_microarch.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| Unknown     | 30        | 42.86%  |
| IvyBridge   | 6         | 8.57%   |
| Zen+        | 3         | 4.29%   |
| Skylake     | 3         | 4.29%   |
| SandyBridge | 3         | 4.29%   |
| P6          | 3         | 4.29%   |
| K10         | 3         | 4.29%   |
| Haswell     | 3         | 4.29%   |
| Zen 2       | 2         | 2.86%   |
| Zen         | 2         | 2.86%   |
| Piledriver  | 2         | 2.86%   |
| KabyLake    | 2         | 2.86%   |
| Core        | 2         | 2.86%   |
| Broadwell   | 2         | 2.86%   |
| Westmere    | 1         | 1.43%   |
| Silvermont  | 1         | 1.43%   |
| Geode       | 1         | 1.43%   |
| Bobcat      | 1         | 1.43%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart_bsd/gpu_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Intel                      | 37        | 54.41%  |
| AMD                        | 17        | 25%     |
| Nvidia                     | 11        | 16.18%  |
| VIA Technologies           | 1         | 1.47%   |
| Trident Microsystems       | 1         | 1.47%   |
| Matrox Electronics Systems | 1         | 1.47%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart_bsd/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 3rd Gen Core processor Graphics Controller                                         | 5         | 7.04%   |
| Intel HD Graphics 530                                                                    | 3         | 4.23%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 3         | 4.23%   |
| Nvidia GF114 [GeForce GTX 560]                                                           | 2         | 2.82%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 2         | 2.82%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 2         | 2.82%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 2         | 2.82%   |
| Intel Mobile 945GM/GMS, 943/940GML Express Integrated Graphics Controller                | 2         | 2.82%   |
| Intel JasperLake [UHD Graphics]                                                          | 2         | 2.82%   |
| Intel Iris Graphics 6100                                                                 | 2         | 2.82%   |
| Intel Alder Lake-N [UHD Graphics]                                                        | 2         | 2.82%   |
| Intel 82852/855GM Integrated Graphics Device                                             | 2         | 2.82%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 2         | 2.82%   |
| VIA Technologies CN400/PM800/PM880/PN800/PN880 [S3 UniChrome Pro]                        | 1         | 1.41%   |
| Trident Microsystems TGUI 9660/938x/968x                                                 | 1         | 1.41%   |
| Nvidia NV18 [GeForce4 MX 440 AGP 8x]                                                     | 1         | 1.41%   |
| Nvidia GT218M [NVS 3100M]                                                                | 1         | 1.41%   |
| Nvidia GT216GLM [Quadro FX 880M]                                                         | 1         | 1.41%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 1         | 1.41%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 1         | 1.41%   |
| Nvidia GM204 [GeForce GTX 970]                                                           | 1         | 1.41%   |
| Nvidia GK208BM [GeForce 920M]                                                            | 1         | 1.41%   |
| Nvidia G86 [GeForce 8500 GT]                                                             | 1         | 1.41%   |
| Nvidia C61 [GeForce 7025 / nForce 630a]                                                  | 1         | 1.41%   |
| Matrox Electronics Systems G200eR2                                                       | 1         | 1.41%   |
| Intel IvyBridge GT2 [HD Graphics 4000]                                                   | 1         | 1.41%   |
| Intel HD Graphics 630                                                                    | 1         | 1.41%   |
| Intel HD Graphics 6000                                                                   | 1         | 1.41%   |
| Intel HD Graphics 5500                                                                   | 1         | 1.41%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 1         | 1.41%   |
| Intel GeminiLake [UHD Graphics 605]                                                      | 1         | 1.41%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                                 | 1         | 1.41%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 1         | 1.41%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 1         | 1.41%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 1         | 1.41%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 1         | 1.41%   |
| Intel Apollo Lake [HD Graphics 505]                                                      | 1         | 1.41%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 1         | 1.41%   |
| AMD Wrestler [Radeon HD 6320]                                                            | 1         | 1.41%   |
| AMD Wrestler [Radeon HD 6250]                                                            | 1         | 1.41%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart_bsd/gpu_combo.svg)


| Name                     | Computers | Percent |
|--------------------------|-----------|---------|
| 1 x Intel                | 30        | 44.12%  |
| 1 x AMD                  | 14        | 20.59%  |
| 1 x Nvidia               | 8         | 11.76%  |
| Other                    | 7         | 10.29%  |
| 2 x Intel                | 2         | 2.94%   |
| Intel + Nvidia           | 2         | 2.94%   |
| 2 x AMD                  | 1         | 1.47%   |
| 1 x VIA                  | 1         | 1.47%   |
| 1 x Trident Microsystems | 1         | 1.47%   |
| 1 x Matrox               | 1         | 1.47%   |
| Intel + AMD              | 1         | 1.47%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart_bsd/gpu_driver.svg)


| Driver  | Computers | Percent |
|---------|-----------|---------|
| Free    | 49        | 70%     |
| Unknown | 21        | 30%     |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart_bsd/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 33        | 47.83%  |
| 1.01-2.0   | 12        | 17.39%  |
| 0.01-0.5   | 10        | 14.49%  |
| 3.01-4.0   | 8         | 11.59%  |
| 0.51-1.0   | 5         | 7.25%   |
| 7.01-8.0   | 1         | 1.45%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart_bsd/mon_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 7         | 25%     |
| LG Display          | 6         | 21.43%  |
| Goldstar            | 4         | 14.29%  |
| Chimei Innolux      | 2         | 7.14%   |
| Apple               | 2         | 7.14%   |
| ViewSonic           | 1         | 3.57%   |
| Unknown (CDD)       | 1         | 3.57%   |
| LG Philips          | 1         | 3.57%   |
| Lenovo              | 1         | 3.57%   |
| Impression          | 1         | 3.57%   |
| Dell                | 1         | 3.57%   |
| Acer                | 1         | 3.57%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart_bsd/mon_model.svg)


| Model                                                                 | Computers | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| Samsung Electronics LCD Monitor SAM0C39 1920x1080 890x500mm 40.2-inch | 2         | 7.14%   |
| ViewSonic VG2439 Series VSCD22B 1920x1080 520x290mm 23.4-inch         | 1         | 3.57%   |
| Unknown (CDD) VGA CDD0030 1920x1080 1150x650mm 52.0-inch              | 1         | 3.57%   |
| Samsung Electronics SyncMaster SAM01AE 1600x1200 410x310mm 20.2-inch  | 1         | 3.57%   |
| Samsung Electronics SMS27A350H SAM07CE 1920x1080 600x340mm 27.2-inch  | 1         | 3.57%   |
| Samsung Electronics S23C570 SAM0A56 1920x1080 510x290mm 23.1-inch     | 1         | 3.57%   |
| Samsung Electronics LCD Monitor SEC324C 1600x900 310x170mm 13.9-inch  | 1         | 3.57%   |
| Samsung Electronics LCD Monitor SDC4752 1366x768 340x190mm 15.3-inch  | 1         | 3.57%   |
| LG Philips LCD Monitor LPLDD00 1280x800 330x210mm 15.4-inch           | 1         | 3.57%   |
| LG Display LCD Monitor LGD40A0 1366x768 310x170mm 13.9-inch           | 1         | 3.57%   |
| LG Display LCD Monitor LGD0521 1920x1080 310x170mm 13.9-inch          | 1         | 3.57%   |
| LG Display LCD Monitor LGD045E 1366x768 310x170mm 13.9-inch           | 1         | 3.57%   |
| LG Display LCD Monitor LGD03CD 1366x768 280x160mm 12.7-inch           | 1         | 3.57%   |
| LG Display LCD Monitor LGD0335 1366x768 310x170mm 13.9-inch           | 1         | 3.57%   |
| LG Display LCD Monitor LGD029E 1600x900 340x190mm 15.3-inch           | 1         | 3.57%   |
| Lenovo LCD Monitor LEN40B1 1600x900 340x190mm 15.3-inch               | 1         | 3.57%   |
| Impression R19W11 IMP1911 1440x900 410x260mm 19.1-inch                | 1         | 3.57%   |
| Goldstar W1952 GSM4B78 1440x900 410x260mm 19.1-inch                   | 1         | 3.57%   |
| Goldstar LG ULTRAWIDE GSM59F1 2560x1080 670x280mm 28.6-inch           | 1         | 3.57%   |
| Goldstar LCD Monitor GSM5AB6 1920x1080 480x270mm 21.7-inch            | 1         | 3.57%   |
| Goldstar L194WT GSM4B05 1440x900 410x260mm 19.1-inch                  | 1         | 3.57%   |
| Dell P2419H DELD0DA 1920x1080 530x300mm 24.0-inch                     | 1         | 3.57%   |
| Chimei Innolux LCD Monitor CMN15AB 1366x768 340x190mm 15.3-inch       | 1         | 3.57%   |
| Chimei Innolux LCD Monitor CMN1472 1366x768 310x170mm 13.9-inch       | 1         | 3.57%   |
| Apple LCD Monitor APP9C5F 1280x800 290x180mm 13.4-inch                | 1         | 3.57%   |
| Apple Color LCD APPA029 2560x1600 290x180mm 13.4-inch                 | 1         | 3.57%   |
| Acer SB220Q ACR06AB 1920x1080 480x270mm 21.7-inch                     | 1         | 3.57%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart_bsd/mon_resolution.svg)


| Resolution       | Computers | Percent |
|------------------|-----------|---------|
| 1920x1080 (FHD)  | 10        | 35.71%  |
| 1366x768 (WXGA)  | 7         | 25%     |
| 1600x900 (HD+)   | 3         | 10.71%  |
| 1440x900 (WXGA+) | 3         | 10.71%  |
| 1280x800 (WXGA)  | 2         | 7.14%   |
| 2560x1600        | 1         | 3.57%   |
| 2560x1080        | 1         | 3.57%   |
| 1600x1200        | 1         | 3.57%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart_bsd/mon_diagonal.svg)


| Inches | Computers | Percent |
|--------|-----------|---------|
| 13     | 8         | 28.57%  |
| 15     | 5         | 17.86%  |
| 19     | 3         | 10.71%  |
| 40     | 2         | 7.14%   |
| 23     | 2         | 7.14%   |
| 21     | 2         | 7.14%   |
| 52     | 1         | 3.57%   |
| 34     | 1         | 3.57%   |
| 27     | 1         | 3.57%   |
| 24     | 1         | 3.57%   |
| 20     | 1         | 3.57%   |
| 12     | 1         | 3.57%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart_bsd/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 11        | 39.29%  |
| 401-500     | 6         | 21.43%  |
| 501-600     | 4         | 14.29%  |
| 201-300     | 3         | 10.71%  |
| 801-900     | 2         | 7.14%   |
| 701-800     | 1         | 3.57%   |
| 1001-1500   | 1         | 3.57%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart_bsd/mon_ratio.svg)


| Ratio | Computers | Percent |
|-------|-----------|---------|
| 16/9  | 20        | 71.43%  |
| 16/10 | 6         | 21.43%  |
| 4/3   | 1         | 3.57%   |
| 21/9  | 1         | 3.57%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart_bsd/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 81-90          | 8         | 28.57%  |
| 201-250        | 5         | 17.86%  |
| 151-200        | 4         | 14.29%  |
| 101-110        | 3         | 10.71%  |
| 501-1000       | 2         | 7.14%   |
| 91-100         | 2         | 7.14%   |
| More than 1000 | 1         | 3.57%   |
| 61-70          | 1         | 3.57%   |
| 351-500        | 1         | 3.57%   |
| 301-350        | 1         | 3.57%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart_bsd/mon_density.svg)


| Density | Computers | Percent |
|---------|-----------|---------|
| 51-100  | 13        | 46.43%  |
| 101-120 | 10        | 35.71%  |
| 121-160 | 3         | 10.71%  |
| 1-50    | 1         | 3.57%   |
| 161-240 | 1         | 3.57%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart_bsd/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 38        | 55.07%  |
| 0     | 30        | 43.48%  |
| 2     | 1         | 1.45%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart_bsd/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 33        | 35.48%  |
| Intel                             | 29        | 31.18%  |
| Qualcomm Atheros                  | 12        | 12.9%   |
| Broadcom                          | 6         | 6.45%   |
| Huawei Technologies               | 3         | 3.23%   |
| VIA Technologies                  | 1         | 1.08%   |
| TP-Link                           | 1         | 1.08%   |
| Oculus VR                         | 1         | 1.08%   |
| Netchip Technology                | 1         | 1.08%   |
| Mercucys                          | 1         | 1.08%   |
| Marvell Technology Group          | 1         | 1.08%   |
| Ericsson Business Mobile Networks | 1         | 1.08%   |
| D-Link                            | 1         | 1.08%   |
| Apple                             | 1         | 1.08%   |
| 3Com                              | 1         | 1.08%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart_bsd/net_model.svg)


| Model                                                                                 | Computers | Percent |
|---------------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller                     | 30        | 25.64%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)                                 | 6         | 5.13%   |
| Intel I211 Gigabit Network Connection                                                 | 3         | 2.56%   |
| Huawei USB Device                                                                     | 3         | 2.56%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                                 | 2         | 1.71%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                            | 2         | 1.71%   |
| Qualcomm Atheros AR2413/AR2414 Wireless Network Adapter [AR5005G(S) 802.11bg]         | 2         | 1.71%   |
| Intel Wireless-AC 9260                                                                | 2         | 1.71%   |
| Intel Wireless 8260                                                                   | 2         | 1.71%   |
| Intel Wireless 7265                                                                   | 2         | 1.71%   |
| Intel Wi-Fi 6 AX201 160MHz                                                            | 2         | 1.71%   |
| Intel Ethernet Connection (2) I219-LM                                                 | 2         | 1.71%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                                      | 2         | 1.71%   |
| Intel Centrino Ultimate-N 6300                                                        | 2         | 1.71%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                                          | 2         | 1.71%   |
| Intel Cannon Lake PCH CNVi WiFi                                                       | 2         | 1.71%   |
| VIA VT6102/VT6103 [Rhine-II]                                                          | 1         | 0.85%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                                          | 1         | 0.85%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter                              | 1         | 0.85%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                                       | 1         | 0.85%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                                                | 1         | 0.85%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                                   | 1         | 0.85%   |
| Realtek RTL8188EE Wireless Network Adapter                                            | 1         | 0.85%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                                               | 1         | 0.85%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                                 | 1         | 0.85%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                                                | 1         | 0.85%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller                             | 1         | 0.85%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                                      | 1         | 0.85%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                                      | 1         | 0.85%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)                        | 1         | 0.85%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                        | 1         | 0.85%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                         | 1         | 0.85%   |
| Qualcomm Atheros AR5418 Wireless Network Adapter [AR5008E 802.11(a)bgn] (PCI-Express) | 1         | 0.85%   |
| Oculus VR Rift S                                                                      | 1         | 0.85%   |
| Netchip Linux-USB Serial Gadget (CDC ACM mode)                                        | 1         | 0.85%   |
| Mercucys MERCUSYS Wireless USB Adapter                                                | 1         | 0.85%   |
| Marvell Group 88E8053 PCI-E Gigabit Ethernet Controller                               | 1         | 0.85%   |
| Intel Wireless 7260                                                                   | 1         | 0.85%   |
| Intel Wi-Fi 6 AX200                                                                   | 1         | 0.85%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                                 | 1         | 0.85%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart_bsd/net_wireless_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Intel                 | 22        | 51.16%  |
| Qualcomm Atheros      | 9         | 20.93%  |
| Realtek Semiconductor | 5         | 11.63%  |
| Broadcom              | 4         | 9.3%    |
| TP-Link               | 1         | 2.33%   |
| Mercucys              | 1         | 2.33%   |
| D-Link                | 1         | 2.33%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart_bsd/net_wireless_model.svg)


| Model                                                                                 | Computers | Percent |
|---------------------------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                            | 2         | 4.55%   |
| Qualcomm Atheros AR2413/AR2414 Wireless Network Adapter [AR5005G(S) 802.11bg]         | 2         | 4.55%   |
| Intel Wireless-AC 9260                                                                | 2         | 4.55%   |
| Intel Wireless 8260                                                                   | 2         | 4.55%   |
| Intel Wireless 7265                                                                   | 2         | 4.55%   |
| Intel Wi-Fi 6 AX201 160MHz                                                            | 2         | 4.55%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                                      | 2         | 4.55%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                                          | 2         | 4.55%   |
| Intel Cannon Lake PCH CNVi WiFi                                                       | 2         | 4.55%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                                          | 1         | 2.27%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter                              | 1         | 2.27%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                                       | 1         | 2.27%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                                                | 1         | 2.27%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                                   | 1         | 2.27%   |
| Realtek RTL8188EE Wireless Network Adapter                                            | 1         | 2.27%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                                               | 1         | 2.27%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                                      | 1         | 2.27%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                                      | 1         | 2.27%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)                        | 1         | 2.27%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                        | 1         | 2.27%   |
| Qualcomm Atheros AR5418 Wireless Network Adapter [AR5008E 802.11(a)bgn] (PCI-Express) | 1         | 2.27%   |
| Mercucys MERCUSYS Wireless USB Adapter                                                | 1         | 2.27%   |
| Intel Wireless 7260                                                                   | 1         | 2.27%   |
| Intel Wi-Fi 6 AX200                                                                   | 1         | 2.27%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                                 | 1         | 2.27%   |
| Intel PRO/Wireless 2200BG [Calexico2] Network Connection                              | 1         | 2.27%   |
| Intel Gemini Lake PCH CNVi WiFi                                                       | 1         | 2.27%   |
| Intel CNVi: Wi-Fi                                                                     | 1         | 2.27%   |
| Intel Centrino Wireless-N 135                                                         | 1         | 2.27%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                                          | 1         | 2.27%   |
| D-Link DWA-131 Wireless N Nano Adapter (Rev. E1) [Realtek RTL8192EU]                  | 1         | 2.27%   |
| Broadcom BCM43602 802.11ac Wireless LAN SoC                                           | 1         | 2.27%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                                    | 1         | 2.27%   |
| Broadcom BCM4331 802.11a/b/g/n                                                        | 1         | 2.27%   |
| Broadcom BCM43142 802.11b/g/n                                                         | 1         | 2.27%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart_bsd/net_ethernet_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 33        | 50%     |
| Intel                    | 20        | 30.3%   |
| Qualcomm Atheros         | 3         | 4.55%   |
| Huawei Technologies      | 3         | 4.55%   |
| Broadcom                 | 3         | 4.55%   |
| VIA Technologies         | 1         | 1.52%   |
| Marvell Technology Group | 1         | 1.52%   |
| Apple                    | 1         | 1.52%   |
| 3Com                     | 1         | 1.52%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart_bsd/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 30        | 44.78%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 6         | 8.96%   |
| Intel I211 Gigabit Network Connection                             | 3         | 4.48%   |
| Huawei USB Device                                                 | 3         | 4.48%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 2         | 2.99%   |
| Intel Ethernet Connection (2) I219-LM                             | 2         | 2.99%   |
| VIA VT6102/VT6103 [Rhine-II]                                      | 1         | 1.49%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 1         | 1.49%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                            | 1         | 1.49%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 1         | 1.49%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 1         | 1.49%   |
| Marvell Group 88E8053 PCI-E Gigabit Ethernet Controller           | 1         | 1.49%   |
| Intel PRO/100 VE Network Connection                               | 1         | 1.49%   |
| Intel Ethernet Controller I225-V                                  | 1         | 1.49%   |
| Intel Ethernet Connection I219-V                                  | 1         | 1.49%   |
| Intel Ethernet Connection I219-LM                                 | 1         | 1.49%   |
| Intel Ethernet Connection I218-LM                                 | 1         | 1.49%   |
| Intel Ethernet Connection I217-V                                  | 1         | 1.49%   |
| Intel Ethernet Connection (3) I218-V                              | 1         | 1.49%   |
| Intel 82801DB PRO/100 VE (MOB) Ethernet Controller                | 1         | 1.49%   |
| Intel 82577LM Gigabit Network Connection                          | 1         | 1.49%   |
| Intel 82574L Gigabit Network Connection                           | 1         | 1.49%   |
| Broadcom NetXtreme BCM57766 Gigabit Ethernet PCIe                 | 1         | 1.49%   |
| Broadcom NetXtreme BCM5720 Gigabit Ethernet PCIe                  | 1         | 1.49%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 1         | 1.49%   |
| Apple Ethernet Adapter [A1277]                                    | 1         | 1.49%   |
| 3Com 3c905C-TX/TX-M [Tornado]                                     | 1         | 1.49%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart_bsd/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 61        | 57.01%  |
| WiFi     | 40        | 37.38%  |
| Modem    | 4         | 3.74%   |
| Unknown  | 2         | 1.87%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart_bsd/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 49        | 71.01%  |
| WiFi     | 19        | 27.54%  |
| Unknown  | 1         | 1.45%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart_bsd/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 32        | 47.06%  |
| 1     | 21        | 30.88%  |
| 0     | 10        | 14.71%  |
| 3     | 5         | 7.35%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart_bsd/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 56        | 81.16%  |
| Yes  | 13        | 18.84%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart_bsd/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 14        | 53.85%  |
| Apple                           | 4         | 15.38%  |
| Realtek Semiconductor           | 2         | 7.69%   |
| Broadcom                        | 2         | 7.69%   |
| Qualcomm Atheros Communications | 1         | 3.85%   |
| Lite-On Technology              | 1         | 3.85%   |
| IMC Networks                    | 1         | 3.85%   |
| Cambridge Silicon Radio         | 1         | 3.85%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart_bsd/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 5         | 19.23%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 4         | 15.38%  |
| Intel Wireless-AC 3168 Bluetooth                    | 2         | 7.69%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 2         | 7.69%   |
| Apple Broadcom Built-in Bluetooth                   | 2         | 7.69%   |
| Realtek Bluetooth Adapter                           | 1         | 3.85%   |
| Realtek Bluetooth 4.0 Adapter                       | 1         | 3.85%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 1         | 3.85%   |
| Lite-On Atheros AR3012 Bluetooth                    | 1         | 3.85%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 1         | 3.85%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 1         | 3.85%   |
| Intel AX201 Bluetooth                               | 1         | 3.85%   |
| IMC Networks Qualcomm Atheros Bluetooth 4.0 + HS    | 1         | 3.85%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 1         | 3.85%   |
| Apple Built-in iSight (no firmware loaded)          | 1         | 3.85%   |
| Apple Bluetooth Host Controller                     | 1         | 3.85%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart_bsd/snd_vendor.svg)


| Vendor                                       | Computers | Percent |
|----------------------------------------------|-----------|---------|
| Intel                                        | 44        | 57.14%  |
| AMD                                          | 19        | 24.68%  |
| Nvidia                                       | 7         | 9.09%   |
| Zoran Co. Personal Media Division (Nogatech) | 1         | 1.3%    |
| Yamaha                                       | 1         | 1.3%    |
| VIA Technologies                             | 1         | 1.3%    |
| Samsung Electronics                          | 1         | 1.3%    |
| Native Instruments                           | 1         | 1.3%    |
| Logitech                                     | 1         | 1.3%    |
| ESS Technology                               | 1         | 1.3%    |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart_bsd/snd_model.svg)


| Model                                                                                             | Computers | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 8         | 8.25%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 6         | 6.19%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 4         | 4.12%   |
| Intel Broadwell-U Audio Controller                                                                | 4         | 4.12%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 4         | 4.12%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                                               | 4         | 4.12%   |
| Intel Cannon Lake PCH cAVS                                                                        | 3         | 3.09%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 3         | 3.09%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 3         | 3.09%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                                        | 3         | 3.09%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 2         | 2.06%   |
| Nvidia GF114 HDMI Audio Controller                                                                | 2         | 2.06%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 2         | 2.06%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 2         | 2.06%   |
| Intel Jasper Lake HD Audio                                                                        | 2         | 2.06%   |
| Intel Alder Lake-N HD Graphics SGPC                                                               | 2         | 2.06%   |
| Intel 82801DB/DBL/DBM (ICH4/ICH4-L/ICH4-M) AC'97 Audio Controller                                 | 2         | 2.06%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 2         | 2.06%   |
| AMD Wrestler HDMI Audio                                                                           | 2         | 2.06%   |
| AMD Starship/Matisse HD Audio Controller                                                          | 2         | 2.06%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 2         | 2.06%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]                           | 2         | 2.06%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 2         | 2.06%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                                            | 2         | 2.06%   |
| AMD Caicos HDMI Audio [Radeon HD 6450 / 7450/8450/8490 OEM / R5 230/235/235X OEM]                 | 2         | 2.06%   |
| Zoran Co. Personal Media Division (Nogatech) USB Audio and HID                                    | 1         | 1.03%   |
| Yamaha AG06/AG03                                                                                  | 1         | 1.03%   |
| VIA Technologies VT8233/A/8235/8237 AC97 Audio Controller                                         | 1         | 1.03%   |
| Samsung Electronics Samsung Type-C to 3.5pi gender adapter                                        | 1         | 1.03%   |
| Nvidia High Definition Audio Controller                                                           | 1         | 1.03%   |
| Nvidia GT216 HDMI Audio Controller                                                                | 1         | 1.03%   |
| Nvidia GM204 High Definition Audio Controller                                                     | 1         | 1.03%   |
| Native Instruments Komplete Audio 1                                                               | 1         | 1.03%   |
| Logitech Zone Wired Earbuds                                                                       | 1         | 1.03%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 1         | 1.03%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 1         | 1.03%   |
| Intel Comet Lake PCH-V cAVS                                                                       | 1         | 1.03%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 1         | 1.03%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 1         | 1.03%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 1         | 1.03%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart_bsd/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Unknown             | 8         | 15.09%  |
| Kingston            | 8         | 15.09%  |
| Crucial             | 7         | 13.21%  |
| Samsung Electronics | 6         | 11.32%  |
| Micron Technology   | 5         | 9.43%   |
| SK hynix            | 4         | 7.55%   |
| G.Skill             | 3         | 5.66%   |
| A-DATA Technology   | 3         | 5.66%   |
| Ramaxel Technology  | 2         | 3.77%   |
| Patriot             | 2         | 3.77%   |
| Corsair             | 2         | 3.77%   |
| SHARETRONIC         | 1         | 1.89%   |
| Nanya Technology    | 1         | 1.89%   |
| Unknown             | 1         | 1.89%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart_bsd/memory_model.svg)


| Model                                                      | Computers | Percent |
|------------------------------------------------------------|-----------|---------|
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1867MT/s      | 2         | 3.51%   |
| Micron RAM Module 8GB Chip LPDDR4                          | 2         | 3.51%   |
| Unknown RAM Module 8192MB DIMM 400MT/s                     | 1         | 1.75%   |
| Unknown RAM Module 512MB SODIMM DRAM 166MT/s               | 1         | 1.75%   |
| Unknown RAM Module 512MB SODIMM DDR2 533MT/s               | 1         | 1.75%   |
| Unknown RAM Module 2GB SODIMM DDR3                         | 1         | 1.75%   |
| Unknown RAM Module 256MB SODIMM DDR                        | 1         | 1.75%   |
| Unknown RAM Module 2048MB DIMM DDR2 800MT/s                | 1         | 1.75%   |
| Unknown RAM Module 2048MB DIMM 400MT/s                     | 1         | 1.75%   |
| Unknown RAM Module 128MB DIMM DRAM                         | 1         | 1.75%   |
| Unknown RAM Module 1024MB SODIMM SDRAM 266MT/s             | 1         | 1.75%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s     | 1         | 1.75%   |
| SK hynix RAM HMT351S6BFR8C-H9 4GB SODIMM DDR3 1334MT/s     | 1         | 1.75%   |
| SK hynix RAM HMT351S6BFR8C-H9 4GB SODIMM DDR3 1333MT/s     | 1         | 1.75%   |
| SK hynix RAM HMT325S6EFR8A-PB 2GB SODIMM DDR3 1600MT/s     | 1         | 1.75%   |
| SHARETRONIC RAM Module 2048MB SODIMM DDR3 1600MT/s         | 1         | 1.75%   |
| Samsung RAM M471B5673FH0-CF8 2GB SODIMM 1067MT/s           | 1         | 1.75%   |
| Samsung RAM M471B5273EB0-CK0 4GB SODIMM DDR3 1600MT/s      | 1         | 1.75%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s      | 1         | 1.75%   |
| Samsung RAM M386B4G70DM0-YK04 32GB DIMM DDR3 1600MT/s      | 1         | 1.75%   |
| Samsung RAM M386B4G70DM0-YK03 32GB DIMM DDR3 1600MT/s      | 1         | 1.75%   |
| Ramaxel RAM RMT3160ED58E9W1600 4GB SODIMM DDR3 1600MT/s    | 1         | 1.75%   |
| Ramaxel RAM RMSA3230KB78HAF2133 8GB SODIMM DDR4 2133MT/s   | 1         | 1.75%   |
| Patriot RAM PSD44G213382 4096MB DIMM DDR4 2133MT/s         | 1         | 1.75%   |
| Patriot RAM PSD34G13332 4GB DIMM DDR3 1333MT/s             | 1         | 1.75%   |
| Nanya RAM NT2GC64B88B0NS-CG 2GB SODIMM DDR3 1334MT/s       | 1         | 1.75%   |
| Micron RAM 8KTF51264HZ-1G6N1 4GB SODIMM DDR3 1600MT/s      | 1         | 1.75%   |
| Micron RAM 36ASF2G72PZ-2G1A2 16GB DIMM DDR4 2133MT/s       | 1         | 1.75%   |
| Micron RAM 16JSF51264HZ-1G1D1 4GB SODIMM DDR3 1067MT/s     | 1         | 1.75%   |
| Kingston RAM KHX2400C15/8G 8GB DIMM DDR4 2400MT/s          | 1         | 1.75%   |
| Kingston RAM KHX1600C9D3/4GX 4GB DIMM DDR3 1600MT/s        | 1         | 1.75%   |
| Kingston RAM ACR26D4S9S8ME-8 8GB SODIMM DDR4 2667MT/s      | 1         | 1.75%   |
| Kingston RAM ACR16D3LS1KFG/4G 4GB DIMM DDR3 1600MT/s       | 1         | 1.75%   |
| Kingston RAM ACR16D3LFS1KBG/2G 2GB SODIMM DDR3 1600MT/s    | 1         | 1.75%   |
| Kingston RAM 99U5701-077.A00G 16GB DIMM DDR4 2667MT/s      | 1         | 1.75%   |
| Kingston RAM 99U5471-028.A00LF 4GB DIMM DDR3 667MT/s       | 1         | 1.75%   |
| Kingston RAM 9905471-011.A00LF 4GB DIMM DDR3 1333MT/s      | 1         | 1.75%   |
| Kingston RAM 9905428-026.A02LF 2048MB SODIMM DDR3 1066MT/s | 1         | 1.75%   |
| G.Skill RAM F4-3200C16-16GVK 16GB DIMM DDR4 3200MT/s       | 1         | 1.75%   |
| G.Skill RAM F4-2800C17-8GVR 8192MB DIMM DDR4 2133MT/s      | 1         | 1.75%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart_bsd/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR3    | 21        | 46.67%  |
| DDR4    | 15        | 33.33%  |
| LPDDR4  | 2         | 4.44%   |
| DRAM    | 2         | 4.44%   |
| DDR2    | 2         | 4.44%   |
| SDRAM   | 1         | 2.22%   |
| DDR     | 1         | 2.22%   |
| Unknown | 1         | 2.22%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart_bsd/memory_formfactor.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| DIMM   | 22        | 48.89%  |
| SODIMM | 20        | 44.44%  |
| Chip   | 3         | 6.67%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart_bsd/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 17        | 36.17%  |
| 4096  | 13        | 27.66%  |
| 2048  | 7         | 14.89%  |
| 16384 | 4         | 8.51%   |
| 512   | 2         | 4.26%   |
| 32768 | 1         | 2.13%   |
| 1024  | 1         | 2.13%   |
| 256   | 1         | 2.13%   |
| 128   | 1         | 2.13%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart_bsd/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 13        | 25%     |
| 2133    | 5         | 9.62%   |
| Unknown | 5         | 9.62%   |
| 1333    | 4         | 7.69%   |
| 3200    | 3         | 5.77%   |
| 2667    | 3         | 5.77%   |
| 2400    | 2         | 3.85%   |
| 1867    | 2         | 3.85%   |
| 1334    | 2         | 3.85%   |
| 1067    | 2         | 3.85%   |
| 800     | 2         | 3.85%   |
| 3000    | 1         | 1.92%   |
| 2933    | 1         | 1.92%   |
| 2666    | 1         | 1.92%   |
| 1066    | 1         | 1.92%   |
| 667     | 1         | 1.92%   |
| 533     | 1         | 1.92%   |
| 400     | 1         | 1.92%   |
| 266     | 1         | 1.92%   |
| 166     | 1         | 1.92%   |

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


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Canon  | 2         | 100%    |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart_bsd/scanner_model.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Canon CanoScan LiDE 210 | 2         | 100%    |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart_bsd/camera_vendor.svg)


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

![Camera Model](./images/pie_chart_bsd/camera_model.svg)


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

![Fingerprint Vendor](./images/pie_chart_bsd/fingerprint_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Upek   | 1         | 100%    |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart_bsd/fingerprint_model.svg)


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

![Unsupported Devices](./images/pie_chart_bsd/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 24        | 34.78%  |
| 1     | 20        | 28.99%  |
| 2     | 15        | 21.74%  |
| 3     | 6         | 8.7%    |
| 5     | 2         | 2.9%    |
| 4     | 2         | 2.9%    |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart_bsd/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Communication controller | 37        | 48.68%  |
| Net/wireless             | 20        | 26.32%  |
| Card reader              | 7         | 9.21%   |
| Graphics card            | 5         | 6.58%   |
| Storage                  | 2         | 2.63%   |
| Net/ethernet             | 2         | 2.63%   |
| Wireless                 | 1         | 1.32%   |
| Modem                    | 1         | 1.32%   |
| Bluetooth                | 1         | 1.32%   |

