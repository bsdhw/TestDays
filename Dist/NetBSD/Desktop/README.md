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

Total: 69

| Vendor   | Model                   | Probe                                                     | Date         |
|----------|-------------------------|-----------------------------------------------------------|--------------|
| ASUSTek  | TUF B450-PRO GAMING     | [d318950ac5](https://bsd-hardware.info/?probe=d318950ac5) | Jan 15, 2024 |
| Unknown  | Unknown                 | [5deb235717](https://bsd-hardware.info/?probe=5deb235717) | Jan 05, 2024 |
| Unknown  | Unknown                 | [d4bedea996](https://bsd-hardware.info/?probe=d4bedea996) | Dec 30, 2023 |
| Unknown  | Unknown                 | [19daaf5eee](https://bsd-hardware.info/?probe=19daaf5eee) | Dec 30, 2023 |
| Lenovo   | NO DPK                  | [424c33d278](https://bsd-hardware.info/?probe=424c33d278) | Oct 27, 2023 |
| Unknown  | Unknown                 | [a88541d6a6](https://bsd-hardware.info/?probe=a88541d6a6) | Oct 27, 2023 |
| Lenovo   | NO DPK                  | [753b30d88b](https://bsd-hardware.info/?probe=753b30d88b) | Oct 27, 2023 |
| ASRock   | H270 Pro4               | [cba80ecde3](https://bsd-hardware.info/?probe=cba80ecde3) | Sep 24, 2023 |
| Unknown  | Unknown                 | [dcf1ebd901](https://bsd-hardware.info/?probe=dcf1ebd901) | Sep 20, 2023 |
| Unknown  | Unknown                 | [1808e7891c](https://bsd-hardware.info/?probe=1808e7891c) | Sep 16, 2023 |
| Unknown  | Unknown                 | [9c1891cda7](https://bsd-hardware.info/?probe=9c1891cda7) | Sep 03, 2023 |
| Unknown  | Unknown                 | [29fc7f6f45](https://bsd-hardware.info/?probe=29fc7f6f45) | Aug 19, 2023 |
| Gigabyte | A320M-H-CF              | [d1a2b99edc](https://bsd-hardware.info/?probe=d1a2b99edc) | Jul 28, 2023 |
| Acer     | Revo RN86               | [2e52c2b9b2](https://bsd-hardware.info/?probe=2e52c2b9b2) | May 13, 2023 |
| Unknown  | Unknown                 | [d6f92a5ecc](https://bsd-hardware.info/?probe=d6f92a5ecc) | Apr 28, 2023 |
| Gigabyte | B360M D2V               | [f73cb94828](https://bsd-hardware.info/?probe=f73cb94828) | Apr 17, 2023 |
| Unknown  | Unknown                 | [8c93a7e552](https://bsd-hardware.info/?probe=8c93a7e552) | Mar 04, 2023 |
| Unknown  | Unknown                 | [85fdc49ec4](https://bsd-hardware.info/?probe=85fdc49ec4) | Mar 03, 2023 |
| Unknown  | Unknown                 | [8ae1891a85](https://bsd-hardware.info/?probe=8ae1891a85) | Feb 16, 2023 |
| Intel    | DN2820FYK H24582-203    | [ae05d4c6cd](https://bsd-hardware.info/?probe=ae05d4c6cd) | Feb 06, 2023 |
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
| NetBSD 9.3        | 10       | 17.54%  |
| NetBSD 9.2        | 8        | 14.04%  |
| NetBSD 9.1        | 7        | 12.28%  |
| NetBSD 9.0_STABLE | 5        | 8.77%   |
| NetBSD 9.1_STABLE | 3        | 5.26%   |
| NetBSD 10.0_BETA  | 3        | 5.26%   |
| NetBSD 9.99.94    | 2        | 3.51%   |
| NetBSD 9.99.93    | 2        | 3.51%   |
| NetBSD 9.99.77    | 2        | 3.51%   |
| NetBSD 9.3_STABLE | 2        | 3.51%   |
| NetBSD 9.0        | 2        | 3.51%   |
| NetBSD 10.0_RC2   | 2        | 3.51%   |
| NetBSD 9.99.85    | 1        | 1.75%   |
| NetBSD 9.99.81    | 1        | 1.75%   |
| NetBSD 9.99.74    | 1        | 1.75%   |
| NetBSD 9.99.71    | 1        | 1.75%   |
| NetBSD 9.99.61    | 1        | 1.75%   |
| NetBSD 9.99.23    | 1        | 1.75%   |
| NetBSD 9.99.107   | 1        | 1.75%   |
| NetBSD 9.2_STABLE | 1        | 1.75%   |
| NetBSD 10.0_RC1   | 1        | 1.75%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart_bsd/os_family.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| NetBSD | 49       | 100%    |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart_bsd/os_arch.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| amd64   | 40       | 81.63%  |
| evbarm  | 5        | 10.2%   |
| macppc  | 2        | 4.08%   |
| sparc64 | 1        | 2.04%   |
| i386    | 1        | 2.04%   |

DE
--

Desktop Environment

![DE](./images/pie_chart_bsd/os_de.svg)


| Name         | Desktops | Percent |
|--------------|----------|---------|
| Console      | 19       | 38%     |
| XFCE         | 12       | 24%     |
| helloDesktop | 8        | 16%     |
| Fluxbox      | 2        | 4%      |
| CTWM         | 2        | 4%      |
| Xfwm4        | 1        | 2%      |
| Window Maker | 1        | 2%      |
| Ratpoison    | 1        | 2%      |
| PekWM        | 1        | 2%      |
| MATE         | 1        | 2%      |
| JWM          | 1        | 2%      |
| DWM          | 1        | 2%      |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart_bsd/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| X11     | 35       | 71.43%  |
| Console | 14       | 28.57%  |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart_bsd/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Console | 44       | 89.8%   |
| XDM     | 3        | 6.12%   |
| LightDM | 1        | 2.04%   |
| GDM     | 1        | 2.04%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart_bsd/os_lang.svg)


| Lang    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 38       | 71.7%   |
| en_US   | 7        | 13.21%  |
| ru_RU   | 2        | 3.77%   |
| fi_FI   | 2        | 3.77%   |
| C       | 2        | 3.77%   |
| hu_HU   | 1        | 1.89%   |
| en_GB   | 1        | 1.89%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart_bsd/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| BIOS | 45       | 91.84%  |
| EFI  | 4        | 8.16%   |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart_bsd/os_filesystem.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Ufs     | 48       | 97.96%  |
| Unknown | 1        | 2.04%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart_bsd/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| GPT     | 34       | 69.39%  |
| Unknown | 15       | 30.61%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart_bsd/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| Unknown             | 25       | 51.02%  |
| ASUSTek Computer    | 7        | 14.29%  |
| Gigabyte Technology | 6        | 12.24%  |
| ASRock              | 4        | 8.16%   |
| MSI                 | 2        | 4.08%   |
| Lenovo              | 1        | 2.04%   |
| KLLISRE             | 1        | 2.04%   |
| Intel               | 1        | 2.04%   |
| Hewlett-Packard     | 1        | 2.04%   |
| Acer                | 1        | 2.04%   |

Model
-----

Motherboard model

![Model](./images/pie_chart_bsd/node_model.svg)


| Name                            | Desktops | Percent |
|---------------------------------|----------|---------|
| Unknown                         | 25       | 51.02%  |
| ASUS PRIME A320M-K              | 2        | 4.08%   |
| MSI MS-7B86                     | 1        | 2.04%   |
| MSI MS-7551                     | 1        | 2.04%   |
| Lenovo ThinkCentre M72e 3598CP8 | 1        | 2.04%   |
| KLLISRE X99-B5 V1.0             | 1        | 2.04%   |
| Intel DN2820FYK H24582-203      | 1        | 2.04%   |
| HP Vectra                       | 1        | 2.04%   |
| Gigabyte Z170X-Gaming 3         | 1        | 2.04%   |
| Gigabyte X570 AORUS PRO         | 1        | 2.04%   |
| Gigabyte P75-D3                 | 1        | 2.04%   |
| Gigabyte H61M-S2PV              | 1        | 2.04%   |
| Gigabyte A320M-H                | 1        | 2.04%   |
| Gigabyte 970A-D3P               | 1        | 2.04%   |
| ASUS TUF B450-PRO GAMING        | 1        | 2.04%   |
| ASUS TUF B450-PLUS GAMING       | 1        | 2.04%   |
| ASUS E45M1-I DELUXE             | 1        | 2.04%   |
| ASUS B150M-K                    | 1        | 2.04%   |
| ASUS All Series                 | 1        | 2.04%   |
| ASRock X470 Gaming-ITX/ac       | 1        | 2.04%   |
| ASRock N68-VS3 UCC              | 1        | 2.04%   |
| ASRock H270 Pro4                | 1        | 2.04%   |
| ASRock 970 Extreme3             | 1        | 2.04%   |
| Acer Revo RN86                  | 1        | 2.04%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart_bsd/node_model_family.svg)


| Name                  | Desktops | Percent |
|-----------------------|----------|---------|
| Unknown               | 25       | 51.02%  |
| ASUS TUF              | 2        | 4.08%   |
| ASUS PRIME            | 2        | 4.08%   |
| MSI MS-7B86           | 1        | 2.04%   |
| MSI MS-7551           | 1        | 2.04%   |
| Lenovo ThinkCentre    | 1        | 2.04%   |
| KLLISRE X99-B5        | 1        | 2.04%   |
| Intel DN2820FYK       | 1        | 2.04%   |
| HP Vectra             | 1        | 2.04%   |
| Gigabyte Z170X-Gaming | 1        | 2.04%   |
| Gigabyte X570         | 1        | 2.04%   |
| Gigabyte P75-D3       | 1        | 2.04%   |
| Gigabyte H61M-S2PV    | 1        | 2.04%   |
| Gigabyte A320M-H      | 1        | 2.04%   |
| Gigabyte 970A-D3P     | 1        | 2.04%   |
| ASUS E45M1-I          | 1        | 2.04%   |
| ASUS B150M-K          | 1        | 2.04%   |
| ASUS All              | 1        | 2.04%   |
| ASRock X470           | 1        | 2.04%   |
| ASRock N68-VS3        | 1        | 2.04%   |
| ASRock H270           | 1        | 2.04%   |
| ASRock 970            | 1        | 2.04%   |
| Acer Revo             | 1        | 2.04%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart_bsd/node_year.svg)


| Year    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 22       | 44.9%   |
| 2020    | 5        | 10.2%   |
| 2018    | 5        | 10.2%   |
| 2013    | 3        | 6.12%   |
| 2022    | 2        | 4.08%   |
| 2017    | 2        | 4.08%   |
| 2014    | 2        | 4.08%   |
| 2012    | 2        | 4.08%   |
| 2021    | 1        | 2.04%   |
| 2019    | 1        | 2.04%   |
| 2015    | 1        | 2.04%   |
| 2011    | 1        | 2.04%   |
| 2010    | 1        | 2.04%   |
| 2001    | 1        | 2.04%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart_bsd/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 49       | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart_bsd/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 49       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart_bsd/node_ram_total.svg)


| Size in GB  | Desktops | Percent |
|-------------|----------|---------|
| 4.01-8.0    | 11       | 22.45%  |
| 16.01-24.0  | 10       | 20.41%  |
| 8.01-16.0   | 8        | 16.33%  |
| 32.01-64.0  | 5        | 10.2%   |
| 3.01-4.0    | 4        | 8.16%   |
| 0.01-0.5    | 4        | 8.16%   |
| 0.51-1.0    | 3        | 6.12%   |
| 1.01-2.0    | 2        | 4.08%   |
| 24.01-32.0  | 1        | 2.04%   |
| 64.01-256.0 | 1        | 2.04%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart_bsd/node_ram_used.svg)


| Used GB | Desktops | Percent |
|---------|----------|---------|
| Unknown | 49       | 100%    |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart_bsd/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 0      | 23       | 44.23%  |
| 1      | 15       | 28.85%  |
| 2      | 10       | 19.23%  |
| 3      | 3        | 5.77%   |
| 4      | 1        | 1.92%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart_bsd/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 49       | 100%    |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart_bsd/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 40       | 81.63%  |
| No        | 9        | 18.37%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart_bsd/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 28       | 57.14%  |
| Yes       | 21       | 42.86%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart_bsd/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 33       | 67.35%  |
| Yes       | 16       | 32.65%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart_bsd/node_location.svg)


| Country      | Desktops | Percent |
|--------------|----------|---------|
| Russia       | 10       | 20.41%  |
| USA          | 5        | 10.2%   |
| Germany      | 5        | 10.2%   |
| Italy        | 4        | 8.16%   |
| UK           | 3        | 6.12%   |
| France       | 3        | 6.12%   |
| Spain        | 2        | 4.08%   |
| Romania      | 2        | 4.08%   |
| Poland       | 2        | 4.08%   |
| Japan        | 2        | 4.08%   |
| Hungary      | 2        | 4.08%   |
| Finland      | 2        | 4.08%   |
| Saudi Arabia | 1        | 2.04%   |
| Netherlands  | 1        | 2.04%   |
| Latvia       | 1        | 2.04%   |
| India        | 1        | 2.04%   |
| Czechia      | 1        | 2.04%   |
| Brazil       | 1        | 2.04%   |
| Australia    | 1        | 2.04%   |

City
----

Geographic location (city)

![City](./images/pie_chart_bsd/node_city.svg)


| City                  | Desktops | Percent |
|-----------------------|----------|---------|
| Ozersk                | 6        | 12.24%  |
| Rome                  | 3        | 6.12%   |
| Moscow                | 3        | 6.12%   |
| Lille                 | 3        | 6.12%   |
| Tampere               | 2        | 4.08%   |
| Higashihatsuishi      | 2        | 4.08%   |
| Bucharest             | 2        | 4.08%   |
| Urupes                | 1        | 2.04%   |
| Unterhaching          | 1        | 2.04%   |
| Ulan-Ude              | 1        | 2.04%   |
| Turin                 | 1        | 2.04%   |
| Sydney                | 1        | 2.04%   |
| Stourbridge           | 1        | 2.04%   |
| Sopron                | 1        | 2.04%   |
| Royal Tunbridge Wells | 1        | 2.04%   |
| Riyadh                | 1        | 2.04%   |
| Riga                  | 1        | 2.04%   |
| Reno                  | 1        | 2.04%   |
| Prague                | 1        | 2.04%   |
| Poznan                | 1        | 2.04%   |
| Portland              | 1        | 2.04%   |
| Murcia                | 1        | 2.04%   |
| Lohr a. Main          | 1        | 2.04%   |
| Kwidzyn               | 1        | 2.04%   |
| Hayward               | 1        | 2.04%   |
| Hamilton              | 1        | 2.04%   |
| Gardony               | 1        | 2.04%   |
| Fort Wayne            | 1        | 2.04%   |
| Deggendorf            | 1        | 2.04%   |
| Chennai               | 1        | 2.04%   |
| Bormujos              | 1        | 2.04%   |
| Bloomsbury            | 1        | 2.04%   |
| Berlin                | 1        | 2.04%   |
| Amersfoort            | 1        | 2.04%   |
| Aachen                | 1        | 2.04%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart_bsd/drive_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 8        | 11     | 18.6%   |
| Samsung Electronics | 5        | 5      | 11.63%  |
| Toshiba             | 4        | 6      | 9.3%    |
| Seagate             | 4        | 4      | 9.3%    |
| SanDisk             | 4        | 5      | 9.3%    |
| Kingston            | 4        | 5      | 9.3%    |
| Maxtor              | 3        | 3      | 6.98%   |
| Crucial             | 2        | 3      | 4.65%   |
| SK hynix            | 1        | 2      | 2.33%   |
| Lexar               | 1        | 1      | 2.33%   |
| JetFlash            | 1        | 1      | 2.33%   |
| Intenso             | 1        | 1      | 2.33%   |
| IBM/Hitachi         | 1        | 1      | 2.33%   |
| HGST                | 1        | 1      | 2.33%   |
| Hewlett-Packard     | 1        | 1      | 2.33%   |
| Generic             | 1        | 1      | 2.33%   |
| China               | 1        | 1      | 2.33%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart_bsd/drive_model.svg)


| Model                             | Desktops | Percent |
|-----------------------------------|----------|---------|
| Toshiba DT01ACA100 1TB            | 3        | 6.82%   |
| SanDisk Extreme SSD 500GB         | 2        | 4.55%   |
| Samsung SSD 860 EVO 500GB         | 2        | 4.55%   |
| Samsung HD103UJ 1TB               | 2        | 4.55%   |
| Maxtor STM3250310AS 250GB         | 2        | 4.55%   |
| Kingston DataTraveler 3.0 32GB    | 2        | 4.55%   |
| WDC WDS240G2G0A-00JH30 240GB      | 1        | 2.27%   |
| WDC WDS120G2G0A-00JH30 120GB      | 1        | 2.27%   |
| WDC WD5003AZEX-00K3CA0 500GB      | 1        | 2.27%   |
| WDC WD5000AAKX-753CA1 500GB       | 1        | 2.27%   |
| WDC WD5000AACS-00ZUB0 500GB       | 1        | 2.27%   |
| WDC WD2502ABYS-01B7A0 256GB       | 1        | 2.27%   |
| WDC WD20EFRX-68EUZN0 2TB          | 1        | 2.27%   |
| WDC WD200EB-00BHF0 20GB           | 1        | 2.27%   |
| WDC WD10EZEX-60WN4A0 1TB          | 1        | 2.27%   |
| Toshiba DT01ACA200 2TB            | 1        | 2.27%   |
| SK hynix HFS128G39TND-N210A 128GB | 1        | 2.27%   |
| Seagate ST940110A 40GB            | 1        | 2.27%   |
| Seagate ST380011A 80GB            | 1        | 2.27%   |
| Seagate ST2000DL003-9VT166 2TB    | 1        | 2.27%   |
| Seagate ST1000DM010-2EP102 1TB    | 1        | 2.27%   |
| SanDisk SDSSDH3512G 512GB         | 1        | 2.27%   |
| SanDisk Cruzer Glide 16GB         | 1        | 2.27%   |
| Samsung HD501LJ 500GB             | 1        | 2.27%   |
| Maxtor 6E040L0 40GB               | 1        | 2.27%   |
| Lexar USB Flash Drive 64GB        | 1        | 2.27%   |
| Kingston SM2280S3G2120G 120GB     | 1        | 2.27%   |
| Kingston SA400S37480G 480GB       | 1        | 2.27%   |
| JetFlash Transcend 16GB           | 1        | 2.27%   |
| Intenso Rainbow Line 8GB          | 1        | 2.27%   |
| IBM/Hitachi IC25N040ATMR04-0 40GB | 1        | 2.27%   |
| HGST HTS541010A9E680 1TB          | 1        | 2.27%   |
| HP v100w 8GB                      | 1        | 2.27%   |
| Generic Flash Disk 2GB            | 1        | 2.27%   |
| Crucial CT240BX500SSD1 240GB      | 1        | 2.27%   |
| Crucial CT1000BX500SSD1 1TB       | 1        | 2.27%   |
| China SATA SSD 120GB              | 1        | 2.27%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart_bsd/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 7        | 9      | 25%     |
| Toshiba             | 4        | 6      | 14.29%  |
| Seagate             | 4        | 4      | 14.29%  |
| Samsung Electronics | 3        | 3      | 10.71%  |
| Maxtor              | 3        | 3      | 10.71%  |
| Lexar               | 1        | 1      | 3.57%   |
| JetFlash            | 1        | 1      | 3.57%   |
| Intenso             | 1        | 1      | 3.57%   |
| IBM/Hitachi         | 1        | 1      | 3.57%   |
| HGST                | 1        | 1      | 3.57%   |
| Hewlett-Packard     | 1        | 1      | 3.57%   |
| Generic             | 1        | 1      | 3.57%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart_bsd/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| SanDisk             | 4        | 5      | 25%     |
| Kingston            | 4        | 5      | 25%     |
| WDC                 | 2        | 2      | 12.5%   |
| Samsung Electronics | 2        | 2      | 12.5%   |
| Crucial             | 2        | 3      | 12.5%   |
| SK hynix            | 1        | 2      | 6.25%   |
| China               | 1        | 1      | 6.25%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart_bsd/drive_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 21       | 32     | 58.33%  |
| SSD  | 15       | 20     | 41.67%  |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart_bsd/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 29       | 52     | 100%    |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart_bsd/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 28       | 35     | 70%     |
| 0.51-1.0   | 10       | 13     | 25%     |
| 1.01-2.0   | 2        | 4      | 5%      |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart_bsd/drive_space_total.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| 101-250    | 14       | 28.57%  |
| 251-500    | 8        | 16.33%  |
| 501-1000   | 7        | 14.29%  |
| 1-20       | 6        | 12.24%  |
| 21-50      | 5        | 10.2%   |
| 51-100     | 4        | 8.16%   |
| 2001-3000  | 3        | 6.12%   |
| 1001-2000  | 2        | 4.08%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart_bsd/drive_space_used.svg)


| Used GB   | Desktops | Percent |
|-----------|----------|---------|
| 1-20      | 38       | 70.37%  |
| 21-50     | 7        | 12.96%  |
| 51-100    | 3        | 5.56%   |
| 251-500   | 2        | 3.7%    |
| 1001-2000 | 2        | 3.7%    |
| 101-250   | 1        | 1.85%   |
| 501-1000  | 1        | 1.85%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart_bsd/drive_malfunc.svg)


| Model                             | Desktops | Drives | Percent |
|-----------------------------------|----------|--------|---------|
| WDC WDS240G2G0A-00JH30 240GB      | 1        | 1      | 16.67%  |
| WDC WD10EZEX-60WN4A0 1TB          | 1        | 1      | 16.67%  |
| SK hynix HFS128G39TND-N210A 128GB | 1        | 1      | 16.67%  |
| Seagate ST2000DL003-9VT166 2TB    | 1        | 1      | 16.67%  |
| Maxtor 6E040L0 40GB               | 1        | 1      | 16.67%  |
| IBM/Hitachi IC25N040ATMR04-0 40GB | 1        | 1      | 16.67%  |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart_bsd/drive_malfunc_vendor.svg)


| Vendor      | Desktops | Drives | Percent |
|-------------|----------|--------|---------|
| WDC         | 2        | 2      | 33.33%  |
| SK hynix    | 1        | 1      | 16.67%  |
| Seagate     | 1        | 1      | 16.67%  |
| Maxtor      | 1        | 1      | 16.67%  |
| IBM/Hitachi | 1        | 1      | 16.67%  |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart_bsd/drive_malfunc_hdd_vendor.svg)


| Vendor      | Desktops | Drives | Percent |
|-------------|----------|--------|---------|
| WDC         | 1        | 1      | 25%     |
| Seagate     | 1        | 1      | 25%     |
| Maxtor      | 1        | 1      | 25%     |
| IBM/Hitachi | 1        | 1      | 25%     |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart_bsd/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 4        | 4      | 66.67%  |
| SSD  | 2        | 2      | 33.33%  |

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
| Works    | 21       | 38     | 60%     |
| Detected | 8        | 8      | 22.86%  |
| Malfunc  | 6        | 6      | 17.14%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart_bsd/storage_vendor.svg)


| Vendor                    | Desktops | Percent |
|---------------------------|----------|---------|
| Intel                     | 24       | 42.11%  |
| AMD                       | 15       | 26.32%  |
| Samsung Electronics       | 5        | 8.77%   |
| Silicon Motion            | 3        | 5.26%   |
| SanDisk                   | 3        | 5.26%   |
| Phison Electronics        | 2        | 3.51%   |
| Micron/Crucial Technology | 2        | 3.51%   |
| ULi Electronics           | 1        | 1.75%   |
| Nvidia                    | 1        | 1.75%   |
| ASMedia Technology        | 1        | 1.75%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart_bsd/storage_model.svg)


| Model                                                                          | Desktops | Percent |
|--------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 7        | 10.77%  |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 5        | 7.69%   |
| AMD 400 Series Chipset SATA Controller                                         | 5        | 7.69%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 4        | 6.15%   |
| Silicon Motion SM2263EN/SM2263XT (DRAM-less) NVMe SSD Controllers              | 3        | 4.62%   |
| SanDisk Ultra 3D / WD Blue SN550 NVMe SSD                                      | 3        | 4.62%   |
| Intel product 54d3                                                             | 3        | 4.62%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]   | 3        | 4.62%   |
| AMD FCH SATA Controller D                                                      | 3        | 4.62%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                    | 2        | 3.08%   |
| Micron/Crucial P2 [Nick P2] / P3 / P3 Plus NVMe PCIe SSD (DRAM-less)           | 2        | 3.08%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                     | 2        | 3.08%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 2        | 3.08%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 2        | 3.08%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller  | 2        | 3.08%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                           | 2        | 3.08%   |
| ULi M5229 IDE                                                                  | 1        | 1.54%   |
| Samsung S4LN058A01[SSUBX] AHCI SSD Controller (Apple slot)                     | 1        | 1.54%   |
| Samsung S4LN053X01 AHCI SSD Controller(Apple slot)                             | 1        | 1.54%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 1        | 1.54%   |
| Phison E16 PCIe4 NVMe Controller                                               | 1        | 1.54%   |
| Phison E12 NVMe Controller                                                     | 1        | 1.54%   |
| Nvidia MCP61 SATA Controller                                                   | 1        | 1.54%   |
| Nvidia MCP61 IDE                                                               | 1        | 1.54%   |
| Intel Jasper Lake SATA AHCI Controller                                         | 1        | 1.54%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 1        | 1.54%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                         | 1        | 1.54%   |
| Intel 82801AA IDE Controller                                                   | 1        | 1.54%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                           | 1        | 1.54%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                               | 1        | 1.54%   |
| ASMedia ASM1061 Serial ATA Controller                                          | 1        | 1.54%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart_bsd/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 40       | 67.8%   |
| NVMe | 13       | 22.03%  |
| IDE  | 6        | 10.17%  |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart_bsd/cpu_vendor.svg)


| Vendor          | Desktops | Percent |
|-----------------|----------|---------|
| Intel           | 26       | 53.06%  |
| AMD             | 15       | 30.61%  |
| Unknown         | 3        | 6.12%   |
| Arm             | 2        | 4.08%   |
| 7447A           | 2        | 4.08%   |
| SUNW,UltraAX-i2 | 1        | 2.04%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart_bsd/cpu_model.svg)


| Model                                           | Desktops | Percent |
|-------------------------------------------------|----------|---------|
| Intel 686-class                                 | 13       | 26%     |
|                                                 | 3        | 6%      |
| Intel N100                                      | 2        | 4%      |
| Arm Cortex-A53 r0p4 (v8-A)                      | 2        | 4%      |
| AMD Ryzen 9 3900X 12-Core Processor             | 2        | 4%      |
| AMD 686-class                                   | 2        | 4%      |
| 7447A (Revision 1.2)                            | 2        | 4%      |
| SUNW,UltraAX-i2 (SUNW,UltraSPARC-IIe @ 500 MHz) | 1        | 2%      |
| Intel Xeon CPU E5-2630L v3 @ 1.80GHz            | 1        | 2%      |
| Intel Pentium III                               | 1        | 2%      |
| Intel Core i7-7700 CPU @ 3.60GHz                | 1        | 2%      |
| Intel Core i7-6700K CPU @ 4.00GHz               | 1        | 2%      |
| Intel Core i7-3770 CPU @ 3.40GHz                | 1        | 2%      |
| Intel Core i5-9400T CPU @ 1.80GHz               | 1        | 2%      |
| Intel Core i5-7400 CPU @ 3.00GHz                | 1        | 2%      |
| Intel Core i5-4310M CPU @ 2.70GHz               | 1        | 2%      |
| Intel Core i5-2500K CPU @ 3.30GHz               | 1        | 2%      |
| Intel Core i5-2320 CPU @ 3.00GHz                | 1        | 2%      |
| Intel Core i3-4150 CPU @ 3.50GHz                | 1        | 2%      |
| Intel Celeron CPU N2830 @ 2.16GHz               | 1        | 2%      |
| AMD Sempron 145 Processor                       | 1        | 2%      |
| AMD Ryzen 7 2700 Eight-Core Processor           | 1        | 2%      |
| AMD Ryzen 5 3600 6-Core Processor               | 1        | 2%      |
| AMD Ryzen 5 2600 Six-Core Processor             | 1        | 2%      |
| AMD Ryzen 3 3200G with Radeon Vega Graphics     | 1        | 2%      |
| AMD Ryzen 3 2200G with Radeon Vega Graphics     | 1        | 2%      |
| AMD Ryzen 3 1200 Quad-Core Processor            | 1        | 2%      |
| AMD Phenom II X6 1055T Processor                | 1        | 2%      |
| AMD Phenom II X4 965 Processor                  | 1        | 2%      |
| AMD FX-8350 Eight-Core Processor                | 1        | 2%      |
| AMD E-450 APU with Radeon HD Graphics           | 1        | 2%      |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart_bsd/cpu_family.svg)


| Model             | Desktops | Percent |
|-------------------|----------|---------|
| Intel 686-class   | 13       | 26%     |
| Other             | 10       | 20%     |
| Intel Core i5     | 5        | 10%     |
| Intel Core i7     | 3        | 6%      |
| AMD Ryzen 3       | 3        | 6%      |
| AMD Ryzen 9       | 2        | 4%      |
| AMD Ryzen 5       | 2        | 4%      |
| AMD 686-class     | 2        | 4%      |
| Intel Xeon        | 1        | 2%      |
| Intel Pentium III | 1        | 2%      |
| Intel Core i3     | 1        | 2%      |
| Intel Celeron     | 1        | 2%      |
| AMD Sempron       | 1        | 2%      |
| AMD Ryzen 7       | 1        | 2%      |
| AMD Phenom II X6  | 1        | 2%      |
| AMD Phenom II X4  | 1        | 2%      |
| AMD FX            | 1        | 2%      |
| AMD E             | 1        | 2%      |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart_bsd/cpu_cores.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| Unknown | 29       | 58%     |
| 4       | 11       | 22%     |
| 8       | 3        | 6%      |
| 6       | 3        | 6%      |
| 12      | 2        | 4%      |
| 2       | 2        | 4%      |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart_bsd/cpu_sockets.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 1       | 26       | 52%     |
| Unknown | 24       | 48%     |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart_bsd/cpu_threads.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| Unknown | 29       | 58%     |
| 1       | 11       | 22%     |
| 2       | 10       | 20%     |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart_bsd/cpu_microarch.svg)


| Name        | Desktops | Percent |
|-------------|----------|---------|
| Unknown     | 27       | 54%     |
| Zen+        | 3        | 6%      |
| Zen 2       | 3        | 6%      |
| KabyLake    | 3        | 6%      |
| Zen         | 2        | 4%      |
| SandyBridge | 2        | 4%      |
| K10         | 2        | 4%      |
| Haswell     | 2        | 4%      |
| Skylake     | 1        | 2%      |
| Silvermont  | 1        | 2%      |
| Piledriver  | 1        | 2%      |
| P6          | 1        | 2%      |
| IvyBridge   | 1        | 2%      |
| Bobcat      | 1        | 2%      |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart_bsd/gpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 21       | 43.75%  |
| AMD    | 18       | 37.5%   |
| Nvidia | 9        | 18.75%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart_bsd/gpu_model.svg)


| Model                                                                     | Desktops | Percent |
|---------------------------------------------------------------------------|----------|---------|
| Intel HD Graphics 530                                                     | 3        | 6.12%   |
| Intel Alder Lake-N [UHD Graphics]                                         | 3        | 6.12%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                   | 3        | 6.12%   |
| Nvidia GF114 [GeForce GTX 560]                                            | 2        | 4.08%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller | 2        | 4.08%   |
| AMD RV280 [Radeon 9200]                                                   | 2        | 4.08%   |
| Nvidia NV18 [GeForce4 MX 440 AGP 8x]                                      | 1        | 2.04%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                   | 1        | 2.04%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                        | 1        | 2.04%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                       | 1        | 2.04%   |
| Nvidia GM204 [GeForce GTX 970]                                            | 1        | 2.04%   |
| Nvidia G86 [GeForce 8500 GT]                                              | 1        | 2.04%   |
| Nvidia C61 [GeForce 7025 / nForce 630a]                                   | 1        | 2.04%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller          | 1        | 2.04%   |
| Intel JasperLake [UHD Graphics]                                           | 1        | 2.04%   |
| Intel IvyBridge GT2 [HD Graphics 4000]                                    | 1        | 2.04%   |
| Intel Iris Graphics 6100                                                  | 1        | 2.04%   |
| Intel HD Graphics 630                                                     | 1        | 2.04%   |
| Intel HD Graphics 6000                                                    | 1        | 2.04%   |
| Intel Haswell-ULT Integrated Graphics Controller                          | 1        | 2.04%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                  | 1        | 2.04%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                 | 1        | 2.04%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                 | 1        | 2.04%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display              | 1        | 2.04%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller               | 1        | 2.04%   |
| Intel 3rd Gen Core processor Graphics Controller                          | 1        | 2.04%   |
| AMD Wrestler [Radeon HD 6320]                                             | 1        | 2.04%   |
| AMD Wrestler [Radeon HD 6250]                                             | 1        | 2.04%   |
| AMD Tonga PRO [Radeon R9 285/380]                                         | 1        | 2.04%   |
| AMD Sun LE [Radeon HD 8550M / R5 M230]                                    | 1        | 2.04%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                  | 1        | 2.04%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]          | 1        | 2.04%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]      | 1        | 2.04%   |
| AMD Oland [Radeon HD 8570 / R5 430 OEM / R7 240/340 / Radeon 520 OEM]     | 1        | 2.04%   |
| AMD Oland PRO [Radeon R7 240/340 / Radeon 520]                            | 1        | 2.04%   |
| AMD Lexa PRO [Radeon 540/540X/550/550X / RX 540X/550/550X]                | 1        | 2.04%   |
| AMD Chelsea XT GL [FirePro M4000]                                         | 1        | 2.04%   |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                          | 1        | 2.04%   |
| AMD Caicos [Radeon HD 6450/7450/8450 / R5 230 OEM]                        | 1        | 2.04%   |
| AMD Caicos PRO [Radeon HD 7450]                                           | 1        | 2.04%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart_bsd/gpu_combo.svg)


