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

Total: 98

| Vendor        | Model                       | Form-Factor | Probe                                                     | Date         |
|---------------|-----------------------------|-------------|-----------------------------------------------------------|--------------|
| ASRock        | H270 Pro4                   | Desktop     | [cba80ecde3](https://bsd-hardware.info/?probe=cba80ecde3) | Sep 24, 2023 |
| Unknown       | Unknown                     | Desktop     | [dcf1ebd901](https://bsd-hardware.info/?probe=dcf1ebd901) | Sep 20, 2023 |
| Unknown       | Unknown                     | Desktop     | [1808e7891c](https://bsd-hardware.info/?probe=1808e7891c) | Sep 16, 2023 |
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

![OS](./All/images/pie_chart_bsd/os_name.svg)


| Name              | Computers | Percent |
|-------------------|-----------|---------|
| NetBSD 9.2        | 13        | 16.25%  |
| NetBSD 9.3        | 11        | 13.75%  |
| NetBSD 9.1        | 11        | 13.75%  |
| NetBSD 9.0_STABLE | 8         | 10%     |
| NetBSD 9.0        | 6         | 7.5%    |
| NetBSD 10.0_BETA  | 5         | 6.25%   |
| NetBSD 9.99.94    | 3         | 3.75%   |
| NetBSD 9.99.93    | 3         | 3.75%   |
| NetBSD 9.1_STABLE | 3         | 3.75%   |
| NetBSD 9.99.77    | 2         | 2.5%    |
| NetBSD 9.3_STABLE | 2         | 2.5%    |
| NetBSD 9.2_STABLE | 2         | 2.5%    |
| NetBSD 9.99.85    | 1         | 1.25%   |
| NetBSD 9.99.81    | 1         | 1.25%   |
| NetBSD 9.99.74    | 1         | 1.25%   |
| NetBSD 9.99.71    | 1         | 1.25%   |
| NetBSD 9.99.61    | 1         | 1.25%   |
| NetBSD 9.99.23    | 1         | 1.25%   |
| NetBSD 9.99.107   | 1         | 1.25%   |
| NetBSD 8.99.51    | 1         | 1.25%   |
| NetBSD 7.2        | 1         | 1.25%   |
| NetBSD 10.99.7    | 1         | 1.25%   |
| NetBSD 10.99.1    | 1         | 1.25%   |

OS Family
---------

OS without a version

![OS Family](./All/images/pie_chart_bsd/os_family.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| NetBSD | 71        | 100%    |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart_bsd/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| amd64   | 57        | 80.28%  |
| evbarm  | 7         | 9.86%   |
| i386    | 6         | 8.45%   |
| sparc64 | 1         | 1.41%   |

DE
--

Desktop Environment

![DE](./All/images/pie_chart_bsd/os_de.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| Console      | 30        | 41.1%   |
| XFCE         | 15        | 20.55%  |
| helloDesktop | 9         | 12.33%  |
| ctwm         | 5         | 6.85%   |
| Fluxbox      | 4         | 5.48%   |
| MATE         | 2         | 2.74%   |
| DWM          | 2         | 2.74%   |
| Xfwm4        | 1         | 1.37%   |
| sdorfehs     | 1         | 1.37%   |
| Ratpoison    | 1         | 1.37%   |
| PekWM        | 1         | 1.37%   |
| LXQt         | 1         | 1.37%   |
| Awesome      | 1         | 1.37%   |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart_bsd/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 52        | 73.24%  |
| Console | 19        | 26.76%  |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart_bsd/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Console | 64        | 90.14%  |
| XDM     | 3         | 4.23%   |
| GDM     | 2         | 2.82%   |
| SLiM    | 1         | 1.41%   |
| LightDM | 1         | 1.41%   |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart_bsd/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 54        | 72%     |
| en_US   | 13        | 17.33%  |
| ru_RU   | 3         | 4%      |
| fi_FI   | 2         | 2.67%   |
| hu_HU   | 1         | 1.33%   |
| en_GB   | 1         | 1.33%   |
| C       | 1         | 1.33%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart_bsd/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| BIOS | 68        | 95.77%  |
| EFI  | 3         | 4.23%   |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart_bsd/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ufs     | 70        | 98.59%  |
| Unknown | 1         | 1.41%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart_bsd/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| GPT     | 46        | 64.79%  |
| Unknown | 25        | 35.21%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart_bsd/node_vendor.svg)


| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| Unknown                 | 22        | 30.99%  |
| Lenovo                  | 8         | 11.27%  |
| ASUSTek Computer        | 8         | 11.27%  |
| Gigabyte Technology     | 6         | 8.45%   |
| ASRock                  | 4         | 5.63%   |
| Intel                   | 3         | 4.23%   |
| Acer                    | 3         | 4.23%   |
| Raspberry Pi Foundation | 2         | 2.82%   |
| MSI                     | 2         | 2.82%   |
| Hewlett-Packard         | 2         | 2.82%   |
| Dell                    | 2         | 2.82%   |
| Toshiba                 | 1         | 1.41%   |
| Sony                    | 1         | 1.41%   |
| Samsung Electronics     | 1         | 1.41%   |
| MiTAC                   | 1         | 1.41%   |
| KLLISRE                 | 1         | 1.41%   |
| IBM                     | 1         | 1.41%   |
| Fujitsu Siemens         | 1         | 1.41%   |
| eMachines               | 1         | 1.41%   |
| Apple                   | 1         | 1.41%   |

Model
-----

Motherboard model

![Model](./All/images/pie_chart_bsd/node_model.svg)


| Name                                        | Computers | Percent |
|---------------------------------------------|-----------|---------|
| Unknown                                     | 22        | 30.99%  |
| RPi Raspberry Pi 4 Model B                  | 2         | 2.82%   |
| ASUS PRIME A320M-K                          | 2         | 2.82%   |
| Toshiba Satellite A100                      | 1         | 1.41%   |
| Sony SVF1421DSGW                            | 1         | 1.41%   |
| Samsung DP700A3D/DM700A3D/DB701A3D/DP700A7D | 1         | 1.41%   |
| MSI MS-7B86                                 | 1         | 1.41%   |
| MSI MS-7551                                 | 1         | 1.41%   |
| MiTAC 5033                                  | 1         | 1.41%   |
| Lenovo ThinkPad X240 20AMS0J01N             | 1         | 1.41%   |
| Lenovo ThinkPad T510 4313CTO                | 1         | 1.41%   |
| Lenovo ThinkPad T460s 20FAS3L002            | 1         | 1.41%   |
| Lenovo ThinkPad T430s 23564H3               | 1         | 1.41%   |
| Lenovo ThinkPad T430 2347A45                | 1         | 1.41%   |
| Lenovo ThinkPad T420 4236D26                | 1         | 1.41%   |
| Lenovo ThinkPad 13 20GJCTO1WW               | 1         | 1.41%   |
| Lenovo G500 20236                           | 1         | 1.41%   |
| KLLISRE X99-B5 V1.0                         | 1         | 1.41%   |
| Intel NUC5PPYB H76558-102                   | 1         | 1.41%   |
| Intel NUC5i7RYB H73774-102                  | 1         | 1.41%   |
| Intel DN2820FYK H24582-203                  | 1         | 1.41%   |
| IBM ThinkPad R51 2887AVG                    | 1         | 1.41%   |
| HP Vectra                                   | 1         | 1.41%   |
| HP Pavilion 17                              | 1         | 1.41%   |
| Gigabyte Z170X-Gaming 3                     | 1         | 1.41%   |
| Gigabyte X570 AORUS PRO                     | 1         | 1.41%   |
| Gigabyte P75-D3                             | 1         | 1.41%   |
| Gigabyte H61M-S2PV                          | 1         | 1.41%   |
| Gigabyte A320M-H                            | 1         | 1.41%   |
| Gigabyte 970A-D3P                           | 1         | 1.41%   |
| Fujitsu Siemens AMILO L7310                 | 1         | 1.41%   |
| eMachines eME642G                           | 1         | 1.41%   |
| Dell Precision M4500                        | 1         | 1.41%   |
| Dell PowerEdge T320                         | 1         | 1.41%   |
| ASUS X555LJ                                 | 1         | 1.41%   |
| ASUS TUF B450-PLUS GAMING                   | 1         | 1.41%   |
| ASUS E45M1-I DELUXE                         | 1         | 1.41%   |
| ASUS B150M-K                                | 1         | 1.41%   |
| ASUS All Series                             | 1         | 1.41%   |
| ASUS A3L                                    | 1         | 1.41%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart_bsd/node_model_family.svg)


| Name                  | Computers | Percent |
|-----------------------|-----------|---------|
| Unknown               | 22        | 30.99%  |
| Lenovo ThinkPad       | 7         | 9.86%   |
| RPi Raspberry         | 2         | 2.82%   |
| ASUS PRIME            | 2         | 2.82%   |
| Acer Aspire           | 2         | 2.82%   |
| Toshiba Satellite     | 1         | 1.41%   |
| Sony SVF1421DSGW      | 1         | 1.41%   |
| Samsung DP700A3D      | 1         | 1.41%   |
| MSI MS-7B86           | 1         | 1.41%   |
| MSI MS-7551           | 1         | 1.41%   |
| MiTAC 5033            | 1         | 1.41%   |
| Lenovo G500           | 1         | 1.41%   |
| KLLISRE X99-B5        | 1         | 1.41%   |
| Intel NUC5PPYB        | 1         | 1.41%   |
| Intel NUC5i7RYB       | 1         | 1.41%   |
| Intel DN2820FYK       | 1         | 1.41%   |
| IBM ThinkPad          | 1         | 1.41%   |
| HP Vectra             | 1         | 1.41%   |
| HP Pavilion           | 1         | 1.41%   |
| Gigabyte Z170X-Gaming | 1         | 1.41%   |
| Gigabyte X570         | 1         | 1.41%   |
| Gigabyte P75-D3       | 1         | 1.41%   |
| Gigabyte H61M-S2PV    | 1         | 1.41%   |
| Gigabyte A320M-H      | 1         | 1.41%   |
| Gigabyte 970A-D3P     | 1         | 1.41%   |
| Fujitsu Siemens AMILO | 1         | 1.41%   |
| eMachines eME642G     | 1         | 1.41%   |
| Dell Precision        | 1         | 1.41%   |
| Dell PowerEdge        | 1         | 1.41%   |
| ASUS X555LJ           | 1         | 1.41%   |
| ASUS TUF              | 1         | 1.41%   |
| ASUS E45M1-I          | 1         | 1.41%   |
| ASUS B150M-K          | 1         | 1.41%   |
| ASUS All              | 1         | 1.41%   |
| ASUS A3L              | 1         | 1.41%   |
| ASRock X470           | 1         | 1.41%   |
| ASRock N68-VS3        | 1         | 1.41%   |
| ASRock H270           | 1         | 1.41%   |
| ASRock 970            | 1         | 1.41%   |
| Apple MacBook2        | 1         | 1.41%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart_bsd/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 21        | 29.58%  |
| 2020    | 9         | 12.68%  |
| 2013    | 8         | 11.27%  |
| 2018    | 4         | 5.63%   |
| 2014    | 4         | 5.63%   |
| 2017    | 3         | 4.23%   |
| 2011    | 3         | 4.23%   |
| 2010    | 3         | 4.23%   |
| 2021    | 2         | 2.82%   |
| 2019    | 2         | 2.82%   |
| 2016    | 2         | 2.82%   |
| 2015    | 2         | 2.82%   |
| 2007    | 2         | 2.82%   |
| 2005    | 2         | 2.82%   |
| 2022    | 1         | 1.41%   |
| 2012    | 1         | 1.41%   |
| 2006    | 1         | 1.41%   |
| 2001    | 1         | 1.41%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart_bsd/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Desktop        | 44        | 61.97%  |
| Notebook       | 21        | 29.58%  |
| System on chip | 2         | 2.82%   |
| Mini pc        | 2         | 2.82%   |
| All in one     | 1         | 1.41%   |
| Server         | 1         | 1.41%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart_bsd/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 70        | 98.59%  |
| Yes  | 1         | 1.41%   |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart_bsd/node_ram_total.svg)


| Size in GB  | Computers | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 22        | 30.99%  |
| 16.01-24.0  | 11        | 15.49%  |
| 3.01-4.0    | 10        | 14.08%  |
| 8.01-16.0   | 9         | 12.68%  |
| 0.51-1.0    | 5         | 7.04%   |
| 32.01-64.0  | 4         | 5.63%   |
| 1.01-2.0    | 3         | 4.23%   |
| 0.01-0.5    | 3         | 4.23%   |
| 24.01-32.0  | 1         | 1.41%   |
| 64.01-256.0 | 1         | 1.41%   |
| 0           | 1         | 1.41%   |
| Unknown     | 1         | 1.41%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart_bsd/node_ram_used.svg)


| Used GB | Computers | Percent |
|---------|-----------|---------|
| Unknown | 71        | 100%    |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart_bsd/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 0      | 32        | 42.67%  |
| 1      | 29        | 38.67%  |
| 2      | 10        | 13.33%  |
| 3      | 3         | 4%      |
| 4      | 1         | 1.33%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart_bsd/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 68        | 95.77%  |
| Yes       | 3         | 4.23%   |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart_bsd/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 60        | 84.51%  |
| No        | 11        | 15.49%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart_bsd/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 41        | 57.75%  |
| No        | 30        | 42.25%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart_bsd/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 44        | 61.97%  |
| Yes       | 27        | 38.03%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart_bsd/node_location.svg)