| Name           | Desktops | Percent |
|----------------|----------|---------|
| 1 x Intel      | 18       | 36.73%  |
| 1 x AMD        | 15       | 30.61%  |
| 1 x Nvidia     | 7        | 14.29%  |
| Other          | 6        | 12.24%  |
| 2 x AMD        | 1        | 2.04%   |
| Intel + Nvidia | 1        | 2.04%   |
| Intel + AMD    | 1        | 2.04%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart_bsd/gpu_driver.svg)


| Driver  | Desktops | Percent |
|---------|----------|---------|
| Free    | 30       | 58.82%  |
| Unknown | 21       | 41.18%  |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart_bsd/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 27       | 54%     |
| 1.01-2.0   | 8        | 16%     |
| 3.01-4.0   | 6        | 12%     |
| 0.01-0.5   | 4        | 8%      |
| 0.51-1.0   | 3        | 6%      |
| 7.01-8.0   | 1        | 2%      |
| 5.01-6.0   | 1        | 2%      |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart_bsd/mon_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Samsung Electronics | 5        | 25%     |
| Goldstar            | 3        | 15%     |
| Eizo                | 2        | 10%     |
| ViewSonic           | 1        | 5%      |
| Unknown (CDD)       | 1        | 5%      |
| NEC Computers       | 1        | 5%      |
| LG Display          | 1        | 5%      |
| Lenovo              | 1        | 5%      |
| Impression          | 1        | 5%      |
| Iiyama              | 1        | 5%      |
| Dell                | 1        | 5%      |
| Apple               | 1        | 5%      |
| Acer                | 1        | 5%      |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart_bsd/mon_model.svg)


| Model                                                                 | Desktops | Percent |
|-----------------------------------------------------------------------|----------|---------|
| Samsung Electronics LCD Monitor SAM0C39 1920x1080 890x500mm 40.2-inch | 2        | 10%     |
| Eizo M170 ENC1768 1280x1024 340x270mm 17.1-inch                       | 2        | 10%     |
| ViewSonic VG2439 Series VSCD22B 1920x1080 520x290mm 23.4-inch         | 1        | 5%      |
| Unknown (CDD) VGA CDD0030 1920x1080 1150x650mm 52.0-inch              | 1        | 5%      |
| Samsung Electronics SyncMaster SAM01AE 1600x1200 410x310mm 20.2-inch  | 1        | 5%      |
| Samsung Electronics SMS27A350H SAM07CE 1920x1080 600x340mm 27.2-inch  | 1        | 5%      |
| Samsung Electronics S23C570 SAM0A56 1920x1080 510x290mm 23.1-inch     | 1        | 5%      |
| NEC Computers P221W NEC674A 1680x1050 470x300mm 22.0-inch             | 1        | 5%      |
| LG Display LCD Monitor LGD045E 1366x768 310x170mm 13.9-inch           | 1        | 5%      |
| Lenovo P27h-20 LEN61E9 2560x1440 600x340mm 27.2-inch                  | 1        | 5%      |
| Impression R19W11 IMP1911 1440x900 410x260mm 19.1-inch                | 1        | 5%      |
| Iiyama PL2792Q IVM6630 2560x1440 600x340mm 27.2-inch                  | 1        | 5%      |
| Goldstar W1952 GSM4B78 1440x900 410x260mm 19.1-inch                   | 1        | 5%      |
| Goldstar LG ULTRAWIDE GSM59F1 2560x1080 580x240mm 24.7-inch           | 1        | 5%      |
| Goldstar L194WT GSM4B05 1440x900 410x260mm 19.1-inch                  | 1        | 5%      |
| Dell P2419H DELD0DA 1920x1080 530x300mm 24.0-inch                     | 1        | 5%      |
| Apple Color LCD APPA029 2560x1600 290x180mm 13.4-inch                 | 1        | 5%      |
| Acer SB220Q ACR06AB 1920x1080 480x270mm 21.7-inch                     | 1        | 5%      |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart_bsd/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 8        | 40%     |
| 1440x900 (WXGA+)   | 3        | 15%     |
| 2560x1440 (QHD)    | 2        | 10%     |
| 1280x1024 (SXGA)   | 2        | 10%     |
| 2560x1600          | 1        | 5%      |
| 2560x1080          | 1        | 5%      |
| 1680x1050 (WSXGA+) | 1        | 5%      |
| 1600x1200          | 1        | 5%      |
| 1366x768 (WXGA)    | 1        | 5%      |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart_bsd/mon_diagonal.svg)