| Country      | Computers | Percent |
|--------------|-----------|---------|
| Russia       | 12        | 16.9%   |
| USA          | 9         | 12.68%  |
| Italy        | 9         | 12.68%  |
| Germany      | 7         | 9.86%   |
| UK           | 5         | 7.04%   |
| Hungary      | 4         | 5.63%   |
| France       | 4         | 5.63%   |
| Saudi Arabia | 3         | 4.23%   |
| Finland      | 3         | 4.23%   |
| Spain        | 2         | 2.82%   |
| Romania      | 2         | 2.82%   |
| India        | 2         | 2.82%   |
| Vietnam      | 1         | 1.41%   |
| Poland       | 1         | 1.41%   |
| Norway       | 1         | 1.41%   |
| Netherlands  | 1         | 1.41%   |
| Latvia       | 1         | 1.41%   |
| Czechia      | 1         | 1.41%   |
| Canada       | 1         | 1.41%   |
| Brazil       | 1         | 1.41%   |
| Australia    | 1         | 1.41%   |

City
----

Geographic location (city)

![City](./All/images/pie_chart_bsd/node_city.svg)


| City                  | Computers | Percent |
|-----------------------|-----------|---------|
| Rome                  | 8         | 11.11%  |
| Ozersk                | 7         | 9.72%   |
| Moscow                | 4         | 5.56%   |
| Riyadh                | 3         | 4.17%   |
| Lille                 | 3         | 4.17%   |
| Gardony               | 3         | 4.17%   |
| Tampere               | 2         | 2.78%   |
| Hayward               | 2         | 2.78%   |
| Bucharest             | 2         | 2.78%   |
| Berlin                | 2         | 2.78%   |
| Washington            | 1         | 1.39%   |
| Urupes                | 1         | 1.39%   |
| Unterhaching          | 1         | 1.39%   |
| Ulan-Ude              | 1         | 1.39%   |
| Turin                 | 1         | 1.39%   |
| Turenki               | 1         | 1.39%   |
| Sydney                | 1         | 1.39%   |
| Surrey                | 1         | 1.39%   |
| Sun Prairie           | 1         | 1.39%   |
| Stourbridge           | 1         | 1.39%   |
| Sopron                | 1         | 1.39%   |
| Sandnes               | 1         | 1.39%   |
| Royal Tunbridge Wells | 1         | 1.39%   |
| Riga                  | 1         | 1.39%   |
| Reno                  | 1         | 1.39%   |
| Prague                | 1         | 1.39%   |
| Poznan                | 1         | 1.39%   |
| Portland              | 1         | 1.39%   |
| Murcia                | 1         | 1.39%   |
| London                | 1         | 1.39%   |
| Lohr a. Main          | 1         | 1.39%   |
| Ladbergen             | 1         | 1.39%   |
| Kalispell             | 1         | 1.39%   |
| Ho Chi Minh City      | 1         | 1.39%   |
| Hamilton              | 1         | 1.39%   |
| Genzano di Roma       | 1         | 1.39%   |
| Fort Wayne            | 1         | 1.39%   |
| Deggendorf            | 1         | 1.39%   |
| Chennai               | 1         | 1.39%   |
| Carry-le-Rouet        | 1         | 1.39%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart_bsd/drive_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 9         | 12     | 16.67%  |
| Seagate             | 6         | 6      | 11.11%  |
| Kingston            | 6         | 7      | 11.11%  |
| Samsung Electronics | 5         | 5      | 9.26%   |
| Toshiba             | 4         | 6      | 7.41%   |
| SanDisk             | 4         | 5      | 7.41%   |
| Maxtor              | 3         | 3      | 5.56%   |
| Intel               | 3         | 3      | 5.56%   |
| Crucial             | 3         | 4      | 5.56%   |
| Hitachi             | 2         | 3      | 3.7%    |
| SK hynix            | 1         | 2      | 1.85%   |
| Lexar               | 1         | 1      | 1.85%   |
| JetFlash            | 1         | 1      | 1.85%   |
| Intenso             | 1         | 1      | 1.85%   |
| HGST                | 1         | 1      | 1.85%   |
| Hewlett-Packard     | 1         | 1      | 1.85%   |
| Generic             | 1         | 1      | 1.85%   |
| Dell                | 1         | 2      | 1.85%   |
| China               | 1         | 1      | 1.85%   |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart_bsd/drive_model.svg)