| Inches | Desktops | Percent |
|--------|----------|---------|
| 27     | 3        | 15%     |
| 19     | 3        | 15%     |
| 40     | 2        | 10%     |
| 23     | 2        | 10%     |
| 17     | 2        | 10%     |
| 13     | 2        | 10%     |
| 52     | 1        | 5%      |
| 34     | 1        | 5%      |
| 24     | 1        | 5%      |
| 22     | 1        | 5%      |
| 21     | 1        | 5%      |
| 20     | 1        | 5%      |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart_bsd/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 501-600     | 6        | 30%     |
| 401-500     | 6        | 30%     |
| 301-350     | 3        | 15%     |
| 801-900     | 2        | 10%     |
| 701-800     | 1        | 5%      |
| 201-300     | 1        | 5%      |
| 1001-1500   | 1        | 5%      |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart_bsd/mon_ratio.svg)


| Ratio | Desktops | Percent |
|-------|----------|---------|
| 16/9  | 11       | 55%     |
| 16/10 | 5        | 25%     |
| 5/4   | 2        | 10%     |
| 4/3   | 1        | 5%      |
| 21/9  | 1        | 5%      |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart_bsd/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 5        | 25%     |
| 151-200        | 4        | 20%     |
| 301-350        | 3        | 15%     |
| 81-90          | 2        | 10%     |
| 141-150        | 2        | 10%     |
| 501-1000       | 2        | 10%     |
| More than 1000 | 1        | 5%      |
| 351-500        | 1        | 5%      |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart_bsd/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 14       | 70%     |
| 101-120 | 4        | 20%     |
| 1-50    | 1        | 5%      |
| 161-240 | 1        | 5%      |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart_bsd/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 0     | 25       | 50%     |
| 1     | 24       | 48%     |
| 2     | 1        | 2%      |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart_bsd/net_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Realtek Semiconductor | 26       | 42.62%  |
| Intel                 | 17       | 27.87%  |
| Qualcomm Atheros      | 5        | 8.2%    |
| Broadcom              | 5        | 8.2%    |
| Huawei Technologies   | 2        | 3.28%   |
| Oculus VR             | 1        | 1.64%   |
| Netchip Technology    | 1        | 1.64%   |
| Mercucys              | 1        | 1.64%   |
| Davicom Semiconductor | 1        | 1.64%   |
| Apple                 | 1        | 1.64%   |
| 3Com                  | 1        | 1.64%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart_bsd/net_model.svg)


| Model                                                                  | Desktops | Percent |
|------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 24       | 32%     |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]                | 3        | 4%      |
| Intel I211 Gigabit Network Connection                                  | 3        | 4%      |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 3        | 4%      |
| Intel Ethernet Controller I225-V                                       | 2        | 2.67%   |
| Intel Ethernet Connection (2) I219-LM                                  | 2        | 2.67%   |
| Intel CNVi: Wi-Fi                                                      | 2        | 2.67%   |
| Intel Cannon Lake PCH CNVi WiFi                                        | 2        | 2.67%   |
| Huawei USB Device                                                      | 2        | 2.67%   |
| Broadcom BCM4360 802.11ac Dual Band Wireless Network Adapter           | 2        | 2.67%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter               | 1        | 1.33%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                        | 1        | 1.33%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                                 | 1        | 1.33%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                    | 1        | 1.33%   |
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller      | 1        | 1.33%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                  | 1        | 1.33%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter             | 1        | 1.33%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller              | 1        | 1.33%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                       | 1        | 1.33%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)         | 1        | 1.33%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                          | 1        | 1.33%   |
| Oculus VR Rift S                                                       | 1        | 1.33%   |
| Netchip Linux-USB Serial Gadget (CDC ACM mode)                         | 1        | 1.33%   |
| Mercucys MERCUSYS Wireless USB Adapter                                 | 1        | 1.33%   |
| Intel Wireless 8265 / 8275                                             | 1        | 1.33%   |
| Intel Wi-Fi 6 AX201 160MHz                                             | 1        | 1.33%   |
| Intel Wi-Fi 6 AX200                                                    | 1        | 1.33%   |
| Intel Ethernet Connection I217-V                                       | 1        | 1.33%   |
| Intel Ethernet Connection (2) I219-V                                   | 1        | 1.33%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                       | 1        | 1.33%   |
| Intel Centrino Ultimate-N 6300                                         | 1        | 1.33%   |
| Intel 82574L Gigabit Network Connection                                | 1        | 1.33%   |
| Davicom DM9102 Fast Ethernet Controller                                | 1        | 1.33%   |
| Broadcom NetXtreme BCM57766 Gigabit Ethernet PCIe                      | 1        | 1.33%   |
| Broadcom NetXtreme BCM57762 Gigabit Ethernet PCIe                      | 1        | 1.33%   |
| Broadcom NetXtreme BCM5720 Gigabit Ethernet PCIe                       | 1        | 1.33%   |
| Broadcom BCM43602 802.11ac Wireless LAN SoC                            | 1        | 1.33%   |
| Broadcom BCM4331 802.11a/b/g/n                                         | 1        | 1.33%   |
| Apple Ethernet Adapter [A1277]                                         | 1        | 1.33%   |
| 3Com 3c905C-TX/TX-M [Tornado]                                          | 1        | 1.33%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart_bsd/net_wireless_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Intel                 | 11       | 47.83%  |
| Realtek Semiconductor | 4        | 17.39%  |
| Broadcom              | 4        | 17.39%  |
| Qualcomm Atheros      | 3        | 13.04%  |
| Mercucys              | 1        | 4.35%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart_bsd/net_wireless_model.svg)