| Model                               | Computers | Percent |
|-------------------------------------|-----------|---------|
| Toshiba DT01ACA100 1TB              | 3         | 5.45%   |
| SanDisk Extreme SSD 500GB           | 2         | 3.64%   |
| Samsung SSD 860 EVO 500GB           | 2         | 3.64%   |
| Samsung HD103UJ 1TB                 | 2         | 3.64%   |
| Maxtor STM3250310AS 250GB           | 2         | 3.64%   |
| Kingston DataTraveler 3.0 32GB      | 2         | 3.64%   |
| WDC WDS240G2G0A-00JH30 240GB        | 1         | 1.82%   |
| WDC WDS120G2G0A-00JH30 120GB        | 1         | 1.82%   |
| WDC WD5003AZEX-00K3CA0 500GB        | 1         | 1.82%   |
| WDC WD5000AAKX-753CA1 500GB         | 1         | 1.82%   |
| WDC WD5000AACS-00ZUB0 500GB         | 1         | 1.82%   |
| WDC WD2502ABYS-01B7A0 256GB         | 1         | 1.82%   |
| WDC WD20EFRX-68EUZN0 2TB            | 1         | 1.82%   |
| WDC WD200EB-00BHF0 20GB             | 1         | 1.82%   |
| WDC WD1600BEVT-00A23T0 160GB        | 1         | 1.82%   |
| WDC WD10EZEX-60WN4A0 1TB            | 1         | 1.82%   |
| Toshiba DT01ACA200 2TB              | 1         | 1.82%   |
| SK hynix HFS128G39TND-N210A 128GB   | 1         | 1.82%   |
| Seagate ST750LM022 HN-M750MBB 752GB | 1         | 1.82%   |
| Seagate ST500VT000-1DK142 500GB     | 1         | 1.82%   |
| Seagate ST500LT012-9WS142 500GB     | 1         | 1.82%   |
| Seagate ST380011A 80GB              | 1         | 1.82%   |
| Seagate ST2000DL003-9VT166 2TB      | 1         | 1.82%   |
| Seagate ST1000DM010-2EP102 1TB      | 1         | 1.82%   |
| SanDisk SDSSDH3512G 512GB           | 1         | 1.82%   |
| SanDisk Cruzer Glide 16GB           | 1         | 1.82%   |
| Samsung HM080HC 80GB                | 1         | 1.82%   |
| Maxtor 6E040L0 40GB                 | 1         | 1.82%   |
| Lexar USB Flash Drive 64GB          | 1         | 1.82%   |
| Kingston SM2280S3G2120G 120GB       | 1         | 1.82%   |
| Kingston SA400S37480G 480GB         | 1         | 1.82%   |
| Kingston SA400S37240G 240GB         | 1         | 1.82%   |
| Kingston SA400S37120G 120GB         | 1         | 1.82%   |
| JetFlash Transcend 16GB             | 1         | 1.82%   |
| Intenso Rainbow Line 8GB            | 1         | 1.82%   |
| Intel SSDSC2KW120H6 120GB           | 1         | 1.82%   |
| Intel SSDSC2CW120A3 120GB           | 1         | 1.82%   |
| Intel SSDSC2BF180A4L 180GB          | 1         | 1.82%   |
| Hitachi HTS721060G9AT00 64GB        | 1         | 1.82%   |
| Hitachi HTS548040M9AT00 37GB        | 1         | 1.82%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart_bsd/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 8         | 10     | 24.24%  |
| Seagate             | 6         | 6      | 18.18%  |
| Toshiba             | 4         | 6      | 12.12%  |
| Samsung Electronics | 3         | 3      | 9.09%   |
| Maxtor              | 3         | 3      | 9.09%   |
| Hitachi             | 2         | 3      | 6.06%   |
| Lexar               | 1         | 1      | 3.03%   |
| JetFlash            | 1         | 1      | 3.03%   |
| Intenso             | 1         | 1      | 3.03%   |
| HGST                | 1         | 1      | 3.03%   |
| Hewlett-Packard     | 1         | 1      | 3.03%   |
| Generic             | 1         | 1      | 3.03%   |
| Dell                | 1         | 2      | 3.03%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart_bsd/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Kingston            | 6         | 7      | 27.27%  |
| SanDisk             | 4         | 5      | 18.18%  |
| Intel               | 3         | 3      | 13.64%  |
| Crucial             | 3         | 4      | 13.64%  |
| WDC                 | 2         | 2      | 9.09%   |
| Samsung Electronics | 2         | 2      | 9.09%   |
| SK hynix            | 1         | 2      | 4.55%   |
| China               | 1         | 1      | 4.55%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart_bsd/drive_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 27        | 39     | 56.25%  |
| SSD  | 21        | 26     | 43.75%  |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart_bsd/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 41        | 65     | 100%    |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart_bsd/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 38        | 46     | 74.51%  |
| 0.51-1.0   | 10        | 13     | 19.61%  |
| 1.01-2.0   | 2         | 4      | 3.92%   |
| 4.01-10.0  | 1         | 2      | 1.96%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart_bsd/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 20        | 28.17%  |
| 251-500        | 14        | 19.72%  |
| 501-1000       | 11        | 15.49%  |
| 51-100         | 8         | 11.27%  |
| 1-20           | 7         | 9.86%   |
| 21-50          | 5         | 7.04%   |
| 2001-3000      | 3         | 4.23%   |
| 1001-2000      | 2         | 2.82%   |
| More than 3000 | 1         | 1.41%   |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart_bsd/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 52        | 67.53%  |
| 21-50          | 10        | 12.99%  |
| 51-100         | 6         | 7.79%   |
| 101-250        | 3         | 3.9%    |
| 1001-2000      | 2         | 2.6%    |
| 501-1000       | 2         | 2.6%    |
| More than 3000 | 1         | 1.3%    |
| 251-500        | 1         | 1.3%    |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./All/images/pie_chart_bsd/drive_malfunc.svg)


| Model                               | Computers | Drives | Percent |
|-------------------------------------|-----------|--------|---------|
| WDC WDS240G2G0A-00JH30 240GB        | 1         | 1      | 7.69%   |
| WDC WD10EZEX-60WN4A0 1TB            | 1         | 1      | 7.69%   |
| SK hynix HFS128G39TND-N210A 128GB   | 1         | 1      | 7.69%   |
| Seagate ST750LM022 HN-M750MBB 752GB | 1         | 1      | 7.69%   |
| Seagate ST500VT000-1DK142 500GB     | 1         | 1      | 7.69%   |
| Seagate ST500LT012-9WS142 500GB     | 1         | 1      | 7.69%   |
| Seagate ST2000DL003-9VT166 2TB      | 1         | 1      | 7.69%   |
| Maxtor 6E040L0 40GB                 | 1         | 1      | 7.69%   |
| Intel SSDSC2KW120H6 120GB           | 1         | 1      | 7.69%   |
| Intel SSDSC2CW120A3 120GB           | 1         | 1      | 7.69%   |
| Intel SSDSC2BF180A4L 180GB          | 1         | 1      | 7.69%   |
| Hitachi HTS721060G9AT00 64GB        | 1         | 1      | 7.69%   |
| Hitachi HTS548040M9AT00 37GB        | 1         | 2      | 7.69%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./All/images/pie_chart_bsd/drive_malfunc_vendor.svg)


| Vendor   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Seagate  | 4         | 4      | 30.77%  |
| Intel    | 3         | 3      | 23.08%  |
| WDC      | 2         | 2      | 15.38%  |
| Hitachi  | 2         | 3      | 15.38%  |
| SK hynix | 1         | 1      | 7.69%   |
| Maxtor   | 1         | 1      | 7.69%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./All/images/pie_chart_bsd/drive_malfunc_hdd_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 4         | 4      | 50%     |
| Hitachi | 2         | 3      | 25%     |
| WDC     | 1         | 1      | 12.5%   |
| Maxtor  | 1         | 1      | 12.5%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./All/images/pie_chart_bsd/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 8         | 9      | 61.54%  |
| SSD  | 5         | 5      | 38.46%  |

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
| Works    | 24        | 41     | 52.17%  |
| Malfunc  | 13        | 14     | 28.26%  |
| Detected | 9         | 10     | 19.57%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart_bsd/storage_vendor.svg)


| Vendor                    | Computers | Percent |
|---------------------------|-----------|---------|
| Intel                     | 45        | 56.96%  |
| AMD                       | 16        | 20.25%  |
| Samsung Electronics       | 5         | 6.33%   |
| Silicon Motion            | 3         | 3.8%    |
| SanDisk                   | 2         | 2.53%   |
| Phison Electronics        | 2         | 2.53%   |
| VIA Technologies          | 1         | 1.27%   |
| ULi Electronics           | 1         | 1.27%   |
| Nvidia                    | 1         | 1.27%   |
| Micron/Crucial Technology | 1         | 1.27%   |
| Broadcom / LSI            | 1         | 1.27%   |
| ASMedia Technology        | 1         | 1.27%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart_bsd/storage_model.svg)