| Model                                                          | Desktops | Percent |
|----------------------------------------------------------------|----------|---------|
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]        | 3        | 13.04%  |
| Intel CNVi: Wi-Fi                                              | 2        | 8.7%    |
| Intel Cannon Lake PCH CNVi WiFi                                | 2        | 8.7%    |
| Broadcom BCM4360 802.11ac Dual Band Wireless Network Adapter   | 2        | 8.7%    |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter       | 1        | 4.35%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                | 1        | 4.35%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                         | 1        | 4.35%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter            | 1        | 4.35%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 1        | 4.35%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 1        | 4.35%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 1        | 4.35%   |
| Mercucys MERCUSYS Wireless USB Adapter                         | 1        | 4.35%   |
| Intel Wireless 8265 / 8275                                     | 1        | 4.35%   |
| Intel Wi-Fi 6 AX201 160MHz                                     | 1        | 4.35%   |
| Intel Wi-Fi 6 AX200                                            | 1        | 4.35%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]               | 1        | 4.35%   |
| Broadcom BCM43602 802.11ac Wireless LAN SoC                    | 1        | 4.35%   |
| Broadcom BCM4331 802.11a/b/g/n                                 | 1        | 4.35%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart_bsd/net_ethernet_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Realtek Semiconductor | 26       | 54.17%  |
| Intel                 | 12       | 25%     |
| Broadcom              | 3        | 6.25%   |
| Qualcomm Atheros      | 2        | 4.17%   |
| Huawei Technologies   | 2        | 4.17%   |
| Davicom Semiconductor | 1        | 2.08%   |
| Apple                 | 1        | 2.08%   |
| 3Com                  | 1        | 2.08%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart_bsd/net_ethernet_model.svg)


| Model                                                                  | Desktops | Percent |
|------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 24       | 48.98%  |
| Intel I211 Gigabit Network Connection                                  | 3        | 6.12%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 3        | 6.12%   |
| Intel Ethernet Controller I225-V                                       | 2        | 4.08%   |
| Intel Ethernet Connection (2) I219-LM                                  | 2        | 4.08%   |
| Huawei USB Device                                                      | 2        | 4.08%   |
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller      | 1        | 2.04%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                  | 1        | 2.04%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller              | 1        | 2.04%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                          | 1        | 2.04%   |
| Intel Ethernet Connection I217-V                                       | 1        | 2.04%   |
| Intel Ethernet Connection (2) I219-V                                   | 1        | 2.04%   |
| Intel 82574L Gigabit Network Connection                                | 1        | 2.04%   |
| Davicom DM9102 Fast Ethernet Controller                                | 1        | 2.04%   |
| Broadcom NetXtreme BCM57766 Gigabit Ethernet PCIe                      | 1        | 2.04%   |
| Broadcom NetXtreme BCM57762 Gigabit Ethernet PCIe                      | 1        | 2.04%   |
| Broadcom NetXtreme BCM5720 Gigabit Ethernet PCIe                       | 1        | 2.04%   |
| Apple Ethernet Adapter [A1277]                                         | 1        | 2.04%   |
| 3Com 3c905C-TX/TX-M [Tornado]                                          | 1        | 2.04%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart_bsd/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 43       | 63.24%  |
| WiFi     | 22       | 32.35%  |
| Modem    | 2        | 2.94%   |
| Unknown  | 1        | 1.47%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart_bsd/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 35       | 92.11%  |
| WiFi     | 3        | 7.89%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart_bsd/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 21       | 42.86%  |
| 2     | 14       | 28.57%  |
| 0     | 8        | 16.33%  |
| 3     | 5        | 10.2%   |
| 4     | 1        | 2.04%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart_bsd/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 42       | 84%     |
| Yes  | 8        | 16%     |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart_bsd/bt_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Intel                 | 9        | 56.25%  |
| Apple                 | 4        | 25%     |
| Realtek Semiconductor | 2        | 12.5%   |
| Lite-On Technology    | 1        | 6.25%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart_bsd/bt_model.svg)


| Model                                          | Desktops | Percent |
|------------------------------------------------|----------|---------|
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP) | 3        | 18.75%  |
| Intel Wireless-AC 9260 Bluetooth Adapter       | 2        | 12.5%   |
| Intel AX201 Bluetooth                          | 2        | 12.5%   |
| Apple Broadcom Built-in Bluetooth              | 2        | 12.5%   |
| Apple Bluetooth Host Controller                | 2        | 12.5%   |
| Realtek Bluetooth Adapter                      | 1        | 6.25%   |
| Realtek Bluetooth 4.0 Adapter                  | 1        | 6.25%   |
| Lite-On Atheros AR3012 Bluetooth               | 1        | 6.25%   |
| Intel Wireless-AC 3168 Bluetooth               | 1        | 6.25%   |
| Intel Bluetooth wireless interface             | 1        | 6.25%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart_bsd/snd_vendor.svg)


| Vendor                                       | Desktops | Percent |
|----------------------------------------------|----------|---------|
| Intel                                        | 26       | 44.07%  |
| AMD                                          | 18       | 30.51%  |
| Nvidia                                       | 6        | 10.17%  |
| Zoran Co. Personal Media Division (Nogatech) | 2        | 3.39%   |
| Logitech                                     | 2        | 3.39%   |
| Yamaha                                       | 1        | 1.69%   |
| Samsung Electronics                          | 1        | 1.69%   |
| Native Instruments                           | 1        | 1.69%   |
| ESS Technology                               | 1        | 1.69%   |
| Creative Labs                                | 1        | 1.69%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart_bsd/snd_model.svg)


| Model                                                                                           | Desktops | Percent |
|-------------------------------------------------------------------------------------------------|----------|---------|
| AMD SBx00 Azalia (Intel HDA)                                                                    | 5        | 6.58%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                             | 4        | 5.26%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                 | 4        | 5.26%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                                             | 4        | 5.26%   |
| Intel Cannon Lake PCH cAVS                                                                      | 3        | 3.95%   |
| Intel Alder Lake-N PCH High Definition Audio Controller                                         | 3        | 3.95%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                             | 3        | 3.95%   |
| AMD Starship/Matisse HD Audio Controller                                                        | 3        | 3.95%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]                         | 3        | 3.95%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                                      | 3        | 3.95%   |
| Zoran Co. Personal Media Division (Nogatech) USB Audio and HID                                  | 2        | 2.63%   |
| Nvidia GP107GL High Definition Audio Controller                                                 | 2        | 2.63%   |
| Nvidia GF114 HDMI Audio Controller                                                              | 2        | 2.63%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                         | 2        | 2.63%   |
| Intel Broadwell-U Audio Controller                                                              | 2        | 2.63%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                      | 2        | 2.63%   |
| AMD Wrestler HDMI Audio                                                                         | 2        | 2.63%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                             | 2        | 2.63%   |
| AMD Family 17h/19h HD Audio Controller                                                          | 2        | 2.63%   |
| AMD Caicos HDMI Audio [Radeon HD 6450 / 7450/8450/8490 OEM / R5 230/235/235X OEM]               | 2        | 2.63%   |
| Yamaha AG06/AG03                                                                                | 1        | 1.32%   |
| Samsung Electronics Samsung Type-C to 3.5pi gender adapter                                      | 1        | 1.32%   |
| Nvidia GP106 High Definition Audio Controller                                                   | 1        | 1.32%   |
| Nvidia GM204 High Definition Audio Controller                                                   | 1        | 1.32%   |
| Native Instruments Komplete Audio 1                                                             | 1        | 1.32%   |
| Logitech Zone Wired Earbuds                                                                     | 1        | 1.32%   |
| Logitech H600 [Wireless Headset]                                                                | 1        | 1.32%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                | 1        | 1.32%   |
| Intel Jasper Lake HD Audio                                                                      | 1        | 1.32%   |
| Intel Haswell-ULT HD Audio Controller                                                           | 1        | 1.32%   |
| Intel Comet Lake PCH-V cAVS                                                                     | 1        | 1.32%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                      | 1        | 1.32%   |
| Intel 82801AA AC'97 Audio Controller                                                            | 1        | 1.32%   |
| Intel 8 Series HD Audio Controller                                                              | 1        | 1.32%   |
| ESS Technology ESS USB DAC                                                                      | 1        | 1.32%   |
| Creative Labs CA0132 Sound Core3D [Sound Blaster Recon3D / Z-Series / Sound BlasterX AE-5 Plus] | 1        | 1.32%   |
| AMD Tonga HDMI Audio [Radeon R9 285/380]                                                        | 1        | 1.32%   |
| AMD High Definition Audio Controller                                                            | 1        | 1.32%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                | 1        | 1.32%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                                          | 1        | 1.32%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart_bsd/memory_vendor.svg)