| Model                                                                            | Computers | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                              | 8         | 8.99%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 6         | 6.74%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                | 6         | 6.74%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]    | 4         | 4.49%   |
| AMD 400 Series Chipset SATA Controller                                           | 4         | 4.49%   |
| Silicon Motion SM2263EN/SM2263XT (DRAM-less) NVMe SSD Controllers                | 3         | 3.37%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]     | 3         | 3.37%   |
| AMD FCH SATA Controller D                                                        | 3         | 3.37%   |
| SanDisk WD Blue SN550 NVMe SSD                                                   | 2         | 2.25%   |
| Samsung NVMe SSD Controller 980                                                  | 2         | 2.25%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 2         | 2.25%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 2         | 2.25%   |
| Intel product 54d3                                                               | 2         | 2.25%   |
| Intel Jasper Lake SATA AHCI Controller                                           | 2         | 2.25%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                       | 2         | 2.25%   |
| Intel 82801DBM (ICH4-M) IDE Controller                                           | 2         | 2.25%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 2         | 2.25%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller    | 2         | 2.25%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                   | 2         | 2.25%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                             | 2         | 2.25%   |
| VIA VT82C586A/B/VT82C686/A/B/VT823x/A/C PIPC Bus Master IDE                      | 1         | 1.12%   |
| ULi M5229 IDE                                                                    | 1         | 1.12%   |
| Samsung S4LN058A01[SSUBX] AHCI SSD Controller (Apple slot)                       | 1         | 1.12%   |
| Samsung S4LN053X01 AHCI SSD Controller(Apple slot)                               | 1         | 1.12%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 1         | 1.12%   |
| Phison E16 PCIe4 NVMe Controller                                                 | 1         | 1.12%   |
| Phison E12 NVMe Controller                                                       | 1         | 1.12%   |
| Nvidia MCP61 SATA Controller                                                     | 1         | 1.12%   |
| Nvidia MCP61 IDE                                                                 | 1         | 1.12%   |
| Micron/Crucial P2 [Nick P2] / P3 / P3 Plus NVMe PCIe SSD (DRAM-less)             | 1         | 1.12%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                           | 1         | 1.12%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller         | 1         | 1.12%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                | 1         | 1.12%   |
| Intel C600/X79 series chipset 6-Port SATA AHCI Controller                        | 1         | 1.12%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 1         | 1.12%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                           | 1         | 1.12%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [IDE mode]                    | 1         | 1.12%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [AHCI mode]                   | 1         | 1.12%   |
| Intel 82801G (ICH7 Family) IDE Controller                                        | 1         | 1.12%   |
| Intel 82801AA IDE Controller                                                     | 1         | 1.12%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart_bsd/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 58        | 69.88%  |
| IDE  | 13        | 15.66%  |
| NVMe | 11        | 13.25%  |
| RAID | 1         | 1.2%    |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart_bsd/cpu_vendor.svg)


| Vendor          | Computers | Percent |
|-----------------|-----------|---------|
| Intel           | 45        | 63.38%  |
| AMD             | 17        | 23.94%  |
| Unknown         | 3         | 4.23%   |
| Broadcom        | 2         | 2.82%   |
| Arm             | 2         | 2.82%   |
| SUNW,UltraAX-i2 | 1         | 1.41%   |
| 123456789ABC    | 1         | 1.41%   |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart_bsd/cpu_model.svg)


| Model                                           | Computers | Percent |
|-------------------------------------------------|-----------|---------|
| Intel 686-class                                 | 17        | 23.29%  |
|                                                 | 3         | 4.11%   |
| Broadcom BCM2711 (ARM Cortex-A72)               | 2         | 2.74%   |
| Arm Cortex-A53 r0p4 (v8-A)                      | 2         | 2.74%   |
| AMD 686-class                                   | 2         | 2.74%   |
| SUNW,UltraAX-i2 (SUNW,UltraSPARC-IIe @ 500 MHz) | 1         | 1.37%   |
| Intel Xeon CPU E5-2630L v3 @ 1.80GHz            | 1         | 1.37%   |
| Intel Xeon CPU E5-2450L 0 @ 1.80GHz             | 1         | 1.37%   |
| Intel Pentium M processor 1.60GHz               | 1         | 1.37%   |
| Intel Pentium M processor                       | 1         | 1.37%   |
| Intel Pentium III                               | 1         | 1.37%   |
| Intel Pentium CPU 2020M @ 2.40GHz               | 1         | 1.37%   |
| Intel N100                                      | 1         | 1.37%   |
| Intel Core i7-7700 CPU @ 3.60GHz                | 1         | 1.37%   |
| Intel Core i7-6700K CPU @ 4.00GHz               | 1         | 1.37%   |
| Intel Core i7-5557U CPU @ 3.10GHz               | 1         | 1.37%   |
| Intel Core i7-5500U CPU @ 2.40GHz               | 1         | 1.37%   |
| Intel Core i7-3770 CPU @ 3.40GHz                | 1         | 1.37%   |
| Intel Core i7-3520M CPU @ 2.90GHz               | 1         | 1.37%   |
| Intel Core i7-2640M CPU @ 2.80GHz               | 1         | 1.37%   |
| Intel Core i5-9400T CPU @ 1.80GHz               | 1         | 1.37%   |
| Intel Core i5-7400 CPU @ 3.00GHz                | 1         | 1.37%   |
| Intel Core i5-6300U CPU @ 2.40GHz               | 1         | 1.37%   |
| Intel Core i5-6200U CPU @ 2.30GHz               | 1         | 1.37%   |
| Intel Core i5-4310M CPU @ 2.70GHz               | 1         | 1.37%   |
| Intel Core i5-4300U CPU @ 1.90GHz               | 1         | 1.37%   |
| Intel Core i5-3320M CPU @ 2.60GHz               | 1         | 1.37%   |
| Intel Core i5-2320 CPU @ 3.00GHz                | 1         | 1.37%   |
| Intel Core i5 CPU M 560 @ 2.67GH                | 1         | 1.37%   |
| Intel Core i5 CPU M 540 @ 2.53GHz               | 1         | 1.37%   |
| Intel Core i3-4150 CPU @ 3.50GHz                | 1         | 1.37%   |
| Intel Core i3-3220T CPU @ 2.80GHz               | 1         | 1.37%   |
| Intel Core i3-3217U CPU @ 1.80GHz               | 1         | 1.37%   |
| Intel Core 2 CPU T7200 @ 2.00GHz                | 1         | 1.37%   |
| Intel Core 2 CPU T7                             | 1         | 1.37%   |
| Intel Celeron CPU N2830 @ 2.16GHz               | 1         | 1.37%   |
| AMD Tillamook                                   | 1         | 1.37%   |
| AMD Sempron 145 Processor                       | 1         | 1.37%   |
| AMD Ryzen 9 3900X 12-Core Processor             | 1         | 1.37%   |
| AMD Ryzen 7 2700 Eight-Core Processor           | 1         | 1.37%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart_bsd/cpu_family.svg)


| Model             | Computers | Percent |
|-------------------|-----------|---------|
| Intel 686-class   | 17        | 23.29%  |
| Other             | 11        | 15.07%  |
| Intel Core i5     | 10        | 13.7%   |
| Intel Core i7     | 7         | 9.59%   |
| Intel Core i3     | 3         | 4.11%   |
| AMD Ryzen 3       | 3         | 4.11%   |
| Intel Xeon        | 2         | 2.74%   |
| Intel Pentium M   | 2         | 2.74%   |
| Intel Core 2      | 2         | 2.74%   |
| AMD Ryzen 5       | 2         | 2.74%   |
| AMD 686-class     | 2         | 2.74%   |
| Intel Pentium III | 1         | 1.37%   |
| Intel Pentium     | 1         | 1.37%   |
| Intel Celeron     | 1         | 1.37%   |
| AMD Sempron       | 1         | 1.37%   |
| AMD Ryzen 9       | 1         | 1.37%   |
| AMD Ryzen 7       | 1         | 1.37%   |
| AMD Phenom II X6  | 1         | 1.37%   |
| AMD Phenom II X4  | 1         | 1.37%   |
| AMD FX            | 1         | 1.37%   |
| AMD E             | 1         | 1.37%   |
| AMD Athlon II     | 1         | 1.37%   |
| AMD A10           | 1         | 1.37%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart_bsd/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| Unknown | 37        | 50.68%  |
| 2       | 16        | 21.92%  |
| 4       | 12        | 16.44%  |
| 8       | 4         | 5.48%   |
| 6       | 3         | 4.11%   |
| 12      | 1         | 1.37%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart_bsd/cpu_sockets.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 47        | 64.38%  |
| Unknown | 26        | 35.62%  |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart_bsd/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| Unknown | 37        | 50.68%  |
| 2       | 21        | 28.77%  |
| 1       | 15        | 20.55%  |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart_bsd/cpu_microarch.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| Unknown     | 32        | 43.84%  |
| IvyBridge   | 6         | 8.22%   |
| Zen+        | 3         | 4.11%   |
| Skylake     | 3         | 4.11%   |
| SandyBridge | 3         | 4.11%   |
| P6          | 3         | 4.11%   |
| KabyLake    | 3         | 4.11%   |
| K10         | 3         | 4.11%   |
| Haswell     | 3         | 4.11%   |
| Zen 2       | 2         | 2.74%   |
| Zen         | 2         | 2.74%   |
| Piledriver  | 2         | 2.74%   |
| Core        | 2         | 2.74%   |
| Broadwell   | 2         | 2.74%   |
| Westmere    | 1         | 1.37%   |
| Silvermont  | 1         | 1.37%   |
| Geode       | 1         | 1.37%   |
| Bobcat      | 1         | 1.37%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart_bsd/gpu_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Intel                      | 38        | 54.29%  |
| AMD                        | 17        | 24.29%  |
| Nvidia                     | 12        | 17.14%  |
| VIA Technologies           | 1         | 1.43%   |
| Trident Microsystems       | 1         | 1.43%   |
| Matrox Electronics Systems | 1         | 1.43%   |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart_bsd/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 3rd Gen Core processor Graphics Controller                                         | 5         | 6.85%   |
| Intel HD Graphics 530                                                                    | 3         | 4.11%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 3         | 4.11%   |
| Nvidia GF114 [GeForce GTX 560]                                                           | 2         | 2.74%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 2         | 2.74%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 2         | 2.74%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 2         | 2.74%   |
| Intel Mobile 945GM/GMS, 943/940GML Express Integrated Graphics Controller                | 2         | 2.74%   |
| Intel JasperLake [UHD Graphics]                                                          | 2         | 2.74%   |
| Intel Iris Graphics 6100                                                                 | 2         | 2.74%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 2         | 2.74%   |
| Intel Alder Lake-N [UHD Graphics]                                                        | 2         | 2.74%   |
| Intel 82852/855GM Integrated Graphics Device                                             | 2         | 2.74%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 2         | 2.74%   |
| VIA Technologies CN400/PM800/PM880/PN800/PN880 [S3 UniChrome Pro]                        | 1         | 1.37%   |
| Trident Microsystems TGUI 9660/938x/968x                                                 | 1         | 1.37%   |
| Nvidia NV18 [GeForce4 MX 440 AGP 8x]                                                     | 1         | 1.37%   |
| Nvidia GT218M [NVS 3100M]                                                                | 1         | 1.37%   |
| Nvidia GT216GLM [Quadro FX 880M]                                                         | 1         | 1.37%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 1         | 1.37%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 1         | 1.37%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                                      | 1         | 1.37%   |
| Nvidia GM204 [GeForce GTX 970]                                                           | 1         | 1.37%   |
| Nvidia GK208BM [GeForce 920M]                                                            | 1         | 1.37%   |
| Nvidia G86 [GeForce 8500 GT]                                                             | 1         | 1.37%   |
| Nvidia C61 [GeForce 7025 / nForce 630a]                                                  | 1         | 1.37%   |
| Matrox Electronics Systems G200eR2                                                       | 1         | 1.37%   |
| Intel IvyBridge GT2 [HD Graphics 4000]                                                   | 1         | 1.37%   |
| Intel HD Graphics 630                                                                    | 1         | 1.37%   |
| Intel HD Graphics 6000                                                                   | 1         | 1.37%   |
| Intel HD Graphics 5500                                                                   | 1         | 1.37%   |
| Intel GeminiLake [UHD Graphics 605]                                                      | 1         | 1.37%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                                 | 1         | 1.37%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 1         | 1.37%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 1         | 1.37%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 1         | 1.37%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 1         | 1.37%   |
| Intel Apollo Lake [HD Graphics 505]                                                      | 1         | 1.37%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 1         | 1.37%   |
| AMD Wrestler [Radeon HD 6320]                                                            | 1         | 1.37%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart_bsd/gpu_combo.svg)


| Name                     | Computers | Percent |
|--------------------------|-----------|---------|
| 1 x Intel                | 31        | 43.66%  |
| 1 x AMD                  | 14        | 19.72%  |
| 1 x Nvidia               | 9         | 12.68%  |
| Other                    | 8         | 11.27%  |
| 2 x Intel                | 2         | 2.82%   |
| Intel + Nvidia           | 2         | 2.82%   |
| 2 x AMD                  | 1         | 1.41%   |
| 1 x VIA                  | 1         | 1.41%   |
| 1 x Trident Microsystems | 1         | 1.41%   |
| 1 x Matrox               | 1         | 1.41%   |
| Intel + AMD              | 1         | 1.41%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart_bsd/gpu_driver.svg)


| Driver  | Computers | Percent |
|---------|-----------|---------|
| Free    | 51        | 69.86%  |
| Unknown | 22        | 30.14%  |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart_bsd/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 34        | 47.22%  |
| 1.01-2.0   | 13        | 18.06%  |
| 0.01-0.5   | 10        | 13.89%  |
| 3.01-4.0   | 8         | 11.11%  |
| 0.51-1.0   | 5         | 6.94%   |
| 7.01-8.0   | 1         | 1.39%   |
| 5.01-6.0   | 1         | 1.39%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart_bsd/mon_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 7         | 24.14%  |
| LG Display          | 6         | 20.69%  |
| Goldstar            | 4         | 13.79%  |
| Chimei Innolux      | 2         | 6.9%    |
| Apple               | 2         | 6.9%    |
| ViewSonic           | 1         | 3.45%   |
| Unknown (CDD)       | 1         | 3.45%   |
| LG Philips          | 1         | 3.45%   |
| Lenovo              | 1         | 3.45%   |
| Impression          | 1         | 3.45%   |
| Iiyama              | 1         | 3.45%   |
| Dell                | 1         | 3.45%   |
| Acer                | 1         | 3.45%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart_bsd/mon_model.svg)


| Model                                                                 | Computers | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| Samsung Electronics LCD Monitor SAM0C39 1920x1080 890x500mm 40.2-inch | 2         | 6.9%    |
| ViewSonic VG2439 Series VSCD22B 1920x1080 520x290mm 23.4-inch         | 1         | 3.45%   |
| Unknown (CDD) VGA CDD0030 1920x1080 1150x650mm 52.0-inch              | 1         | 3.45%   |
| Samsung Electronics SyncMaster SAM01AE 1600x1200 410x310mm 20.2-inch  | 1         | 3.45%   |
| Samsung Electronics SMS27A350H SAM07CE 1920x1080 600x340mm 27.2-inch  | 1         | 3.45%   |
| Samsung Electronics S23C570 SAM0A56 1920x1080 510x290mm 23.1-inch     | 1         | 3.45%   |
| Samsung Electronics LCD Monitor SEC324C 1600x900 310x170mm 13.9-inch  | 1         | 3.45%   |
| Samsung Electronics LCD Monitor SDC4752 1366x768 340x190mm 15.3-inch  | 1         | 3.45%   |
| LG Philips LCD Monitor LPLDD00 1280x800 330x210mm 15.4-inch           | 1         | 3.45%   |
| LG Display LCD Monitor LGD40A0 1366x768 310x170mm 13.9-inch           | 1         | 3.45%   |
| LG Display LCD Monitor LGD0521 1920x1080 310x170mm 13.9-inch          | 1         | 3.45%   |
| LG Display LCD Monitor LGD045E 1366x768 310x170mm 13.9-inch           | 1         | 3.45%   |
| LG Display LCD Monitor LGD03CD 1366x768 280x160mm 12.7-inch           | 1         | 3.45%   |
| LG Display LCD Monitor LGD0335 1366x768 310x170mm 13.9-inch           | 1         | 3.45%   |
| LG Display LCD Monitor LGD029E 1600x900 340x190mm 15.3-inch           | 1         | 3.45%   |
| Lenovo LCD Monitor LEN40B1 1600x900 340x190mm 15.3-inch               | 1         | 3.45%   |
| Impression R19W11 IMP1911 1440x900 410x260mm 19.1-inch                | 1         | 3.45%   |
| Iiyama PL2792Q IVM6630 2560x1440 600x340mm 27.2-inch                  | 1         | 3.45%   |
| Goldstar W1952 GSM4B78 1440x900 410x260mm 19.1-inch                   | 1         | 3.45%   |
| Goldstar LG ULTRAWIDE GSM59F1 2560x1080 670x280mm 28.6-inch           | 1         | 3.45%   |
| Goldstar LG IPS FULLHD GSM5AB6 1920x1080 480x270mm 21.7-inch          | 1         | 3.45%   |
| Goldstar L194WT GSM4B05 1440x900 410x260mm 19.1-inch                  | 1         | 3.45%   |
| Dell P2419H DELD0DA 1920x1080 530x300mm 24.0-inch                     | 1         | 3.45%   |
| Chimei Innolux LCD Monitor CMN15AB 1366x768 340x190mm 15.3-inch       | 1         | 3.45%   |
| Chimei Innolux LCD Monitor CMN1472 1366x768 310x170mm 13.9-inch       | 1         | 3.45%   |
| Apple LCD Monitor APP9C5F 1280x800 290x180mm 13.4-inch                | 1         | 3.45%   |
| Apple Color LCD APPA029 2560x1600 290x180mm 13.4-inch                 | 1         | 3.45%   |
| Acer SB220Q ACR06AB 1920x1080 480x270mm 21.7-inch                     | 1         | 3.45%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart_bsd/mon_resolution.svg)


| Resolution       | Computers | Percent |
|------------------|-----------|---------|
| 1920x1080 (FHD)  | 10        | 34.48%  |
| 1366x768 (WXGA)  | 7         | 24.14%  |
| 1600x900 (HD+)   | 3         | 10.34%  |
| 1440x900 (WXGA+) | 3         | 10.34%  |
| 1280x800 (WXGA)  | 2         | 6.9%    |
| 2560x1600        | 1         | 3.45%   |
| 2560x1440 (QHD)  | 1         | 3.45%   |
| 2560x1080        | 1         | 3.45%   |
| 1600x1200        | 1         | 3.45%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart_bsd/mon_diagonal.svg)