| Vendor            | Desktops | Percent |
|-------------------|----------|---------|
| Crucial           | 9        | 32.14%  |
| Kingston          | 6        | 21.43%  |
| Unknown           | 3        | 10.71%  |
| G.Skill           | 3        | 10.71%  |
| Patriot           | 2        | 7.14%   |
| Micron Technology | 2        | 7.14%   |
| Corsair           | 2        | 7.14%   |
| A-DATA Technology | 1        | 3.57%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart_bsd/memory_model.svg)


| Model                                                    | Desktops | Percent |
|----------------------------------------------------------|----------|---------|
| Crucial RAM CT16G4SFS832A.C8FF 16GB SODIMM DDR4 3200MT/s | 2        | 6.06%   |
| Unknown RAM Module 8192MB DIMM 400MT/s                   | 1        | 3.03%   |
| Unknown RAM Module 2048MB DIMM DDR2 800MT/s              | 1        | 3.03%   |
| Unknown RAM Module 2048MB DIMM 400MT/s                   | 1        | 3.03%   |
| Unknown RAM Module 128MB DIMM DRAM                       | 1        | 3.03%   |
| Patriot RAM PSD44G213382 4096MB DIMM DDR4 2133MT/s       | 1        | 3.03%   |
| Patriot RAM PSD34G13332 4GB DIMM DDR3 1333MT/s           | 1        | 3.03%   |
| Micron RAM 36ASF2G72PZ-2G1A2 16GB DIMM DDR4 2133MT/s     | 1        | 3.03%   |
| Micron RAM 16JTF1G64AZ-1G6J1 8GB DIMM DDR3 1333MT/s      | 1        | 3.03%   |
| Kingston RAM KHX2400C15/8G 8GB DIMM DDR4 2400MT/s        | 1        | 3.03%   |
| Kingston RAM KHX1600C9D3/4GX 4GB DIMM DDR3 1600MT/s      | 1        | 3.03%   |
| Kingston RAM ACR26D4S9S8ME-8 8GB SODIMM DDR4 2667MT/s    | 1        | 3.03%   |
| Kingston RAM ACR16D3LS1KFG/4G 4GB DIMM DDR3 1600MT/s     | 1        | 3.03%   |
| Kingston RAM 99U5701-077.A00G 16GB DIMM DDR4 2667MT/s    | 1        | 3.03%   |
| Kingston RAM 99U5471-028.A00LF 4GB DIMM DDR3 667MT/s     | 1        | 3.03%   |
| Kingston RAM 9905471-011.A00LF 4GB DIMM DDR3 1333MT/s    | 1        | 3.03%   |
| G.Skill RAM F4-3200C16-16GVK 16GB DIMM DDR4 3200MT/s     | 1        | 3.03%   |
| G.Skill RAM F4-2800C17-8GVR 8192MB DIMM DDR4 2133MT/s    | 1        | 3.03%   |
| G.Skill RAM F3-1600C11-8G 8GB DIMM DDR3 1600MT/s         | 1        | 3.03%   |
| Crucial RAM CT8G4DFS8266.M8FD 8GB DIMM DDR4 2667MT/s     | 1        | 3.03%   |
| Crucial RAM CT8G4DFS824A.M8FE 8GB DIMM DDR4 2933MT/s     | 1        | 3.03%   |
| Crucial RAM CT8G4DFS8213.C8FDR1 8GB DIMM DDR4 2133MT/s   | 1        | 3.03%   |
| Crucial RAM CT8G4DFS8213.C8FBD1 8GB DIMM DDR4 2133MT/s   | 1        | 3.03%   |
| Crucial RAM CT51264BA160B.C16F 4GB DIMM DDR3 1600MT/s    | 1        | 3.03%   |
| Crucial RAM CT102464BA160B.C16 8GB DIMM DDR3 1600MT/s    | 1        | 3.03%   |
| Crucial RAM BLS4G4D240FSE.8FBD 4GB DIMM DDR4 2400MT/s    | 1        | 3.03%   |
| Crucial RAM BLS4G4D240FSB.8FBD2 4GB DIMM DDR4 2400MT/s   | 1        | 3.03%   |
| Crucial RAM BLS4G4D240FSB.8FBD 4GB DIMM DDR4 2400MT/s    | 1        | 3.03%   |
| Corsair RAM CMV8GX3M1A160 8GB DIMM DDR3 800MT/s          | 1        | 3.03%   |
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3200MT/s    | 1        | 3.03%   |
| Corsair RAM CMK16GX4M2B3000C15 8GB DIMM DDR4 3000MT/s    | 1        | 3.03%   |
| A-DATA RAM Module 8GB DIMM DDR4 2666MT/s                 | 1        | 3.03%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart_bsd/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR4    | 16       | 59.26%  |
| DDR3    | 8        | 29.63%  |
| DRAM    | 1        | 3.7%    |
| DDR2    | 1        | 3.7%    |
| Unknown | 1        | 3.7%    |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart_bsd/memory_formfactor.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| DIMM   | 24       | 88.89%  |
| SODIMM | 3        | 11.11%  |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart_bsd/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 8192  | 12       | 42.86%  |
| 4096  | 8        | 28.57%  |
| 16384 | 5        | 17.86%  |
| 2048  | 2        | 7.14%   |
| 128   | 1        | 3.57%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart_bsd/memory_speed.svg)


| Speed   | Desktops | Percent |
|---------|----------|---------|
| 1600    | 5        | 16.67%  |
| 3200    | 4        | 13.33%  |
| 2133    | 4        | 13.33%  |
| 2667    | 3        | 10%     |
| 2400    | 3        | 10%     |
| 1333    | 3        | 10%     |
| 800     | 2        | 6.67%   |
| 3000    | 1        | 3.33%   |
| 2933    | 1        | 3.33%   |
| 2666    | 1        | 3.33%   |
| 667     | 1        | 3.33%   |
| 400     | 1        | 3.33%   |
| Unknown | 1        | 3.33%   |

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


| Vendor                           | Desktops | Percent |
|----------------------------------|----------|---------|
| Chicony Electronics              | 2        | 33.33%  |
| Silicon Motion                   | 1        | 16.67%  |
| Shenzhen Kingcome Optoelectronic | 1        | 16.67%  |
| Logitech                         | 1        | 16.67%  |
| ARC International                | 1        | 16.67%  |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart_bsd/camera_model.svg)


| Model                                                         | Desktops | Percent |
|---------------------------------------------------------------|----------|---------|
| Silicon Motion 300k Pixel Camera                              | 1        | 16.67%  |
| Shenzhen Kingcome Optoelectronic NexiGo HelloCam N930W Camera | 1        | 16.67%  |
| Logitech Webcam C270                                          | 1        | 16.67%  |
| Chicony USB2.0 VGA UVC WebCam                                 | 1        | 16.67%  |
| Chicony HP HD Webcam [Fixed]                                  | 1        | 16.67%  |
| ARC International Camera                                      | 1        | 16.67%  |

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
| 0     | 21       | 42%     |
| 1     | 13       | 26%     |
| 2     | 9        | 18%     |
| 3     | 6        | 12%     |
| 5     | 1        | 2%      |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart_bsd/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Communication controller | 24       | 48.98%  |
| Net/wireless             | 17       | 34.69%  |
| Net/ethernet             | 2        | 4.08%   |
| Card reader              | 2        | 4.08%   |
| Wireless                 | 1        | 2.04%   |
| Storage                  | 1        | 2.04%   |
| Graphics card            | 1        | 2.04%   |
| Bluetooth                | 1        | 2.04%   |