| Inches | Computers | Percent |
|--------|-----------|---------|
| 13     | 8         | 27.59%  |
| 15     | 5         | 17.24%  |
| 19     | 3         | 10.34%  |
| 40     | 2         | 6.9%    |
| 27     | 2         | 6.9%    |
| 23     | 2         | 6.9%    |
| 21     | 2         | 6.9%    |
| 52     | 1         | 3.45%   |
| 34     | 1         | 3.45%   |
| 24     | 1         | 3.45%   |
| 20     | 1         | 3.45%   |
| 12     | 1         | 3.45%   |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart_bsd/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 11        | 37.93%  |
| 401-500     | 6         | 20.69%  |
| 501-600     | 5         | 17.24%  |
| 201-300     | 3         | 10.34%  |
| 801-900     | 2         | 6.9%    |
| 701-800     | 1         | 3.45%   |
| 1001-1500   | 1         | 3.45%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart_bsd/mon_ratio.svg)


| Ratio | Computers | Percent |
|-------|-----------|---------|
| 16/9  | 21        | 72.41%  |
| 16/10 | 6         | 20.69%  |
| 4/3   | 1         | 3.45%   |
| 21/9  | 1         | 3.45%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart_bsd/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 81-90          | 8         | 27.59%  |
| 201-250        | 5         | 17.24%  |
| 151-200        | 4         | 13.79%  |
| 101-110        | 3         | 10.34%  |
| 301-350        | 2         | 6.9%    |
| 501-1000       | 2         | 6.9%    |
| 91-100         | 2         | 6.9%    |
| More than 1000 | 1         | 3.45%   |
| 61-70          | 1         | 3.45%   |
| 351-500        | 1         | 3.45%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart_bsd/mon_density.svg)


| Density | Computers | Percent |
|---------|-----------|---------|
| 51-100  | 13        | 44.83%  |
| 101-120 | 11        | 37.93%  |
| 121-160 | 3         | 10.34%  |
| 1-50    | 1         | 3.45%   |
| 161-240 | 1         | 3.45%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart_bsd/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 40        | 55.56%  |
| 0     | 31        | 43.06%  |
| 2     | 1         | 1.39%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart_bsd/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 33        | 34.02%  |
| Intel                             | 30        | 30.93%  |
| Qualcomm Atheros                  | 12        | 12.37%  |
| Broadcom                          | 8         | 8.25%   |
| Huawei Technologies               | 3         | 3.09%   |
| VIA Technologies                  | 1         | 1.03%   |
| TP-Link                           | 1         | 1.03%   |
| Oculus VR                         | 1         | 1.03%   |
| Netchip Technology                | 1         | 1.03%   |
| Mercucys                          | 1         | 1.03%   |
| Marvell Technology Group          | 1         | 1.03%   |
| Ericsson Business Mobile Networks | 1         | 1.03%   |
| Davicom Semiconductor             | 1         | 1.03%   |
| D-Link                            | 1         | 1.03%   |
| Apple                             | 1         | 1.03%   |
| 3Com                              | 1         | 1.03%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart_bsd/net_model.svg)


| Model                                                                                 | Computers | Percent |
|---------------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller                     | 30        | 24.39%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)                                 | 6         | 4.88%   |
| Intel Wireless-AC 9260                                                                | 3         | 2.44%   |
| Intel I211 Gigabit Network Connection                                                 | 3         | 2.44%   |
| Huawei USB Device                                                                     | 3         | 2.44%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                                 | 2         | 1.63%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                            | 2         | 1.63%   |
| Qualcomm Atheros AR2413/AR2414 Wireless Network Adapter [AR5005G(S) 802.11bg]         | 2         | 1.63%   |
| Intel Wireless 8260                                                                   | 2         | 1.63%   |
| Intel Wireless 7265                                                                   | 2         | 1.63%   |
| Intel Wi-Fi 6 AX201 160MHz                                                            | 2         | 1.63%   |
| Intel Ethernet Connection (2) I219-LM                                                 | 2         | 1.63%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                                      | 2         | 1.63%   |
| Intel Centrino Ultimate-N 6300                                                        | 2         | 1.63%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                                          | 2         | 1.63%   |
| Intel Cannon Lake PCH CNVi WiFi                                                       | 2         | 1.63%   |
| Broadcom NetXtreme BCM5720 Gigabit Ethernet PCIe                                      | 2         | 1.63%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                                    | 2         | 1.63%   |
| VIA VT6102/VT6103 [Rhine-II]                                                          | 1         | 0.81%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                                          | 1         | 0.81%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter                              | 1         | 0.81%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                                       | 1         | 0.81%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                                                | 1         | 0.81%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                                   | 1         | 0.81%   |
| Realtek RTL8188EE Wireless Network Adapter                                            | 1         | 0.81%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                                               | 1         | 0.81%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                                 | 1         | 0.81%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                                                | 1         | 0.81%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller                             | 1         | 0.81%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                                      | 1         | 0.81%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                                      | 1         | 0.81%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)                        | 1         | 0.81%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                        | 1         | 0.81%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                         | 1         | 0.81%   |
| Qualcomm Atheros AR5418 Wireless Network Adapter [AR5008E 802.11(a)bgn] (PCI-Express) | 1         | 0.81%   |
| Oculus VR Rift S                                                                      | 1         | 0.81%   |
| Netchip Linux-USB Serial Gadget (CDC ACM mode)                                        | 1         | 0.81%   |
| Mercucys MERCUSYS Wireless USB Adapter                                                | 1         | 0.81%   |
| Marvell Group 88E8053 PCI-E Gigabit Ethernet Controller                               | 1         | 0.81%   |
| Intel Wireless 7260                                                                   | 1         | 0.81%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart_bsd/net_wireless_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Intel                 | 23        | 51.11%  |
| Qualcomm Atheros      | 9         | 20%     |
| Realtek Semiconductor | 5         | 11.11%  |
| Broadcom              | 5         | 11.11%  |
| TP-Link               | 1         | 2.22%   |
| Mercucys              | 1         | 2.22%   |
| D-Link                | 1         | 2.22%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart_bsd/net_wireless_model.svg)


| Model                                                                                 | Computers | Percent |
|---------------------------------------------------------------------------------------|-----------|---------|
| Intel Wireless-AC 9260                                                                | 3         | 6.52%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                            | 2         | 4.35%   |
| Qualcomm Atheros AR2413/AR2414 Wireless Network Adapter [AR5005G(S) 802.11bg]         | 2         | 4.35%   |
| Intel Wireless 8260                                                                   | 2         | 4.35%   |
| Intel Wireless 7265                                                                   | 2         | 4.35%   |
| Intel Wi-Fi 6 AX201 160MHz                                                            | 2         | 4.35%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                                      | 2         | 4.35%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                                          | 2         | 4.35%   |
| Intel Cannon Lake PCH CNVi WiFi                                                       | 2         | 4.35%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                                    | 2         | 4.35%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                                          | 1         | 2.17%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter                              | 1         | 2.17%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                                       | 1         | 2.17%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                                                | 1         | 2.17%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                                   | 1         | 2.17%   |
| Realtek RTL8188EE Wireless Network Adapter                                            | 1         | 2.17%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                                               | 1         | 2.17%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                                      | 1         | 2.17%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                                      | 1         | 2.17%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)                        | 1         | 2.17%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                        | 1         | 2.17%   |
| Qualcomm Atheros AR5418 Wireless Network Adapter [AR5008E 802.11(a)bgn] (PCI-Express) | 1         | 2.17%   |
| Mercucys MERCUSYS Wireless USB Adapter                                                | 1         | 2.17%   |
| Intel Wireless 7260                                                                   | 1         | 2.17%   |
| Intel Wi-Fi 6 AX200                                                                   | 1         | 2.17%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                                 | 1         | 2.17%   |
| Intel PRO/Wireless 2200BG [Calexico2] Network Connection                              | 1         | 2.17%   |
| Intel Gemini Lake PCH CNVi WiFi                                                       | 1         | 2.17%   |
| Intel CNVi: Wi-Fi                                                                     | 1         | 2.17%   |
| Intel Centrino Wireless-N 135                                                         | 1         | 2.17%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                                          | 1         | 2.17%   |
| D-Link DWA-131 Wireless N Nano Adapter (Rev. E1) [Realtek RTL8192EU]                  | 1         | 2.17%   |
| Broadcom BCM43602 802.11ac Wireless LAN SoC                                           | 1         | 2.17%   |
| Broadcom BCM4331 802.11a/b/g/n                                                        | 1         | 2.17%   |
| Broadcom BCM43142 802.11b/g/n                                                         | 1         | 2.17%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart_bsd/net_ethernet_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 33        | 47.14%  |
| Intel                    | 21        | 30%     |
| Broadcom                 | 5         | 7.14%   |
| Qualcomm Atheros         | 3         | 4.29%   |
| Huawei Technologies      | 3         | 4.29%   |
| VIA Technologies         | 1         | 1.43%   |
| Marvell Technology Group | 1         | 1.43%   |
| Davicom Semiconductor    | 1         | 1.43%   |
| Apple                    | 1         | 1.43%   |
| 3Com                     | 1         | 1.43%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart_bsd/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 30        | 42.25%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 6         | 8.45%   |
| Intel I211 Gigabit Network Connection                             | 3         | 4.23%   |
| Huawei USB Device                                                 | 3         | 4.23%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 2         | 2.82%   |
| Intel Ethernet Connection (2) I219-LM                             | 2         | 2.82%   |
| Broadcom NetXtreme BCM5720 Gigabit Ethernet PCIe                  | 2         | 2.82%   |
| VIA VT6102/VT6103 [Rhine-II]                                      | 1         | 1.41%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 1         | 1.41%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                            | 1         | 1.41%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 1         | 1.41%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 1         | 1.41%   |
| Marvell Group 88E8053 PCI-E Gigabit Ethernet Controller           | 1         | 1.41%   |
| Intel PRO/100 VE Network Connection                               | 1         | 1.41%   |
| Intel Ethernet Controller I225-V                                  | 1         | 1.41%   |
| Intel Ethernet Connection I219-V                                  | 1         | 1.41%   |
| Intel Ethernet Connection I219-LM                                 | 1         | 1.41%   |
| Intel Ethernet Connection I218-LM                                 | 1         | 1.41%   |
| Intel Ethernet Connection I217-V                                  | 1         | 1.41%   |
| Intel Ethernet Connection (3) I218-V                              | 1         | 1.41%   |
| Intel Ethernet Connection (2) I219-V                              | 1         | 1.41%   |
| Intel 82801DB PRO/100 VE (MOB) Ethernet Controller                | 1         | 1.41%   |
| Intel 82577LM Gigabit Network Connection                          | 1         | 1.41%   |
| Intel 82574L Gigabit Network Connection                           | 1         | 1.41%   |
| Davicom DM9102 Fast Ethernet Controller                           | 1         | 1.41%   |
| Broadcom NetXtreme BCM57766 Gigabit Ethernet PCIe                 | 1         | 1.41%   |
| Broadcom NetXtreme BCM57762 Gigabit Ethernet PCIe                 | 1         | 1.41%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 1         | 1.41%   |
| Apple Ethernet Adapter [A1277]                                    | 1         | 1.41%   |
| 3Com 3c905C-TX/TX-M [Tornado]                                     | 1         | 1.41%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart_bsd/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 64        | 57.14%  |
| WiFi     | 42        | 37.5%   |
| Modem    | 4         | 3.57%   |
| Unknown  | 2         | 1.79%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart_bsd/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 51        | 71.83%  |
| WiFi     | 19        | 26.76%  |
| Unknown  | 1         | 1.41%   |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart_bsd/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 34        | 47.89%  |
| 1     | 21        | 29.58%  |
| 0     | 10        | 14.08%  |
| 3     | 5         | 7.04%   |
| 4     | 1         | 1.41%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart_bsd/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 59        | 81.94%  |
| Yes  | 13        | 18.06%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart_bsd/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 15        | 53.57%  |
| Apple                           | 5         | 17.86%  |
| Realtek Semiconductor           | 2         | 7.14%   |
| Broadcom                        | 2         | 7.14%   |
| Qualcomm Atheros Communications | 1         | 3.57%   |
| Lite-On Technology              | 1         | 3.57%   |
| IMC Networks                    | 1         | 3.57%   |
| Cambridge Silicon Radio         | 1         | 3.57%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart_bsd/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 5         | 17.86%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 4         | 14.29%  |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 2         | 7.14%   |
| Intel Wireless-AC 3168 Bluetooth                    | 2         | 7.14%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 2         | 7.14%   |
| Apple Broadcom Built-in Bluetooth                   | 2         | 7.14%   |
| Apple Bluetooth Host Controller                     | 2         | 7.14%   |
| Realtek Bluetooth Adapter                           | 1         | 3.57%   |
| Realtek Bluetooth 4.0 Adapter                       | 1         | 3.57%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 1         | 3.57%   |
| Lite-On Atheros AR3012 Bluetooth                    | 1         | 3.57%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 1         | 3.57%   |
| Intel AX201 Bluetooth                               | 1         | 3.57%   |
| IMC Networks Qualcomm Atheros Bluetooth 4.0 + HS    | 1         | 3.57%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 1         | 3.57%   |
| Apple Built-in iSight (no firmware loaded)          | 1         | 3.57%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart_bsd/snd_vendor.svg)


| Vendor                                       | Computers | Percent |
|----------------------------------------------|-----------|---------|
| Intel                                        | 45        | 56.25%  |
| AMD                                          | 19        | 23.75%  |
| Nvidia                                       | 8         | 10%     |
| Zoran Co. Personal Media Division (Nogatech) | 1         | 1.25%   |
| Yamaha                                       | 1         | 1.25%   |
| VIA Technologies                             | 1         | 1.25%   |
| Samsung Electronics                          | 1         | 1.25%   |
| Native Instruments                           | 1         | 1.25%   |
| Logitech                                     | 1         | 1.25%   |
| ESS Technology                               | 1         | 1.25%   |
| Creative Labs                                | 1         | 1.25%   |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart_bsd/snd_model.svg)


| Model                                                                             | Computers | Percent |
|-----------------------------------------------------------------------------------|-----------|---------|
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller               | 8         | 7.92%   |
| AMD SBx00 Azalia (Intel HDA)                                                      | 6         | 5.94%   |
| Intel Wildcat Point-LP High Definition Audio Controller                           | 4         | 3.96%   |
| Intel Broadwell-U Audio Controller                                                | 4         | 3.96%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                   | 4         | 3.96%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                               | 4         | 3.96%   |
| Intel Cannon Lake PCH cAVS                                                        | 3         | 2.97%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller               | 3         | 2.97%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller        | 3         | 2.97%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                        | 3         | 2.97%   |
| Nvidia GP107GL High Definition Audio Controller                                   | 2         | 1.98%   |
| Nvidia GF114 HDMI Audio Controller                                                | 2         | 1.98%   |
| Intel Sunrise Point-LP HD Audio                                                   | 2         | 1.98%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                           | 2         | 1.98%   |
| Intel Jasper Lake HD Audio                                                        | 2         | 1.98%   |
| Intel Haswell-ULT HD Audio Controller                                             | 2         | 1.98%   |
| Intel Alder Lake-N HD Graphics SGPC                                               | 2         | 1.98%   |
| Intel 82801DB/DBL/DBM (ICH4/ICH4-L/ICH4-M) AC'97 Audio Controller                 | 2         | 1.98%   |
| Intel 8 Series HD Audio Controller                                                | 2         | 1.98%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                          | 2         | 1.98%   |
| AMD Wrestler HDMI Audio                                                           | 2         | 1.98%   |
| AMD Starship/Matisse HD Audio Controller                                          | 2         | 1.98%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                               | 2         | 1.98%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]           | 2         | 1.98%   |
| AMD Family 17h/19h HD Audio Controller                                            | 2         | 1.98%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                            | 2         | 1.98%   |
| AMD Caicos HDMI Audio [Radeon HD 6450 / 7450/8450/8490 OEM / R5 230/235/235X OEM] | 2         | 1.98%   |
| Zoran Co. Personal Media Division (Nogatech) USB Audio and HID                    | 1         | 0.99%   |
| Yamaha AG06/AG03                                                                  | 1         | 0.99%   |
| VIA Technologies VT8233/A/8235/8237 AC97 Audio Controller                         | 1         | 0.99%   |
| Samsung Electronics Samsung Type-C to 3.5pi gender adapter                        | 1         | 0.99%   |
| Nvidia High Definition Audio Controller                                           | 1         | 0.99%   |
| Nvidia GT216 HDMI Audio Controller                                                | 1         | 0.99%   |
| Nvidia GP106 High Definition Audio Controller                                     | 1         | 0.99%   |
| Nvidia GM204 High Definition Audio Controller                                     | 1         | 0.99%   |
| Native Instruments Komplete Audio 1                                               | 1         | 0.99%   |
| Logitech Zone Wired Earbuds                                                       | 1         | 0.99%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                  | 1         | 0.99%   |
| Intel Comet Lake PCH-V cAVS                                                       | 1         | 0.99%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                      | 1         | 0.99%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart_bsd/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Unknown             | 8         | 14.81%  |
| Kingston            | 8         | 14.81%  |
| Crucial             | 8         | 14.81%  |
| Samsung Electronics | 6         | 11.11%  |
| Micron Technology   | 5         | 9.26%   |
| SK hynix            | 4         | 7.41%   |
| G.Skill             | 3         | 5.56%   |
| A-DATA Technology   | 3         | 5.56%   |
| Ramaxel Technology  | 2         | 3.7%    |
| Patriot             | 2         | 3.7%    |
| Corsair             | 2         | 3.7%    |
| SHARETRONIC         | 1         | 1.85%   |
| Nanya Technology    | 1         | 1.85%   |
| Unknown             | 1         | 1.85%   |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart_bsd/memory_model.svg)


| Model                                                      | Computers | Percent |
|------------------------------------------------------------|-----------|---------|
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1867MT/s      | 2         | 3.39%   |
| Micron RAM Module 8GB Chip LPDDR4                          | 2         | 3.39%   |
| Unknown RAM Module 8192MB DIMM 400MT/s                     | 1         | 1.69%   |
| Unknown RAM Module 512MB SODIMM DRAM 166MT/s               | 1         | 1.69%   |
| Unknown RAM Module 512MB SODIMM DDR2 533MT/s               | 1         | 1.69%   |
| Unknown RAM Module 2GB SODIMM DDR3                         | 1         | 1.69%   |
| Unknown RAM Module 256MB SODIMM DDR                        | 1         | 1.69%   |
| Unknown RAM Module 2048MB DIMM DDR2 800MT/s                | 1         | 1.69%   |
| Unknown RAM Module 2048MB DIMM 400MT/s                     | 1         | 1.69%   |
| Unknown RAM Module 128MB DIMM DRAM                         | 1         | 1.69%   |
| Unknown RAM Module 1024MB SODIMM SDRAM 266MT/s             | 1         | 1.69%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s     | 1         | 1.69%   |
| SK hynix RAM HMT351S6BFR8C-H9 4GB SODIMM DDR3 1334MT/s     | 1         | 1.69%   |
| SK hynix RAM HMT351S6BFR8C-H9 4GB SODIMM DDR3 1333MT/s     | 1         | 1.69%   |
| SK hynix RAM HMT325S6EFR8A-PB 2GB SODIMM DDR3 1600MT/s     | 1         | 1.69%   |
| SHARETRONIC RAM Module 2048MB SODIMM DDR3 1600MT/s         | 1         | 1.69%   |
| Samsung RAM M471B5673FH0-CF8 2GB SODIMM 1067MT/s           | 1         | 1.69%   |
| Samsung RAM M471B5273EB0-CK0 4GB SODIMM DDR3 1600MT/s      | 1         | 1.69%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s      | 1         | 1.69%   |
| Samsung RAM M386B4G70DM0-YK04 32GB DIMM DDR3 1600MT/s      | 1         | 1.69%   |
| Samsung RAM M386B4G70DM0-YK03 32GB DIMM DDR3 1600MT/s      | 1         | 1.69%   |
| Ramaxel RAM RMT3160ED58E9W1600 4GB SODIMM DDR3 1600MT/s    | 1         | 1.69%   |
| Ramaxel RAM RMSA3230KB78HAF2133 8GB SODIMM DDR4 2133MT/s   | 1         | 1.69%   |
| Patriot RAM PSD44G213382 4096MB DIMM DDR4 2133MT/s         | 1         | 1.69%   |
| Patriot RAM PSD34G13332 4GB DIMM DDR3 1333MT/s             | 1         | 1.69%   |
| Nanya RAM NT2GC64B88B0NS-CG 2GB SODIMM DDR3 1334MT/s       | 1         | 1.69%   |
| Micron RAM 8KTF51264HZ-1G6N1 4GB SODIMM DDR3 1600MT/s      | 1         | 1.69%   |
| Micron RAM 36ASF2G72PZ-2G1A2 16GB DIMM DDR4 2133MT/s       | 1         | 1.69%   |
| Micron RAM 16JSF51264HZ-1G1D1 4GB SODIMM DDR3 1067MT/s     | 1         | 1.69%   |
| Kingston RAM KHX2400C15/8G 8GB DIMM DDR4 2400MT/s          | 1         | 1.69%   |
| Kingston RAM KHX1600C9D3/4GX 4GB DIMM DDR3 1600MT/s        | 1         | 1.69%   |
| Kingston RAM ACR26D4S9S8ME-8 8GB SODIMM DDR4 2667MT/s      | 1         | 1.69%   |
| Kingston RAM ACR16D3LS1KFG/4G 4GB DIMM DDR3 1600MT/s       | 1         | 1.69%   |
| Kingston RAM ACR16D3LFS1KBG/2G 2GB SODIMM DDR3 1600MT/s    | 1         | 1.69%   |
| Kingston RAM 99U5701-077.A00G 16GB DIMM DDR4 2667MT/s      | 1         | 1.69%   |
| Kingston RAM 99U5471-028.A00LF 4GB DIMM DDR3 667MT/s       | 1         | 1.69%   |
| Kingston RAM 9905471-011.A00LF 4GB DIMM DDR3 1333MT/s      | 1         | 1.69%   |
| Kingston RAM 9905428-026.A02LF 2048MB SODIMM DDR3 1066MT/s | 1         | 1.69%   |
| G.Skill RAM F4-3200C16-16GVK 16GB DIMM DDR4 3200MT/s       | 1         | 1.69%   |
| G.Skill RAM F4-2800C17-8GVR 8192MB DIMM DDR4 2133MT/s      | 1         | 1.69%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart_bsd/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR3    | 21        | 45.65%  |
| DDR4    | 16        | 34.78%  |
| LPDDR4  | 2         | 4.35%   |
| DRAM    | 2         | 4.35%   |
| DDR2    | 2         | 4.35%   |
| SDRAM   | 1         | 2.17%   |
| DDR     | 1         | 2.17%   |
| Unknown | 1         | 2.17%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart_bsd/memory_formfactor.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| DIMM   | 23        | 50%     |
| SODIMM | 20        | 43.48%  |
| Chip   | 3         | 6.52%   |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart_bsd/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 17        | 35.42%  |
| 4096  | 14        | 29.17%  |
| 2048  | 7         | 14.58%  |
| 16384 | 4         | 8.33%   |
| 512   | 2         | 4.17%   |
| 32768 | 1         | 2.08%   |
| 1024  | 1         | 2.08%   |
| 256   | 1         | 2.08%   |
| 128   | 1         | 2.08%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart_bsd/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 13        | 24.53%  |
| 2133    | 5         | 9.43%   |
| Unknown | 5         | 9.43%   |
| 1333    | 4         | 7.55%   |
| 3200    | 3         | 5.66%   |
| 2667    | 3         | 5.66%   |
| 2400    | 3         | 5.66%   |
| 1867    | 2         | 3.77%   |
| 1334    | 2         | 3.77%   |
| 1067    | 2         | 3.77%   |
| 800     | 2         | 3.77%   |
| 3000    | 1         | 1.89%   |
| 2933    | 1         | 1.89%   |
| 2666    | 1         | 1.89%   |
| 1066    | 1         | 1.89%   |
| 667     | 1         | 1.89%   |
| 533     | 1         | 1.89%   |
| 400     | 1         | 1.89%   |
| 266     | 1         | 1.89%   |
| 166     | 1         | 1.89%   |

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
| Chicony Electronics           | 7         | 36.84%  |
| Silicon Motion                | 2         | 10.53%  |
| Realtek Semiconductor         | 2         | 10.53%  |
| Syntek                        | 1         | 5.26%   |
| Sunplus Innovation Technology | 1         | 5.26%   |
| Quanta                        | 1         | 5.26%   |
| Logitech                      | 1         | 5.26%   |
| Lenovo                        | 1         | 5.26%   |
| Bison Electronics             | 1         | 5.26%   |
| ARC International             | 1         | 5.26%   |
| ALi                           | 1         | 5.26%   |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart_bsd/camera_model.svg)


| Model                                | Computers | Percent |
|--------------------------------------|-----------|---------|
| Chicony Integrated Camera            | 3         | 15.79%  |
| Syntek Lenovo EasyCamera             | 1         | 5.26%   |
| Sunplus Integrated Camera            | 1         | 5.26%   |
| Silicon Motion WebCam SC-10IRQ12340N | 1         | 5.26%   |
| Silicon Motion 300k Pixel Camera     | 1         | 5.26%   |
| Realtek USB Camera                   | 1         | 5.26%   |
| Realtek Acer 640 x 480 laptop camera | 1         | 5.26%   |
| Quanta VGA WebCam                    | 1         | 5.26%   |
| Logitech Webcam C270                 | 1         | 5.26%   |
| Lenovo Integrated Webcam [R5U877]    | 1         | 5.26%   |
| Chicony USB2.0 VGA UVC WebCam        | 1         | 5.26%   |
| Chicony Thinkpad T430 camera         | 1         | 5.26%   |
| Chicony HP HD Webcam [Fixed]         | 1         | 5.26%   |
| Chicony Front Camera                 | 1         | 5.26%   |
| Bison Integrated Camera              | 1         | 5.26%   |
| ARC International Camera             | 1         | 5.26%   |
| ALi Gateway Webcam                   | 1         | 5.26%   |

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
| 0     | 25        | 34.72%  |
| 1     | 20        | 27.78%  |
| 2     | 17        | 23.61%  |
| 3     | 6         | 8.33%   |
| 5     | 2         | 2.78%   |
| 4     | 2         | 2.78%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart_bsd/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Communication controller | 39        | 48.75%  |
| Net/wireless             | 22        | 27.5%   |
| Card reader              | 7         | 8.75%   |
| Graphics card            | 5         | 6.25%   |
| Storage                  | 2         | 2.5%    |
| Net/ethernet             | 2         | 2.5%    |
| Wireless                 | 1         | 1.25%   |
| Modem                    | 1         | 1.25%   |
| Bluetooth                | 1         | 1.25%   |

