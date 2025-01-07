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

Total: 86

| Vendor   | Model                    | Probe                                                     | Date         |
|----------|--------------------------|-----------------------------------------------------------|--------------|
| ASUSTek  | TUF B360M-PLUS GAMING/BR | [ed6505a58e](https://bsd-hardware.info/?probe=ed6505a58e) | Jul 19, 2024 |
| ASUSTek  | TUF B360M-PLUS GAMING/BR | [b1de030d31](https://bsd-hardware.info/?probe=b1de030d31) | Jul 19, 2024 |
| Unknown  | Unknown                  | [ae3e63c3e6](https://bsd-hardware.info/?probe=ae3e63c3e6) | Jun 25, 2024 |
| HP       | 8594                     | [39702449a8](https://bsd-hardware.info/?probe=39702449a8) | May 20, 2024 |
| GEEKOM   | Mini IT13                | [18e5e61859](https://bsd-hardware.info/?probe=18e5e61859) | May 18, 2024 |
| HP       | 8594                     | [209ddea7e7](https://bsd-hardware.info/?probe=209ddea7e7) | May 17, 2024 |
| Unknown  | Unknown                  | [c70960854a](https://bsd-hardware.info/?probe=c70960854a) | May 06, 2024 |
| Lenovo   | 3743 NOK                 | [4b8389c575](https://bsd-hardware.info/?probe=4b8389c575) | Apr 27, 2024 |
| ASRock   | 970 Pro3 R2.0            | [47b751dfa0](https://bsd-hardware.info/?probe=47b751dfa0) | Apr 20, 2024 |
| Gigabyte | B360M D2V                | [766a437527](https://bsd-hardware.info/?probe=766a437527) | Apr 07, 2024 |
| Gigabyte | X570 I AORUS PRO WIFI    | [3208fef860](https://bsd-hardware.info/?probe=3208fef860) | Apr 04, 2024 |
| Google   | Monroe                   | [7c9648d197](https://bsd-hardware.info/?probe=7c9648d197) | Apr 04, 2024 |
| Google   | Monroe                   | [383d7ee0f2](https://bsd-hardware.info/?probe=383d7ee0f2) | Apr 04, 2024 |
| Gigabyte | X570 I AORUS PRO WIFI    | [767ef499db](https://bsd-hardware.info/?probe=767ef499db) | Apr 03, 2024 |
| Unknown  | Unknown                  | [3bcc4b4df3](https://bsd-hardware.info/?probe=3bcc4b4df3) | Mar 31, 2024 |
| Gigabyte | GA-990FX-GAMING          | [13c1963782](https://bsd-hardware.info/?probe=13c1963782) | Mar 01, 2024 |
| MSI      | KA790GX                  | [7b431178e5](https://bsd-hardware.info/?probe=7b431178e5) | Feb 25, 2024 |
| Unknown  | Unknown                  | [d3ed7d1552](https://bsd-hardware.info/?probe=d3ed7d1552) | Feb 24, 2024 |
| Dell     | 096JG8 A01               | [5a03257c9a](https://bsd-hardware.info/?probe=5a03257c9a) | Feb 19, 2024 |
| ASUSTek  | TUF B450-PRO GAMING      | [d318950ac5](https://bsd-hardware.info/?probe=d318950ac5) | Jan 15, 2024 |
| Unknown  | Unknown                  | [5deb235717](https://bsd-hardware.info/?probe=5deb235717) | Jan 05, 2024 |
| Unknown  | Unknown                  | [d4bedea996](https://bsd-hardware.info/?probe=d4bedea996) | Dec 30, 2023 |
| Unknown  | Unknown                  | [19daaf5eee](https://bsd-hardware.info/?probe=19daaf5eee) | Dec 30, 2023 |
| Lenovo   | NO DPK                   | [424c33d278](https://bsd-hardware.info/?probe=424c33d278) | Oct 27, 2023 |
| Unknown  | Unknown                  | [a88541d6a6](https://bsd-hardware.info/?probe=a88541d6a6) | Oct 27, 2023 |
| Lenovo   | NO DPK                   | [753b30d88b](https://bsd-hardware.info/?probe=753b30d88b) | Oct 27, 2023 |
| ASRock   | H270 Pro4                | [cba80ecde3](https://bsd-hardware.info/?probe=cba80ecde3) | Sep 24, 2023 |
| Unknown  | Unknown                  | [dcf1ebd901](https://bsd-hardware.info/?probe=dcf1ebd901) | Sep 20, 2023 |
| Unknown  | Unknown                  | [9c1891cda7](https://bsd-hardware.info/?probe=9c1891cda7) | Sep 03, 2023 |
| Gigabyte | A320M-H-CF               | [d1a2b99edc](https://bsd-hardware.info/?probe=d1a2b99edc) | Jul 28, 2023 |
| Acer     | Revo RN86                | [2e52c2b9b2](https://bsd-hardware.info/?probe=2e52c2b9b2) | May 13, 2023 |
| Unknown  | Unknown                  | [d6f92a5ecc](https://bsd-hardware.info/?probe=d6f92a5ecc) | Apr 28, 2023 |
| Gigabyte | B360M D2V                | [f73cb94828](https://bsd-hardware.info/?probe=f73cb94828) | Apr 17, 2023 |
| Unknown  | Unknown                  | [8c93a7e552](https://bsd-hardware.info/?probe=8c93a7e552) | Mar 04, 2023 |
| Unknown  | Unknown                  | [85fdc49ec4](https://bsd-hardware.info/?probe=85fdc49ec4) | Mar 03, 2023 |
| Unknown  | Unknown                  | [8ae1891a85](https://bsd-hardware.info/?probe=8ae1891a85) | Feb 16, 2023 |
| Intel    | DN2820FYK H24582-203     | [ae05d4c6cd](https://bsd-hardware.info/?probe=ae05d4c6cd) | Feb 06, 2023 |
| Acer     | Revo RN86                | [a4dcb7f7a2](https://bsd-hardware.info/?probe=a4dcb7f7a2) | Nov 27, 2022 |
| Unknown  | Unknown                  | [1d3bd58d18](https://bsd-hardware.info/?probe=1d3bd58d18) | Nov 25, 2022 |
| Unknown  | Unknown                  | [410283dd4f](https://bsd-hardware.info/?probe=410283dd4f) | Oct 22, 2022 |
| Unknown  | Unknown                  | [5e2f93a960](https://bsd-hardware.info/?probe=5e2f93a960) | Aug 06, 2022 |
| Unknown  | Unknown                  | [66fefba790](https://bsd-hardware.info/?probe=66fefba790) | Aug 06, 2022 |
| ASUSTek  | TUF B450-PLUS GAMING     | [aeee3a91e6](https://bsd-hardware.info/?probe=aeee3a91e6) | Jul 03, 2022 |
| Gigabyte | X570 AORUS PRO           | [4e7d57df3b](https://bsd-hardware.info/?probe=4e7d57df3b) | Apr 18, 2022 |
| Gigabyte | 970A-D3P                 | [fa03bdabb6](https://bsd-hardware.info/?probe=fa03bdabb6) | Mar 15, 2022 |
| KLLISRE  | X99-B5 V1.0              | [5dea1304b9](https://bsd-hardware.info/?probe=5dea1304b9) | Feb 26, 2022 |
| ASRock   | X470 Gaming-ITX/ac       | [18eeaf2963](https://bsd-hardware.info/?probe=18eeaf2963) | Dec 29, 2021 |
| Acer     | Revo RN86                | [6d184a1e62](https://bsd-hardware.info/?probe=6d184a1e62) | Dec 23, 2021 |
| ASRock   | 970 Extreme3             | [14907c62f1](https://bsd-hardware.info/?probe=14907c62f1) | Dec 04, 2021 |
| HP       | 3397                     | [155eceb394](https://bsd-hardware.info/?probe=155eceb394) | Nov 07, 2021 |
| ASUSTek  | ROG STRIX X470-F GAMING  | [7259ec87e9](https://bsd-hardware.info/?probe=7259ec87e9) | Oct 05, 2021 |
| ASUSTek  | PRIME A320M-K            | [c574dcc409](https://bsd-hardware.info/?probe=c574dcc409) | Oct 01, 2021 |
| ASUSTek  | ROG STRIX X470-F GAMING  | [b3a18fcab3](https://bsd-hardware.info/?probe=b3a18fcab3) | Sep 29, 2021 |
| Unknown  | Unknown                  | [2a56bcb7c1](https://bsd-hardware.info/?probe=2a56bcb7c1) | Sep 19, 2021 |
| MSI      | B450-A PRO MAX           | [4e3b1f226b](https://bsd-hardware.info/?probe=4e3b1f226b) | Jun 22, 2021 |
| Unknown  | Unknown                  | [f9fa9ae41a](https://bsd-hardware.info/?probe=f9fa9ae41a) | May 24, 2021 |
| Acer     | Revo RN86                | [ec302a221a](https://bsd-hardware.info/?probe=ec302a221a) | May 15, 2021 |
| Unknown  | Unknown                  | [364a778de1](https://bsd-hardware.info/?probe=364a778de1) | May 14, 2021 |
| ASRock   | X470 Gaming-ITX/ac       | [82e63b3fb9](https://bsd-hardware.info/?probe=82e63b3fb9) | Apr 14, 2021 |
| Unknown  | Unknown                  | [df793cf09f](https://bsd-hardware.info/?probe=df793cf09f) | Apr 08, 2021 |
| Unknown  | Unknown                  | [f8ba0ba112](https://bsd-hardware.info/?probe=f8ba0ba112) | Apr 08, 2021 |
| Unknown  | Unknown                  | [0541b120c2](https://bsd-hardware.info/?probe=0541b120c2) | Apr 02, 2021 |
| Unknown  | Unknown                  | [91dd02d436](https://bsd-hardware.info/?probe=91dd02d436) | Mar 30, 2021 |
| Unknown  | Unknown                  | [a1220fba93](https://bsd-hardware.info/?probe=a1220fba93) | Mar 24, 2021 |
| Unknown  | Unknown                  | [edea2d1a64](https://bsd-hardware.info/?probe=edea2d1a64) | Mar 18, 2021 |
| Unknown  | Unknown                  | [1afd7d4381](https://bsd-hardware.info/?probe=1afd7d4381) | Feb 27, 2021 |
| Unknown  | Unknown                  | [4c0171bc04](https://bsd-hardware.info/?probe=4c0171bc04) | Feb 25, 2021 |
| Unknown  | Unknown                  | [a5fa760573](https://bsd-hardware.info/?probe=a5fa760573) | Jan 02, 2021 |
| ASRock   | N68-VS3 UCC              | [647ab5967e](https://bsd-hardware.info/?probe=647ab5967e) | Dec 22, 2020 |
| Unknown  | Unknown                  | [8668b1d651](https://bsd-hardware.info/?probe=8668b1d651) | Dec 17, 2020 |
| ASUSTek  | E45M1-I DELUXE           | [8e767b517d](https://bsd-hardware.info/?probe=8e767b517d) | Dec 16, 2020 |
| Unknown  | Unknown                  | [153be3caa3](https://bsd-hardware.info/?probe=153be3caa3) | Nov 28, 2020 |
| HP       | System Board R3A         | [80593fc3da](https://bsd-hardware.info/?probe=80593fc3da) | Nov 03, 2020 |
| Gigabyte | Z170X-Gaming 3           | [615ac68e50](https://bsd-hardware.info/?probe=615ac68e50) | Oct 29, 2020 |
| Unknown  | Unknown                  | [d08d610bd0](https://bsd-hardware.info/?probe=d08d610bd0) | Oct 29, 2020 |
| ASUSTek  | B150M-K                  | [135db0e455](https://bsd-hardware.info/?probe=135db0e455) | Oct 22, 2020 |
| Unknown  | Unknown                  | [223aa9e0a3](https://bsd-hardware.info/?probe=223aa9e0a3) | Oct 22, 2020 |
| Gigabyte | P75-D3                   | [980218cf46](https://bsd-hardware.info/?probe=980218cf46) | Oct 02, 2020 |
| ASUSTek  | H81M-D PLUS              | [95b75130f4](https://bsd-hardware.info/?probe=95b75130f4) | Sep 26, 2020 |
| Acer     | Revo RN86                | [c6b2c64d14](https://bsd-hardware.info/?probe=c6b2c64d14) | Sep 20, 2020 |
| ASUSTek  | H81M-D PLUS              | [7be45f1bec](https://bsd-hardware.info/?probe=7be45f1bec) | Sep 19, 2020 |
| MSI      | KA790GX                  | [bba5499a4b](https://bsd-hardware.info/?probe=bba5499a4b) | Aug 29, 2020 |
| ASUSTek  | PRIME A320M-K            | [a49cf5c20b](https://bsd-hardware.info/?probe=a49cf5c20b) | May 28, 2020 |
| Gigabyte | H61M-S2PV                | [14e00aa09f](https://bsd-hardware.info/?probe=14e00aa09f) | May 25, 2020 |
| Intel    | DN2820FYK H24582-203     | [6cb240a9f6](https://bsd-hardware.info/?probe=6cb240a9f6) | May 25, 2020 |
| Unknown  | Unknown                  | [d3ad2b17ed](https://bsd-hardware.info/?probe=d3ad2b17ed) | May 22, 2020 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart_bsd/os_name.svg)


| Name              | Desktops | Percent |
|-------------------|----------|---------|
| NetBSD 10.0       | 11       | 15.71%  |
| NetBSD 9.3        | 9        | 12.86%  |
| NetBSD 9.2        | 8        | 11.43%  |
| NetBSD 9.1        | 7        | 10%     |
| NetBSD 9.0_STABLE | 5        | 7.14%   |
| NetBSD 9.1_STABLE | 3        | 4.29%   |
| NetBSD 10.0_BETA  | 3        | 4.29%   |
| NetBSD 9.99.94    | 2        | 2.86%   |
| NetBSD 9.99.93    | 2        | 2.86%   |
| NetBSD 9.99.77    | 2        | 2.86%   |
| NetBSD 9.3_STABLE | 2        | 2.86%   |
| NetBSD 9.0        | 2        | 2.86%   |
| NetBSD 10.0_RC4   | 2        | 2.86%   |
| NetBSD 10.0_RC2   | 2        | 2.86%   |
| NetBSD 9.99.85    | 1        | 1.43%   |
| NetBSD 9.99.81    | 1        | 1.43%   |
| NetBSD 9.99.74    | 1        | 1.43%   |
| NetBSD 9.99.71    | 1        | 1.43%   |
| NetBSD 9.99.61    | 1        | 1.43%   |
| NetBSD 9.99.23    | 1        | 1.43%   |
| NetBSD 9.99.107   | 1        | 1.43%   |
| NetBSD 9.2_STABLE | 1        | 1.43%   |
| NetBSD 10.0_RC5   | 1        | 1.43%   |
| NetBSD 10.0_RC1   | 1        | 1.43%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart_bsd/os_family.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| NetBSD | 60       | 100%    |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart_bsd/os_arch.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| amd64   | 49       | 81.67%  |
| evbarm  | 6        | 10%     |
| macppc  | 2        | 3.33%   |
| i386    | 2        | 3.33%   |
| sparc64 | 1        | 1.67%   |

DE
--

Desktop Environment

![DE](./images/pie_chart_bsd/os_de.svg)


| Name         | Desktops | Percent |
|--------------|----------|---------|
| Console      | 25       | 40.98%  |
| XFCE         | 13       | 21.31%  |
| helloDesktop | 8        | 13.11%  |
| Fluxbox      | 3        | 4.92%   |
| MATE         | 2        | 3.28%   |
| CTWM         | 2        | 3.28%   |
| Xfwm4        | 1        | 1.64%   |
| Window Maker | 1        | 1.64%   |
| spectrwm     | 1        | 1.64%   |
| Ratpoison    | 1        | 1.64%   |
| PekWM        | 1        | 1.64%   |
| JWM          | 1        | 1.64%   |
| GNOME        | 1        | 1.64%   |
| DWM          | 1        | 1.64%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart_bsd/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| X11     | 44       | 73.33%  |
| Console | 16       | 26.67%  |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart_bsd/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Console | 54       | 90%     |
| XDM     | 2        | 3.33%   |
| SLiM    | 2        | 3.33%   |
| LightDM | 1        | 1.67%   |
| GDM     | 1        | 1.67%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart_bsd/os_lang.svg)


| Lang    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 48       | 73.85%  |
| en_US   | 8        | 12.31%  |
| ru_RU   | 2        | 3.08%   |
| fi_FI   | 2        | 3.08%   |
| C       | 2        | 3.08%   |
| hu_HU   | 1        | 1.54%   |
| fr_FR   | 1        | 1.54%   |
| en_GB   | 1        | 1.54%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart_bsd/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| BIOS | 56       | 93.33%  |
| EFI  | 4        | 6.67%   |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart_bsd/os_filesystem.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Ufs     | 59       | 98.33%  |
| Unknown | 1        | 1.67%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart_bsd/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| GPT     | 43       | 71.67%  |
| Unknown | 17       | 28.33%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart_bsd/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| Unknown             | 26       | 43.33%  |
| Gigabyte Technology | 9        | 15%     |
| ASUSTek Computer    | 8        | 13.33%  |
| ASRock              | 5        | 8.33%   |
| MSI                 | 2        | 3.33%   |
| Lenovo              | 2        | 3.33%   |
| Hewlett-Packard     | 2        | 3.33%   |
| KLLISRE             | 1        | 1.67%   |
| Intel               | 1        | 1.67%   |
| Google              | 1        | 1.67%   |
| GEEKOM              | 1        | 1.67%   |
| Dell                | 1        | 1.67%   |
| Acer                | 1        | 1.67%   |

Model
-----

Motherboard model

![Model](./images/pie_chart_bsd/node_model.svg)


| Name                                        | Desktops | Percent |
|---------------------------------------------|----------|---------|
| Unknown                                     | 26       | 43.33%  |
| ASUS PRIME A320M-K                          | 2        | 3.33%   |
| MSI MS-7B86                                 | 1        | 1.67%   |
| MSI MS-7551                                 | 1        | 1.67%   |
| Lenovo ThinkCentre M72e 3598CP8             | 1        | 1.67%   |
| Lenovo IdeaCentre Gaming5 14ACN6 90RW005PUL | 1        | 1.67%   |
| KLLISRE X99-B5 V1.0                         | 1        | 1.67%   |
| Intel DN2820FYK H24582-203                  | 1        | 1.67%   |
| HP Vectra                                   | 1        | 1.67%   |
| HP EliteDesk 800 G5 Desktop Mini            | 1        | 1.67%   |
| Google Monroe                               | 1        | 1.67%   |
| Gigabyte Z170X-Gaming 3                     | 1        | 1.67%   |
| Gigabyte X570 I AORUS PRO WIFI              | 1        | 1.67%   |
| Gigabyte X570 AORUS PRO                     | 1        | 1.67%   |
| Gigabyte P75-D3                             | 1        | 1.67%   |
| Gigabyte H61M-S2PV                          | 1        | 1.67%   |
| Gigabyte GA-990FX-GAMING                    | 1        | 1.67%   |
| Gigabyte B360M-D2V                          | 1        | 1.67%   |
| Gigabyte A320M-H                            | 1        | 1.67%   |
| Gigabyte 970A-D3P                           | 1        | 1.67%   |
| GEEKOM Mini IT13                            | 1        | 1.67%   |
| Dell OptiPlex 7040                          | 1        | 1.67%   |
| ASUS TUF B450-PRO GAMING                    | 1        | 1.67%   |
| ASUS TUF B450-PLUS GAMING                   | 1        | 1.67%   |
| ASUS TUF B360M-PLUS GAMING/BR               | 1        | 1.67%   |
| ASUS E45M1-I DELUXE                         | 1        | 1.67%   |
| ASUS B150M-K                                | 1        | 1.67%   |
| ASUS All Series                             | 1        | 1.67%   |
| ASRock X470 Gaming-ITX/ac                   | 1        | 1.67%   |
| ASRock N68-VS3 UCC                          | 1        | 1.67%   |
| ASRock H270 Pro4                            | 1        | 1.67%   |
| ASRock 970 Pro3 R2.0                        | 1        | 1.67%   |
| ASRock 970 Extreme3                         | 1        | 1.67%   |
| Acer Revo RN86                              | 1        | 1.67%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart_bsd/node_model_family.svg)


| Name                     | Desktops | Percent |
|--------------------------|----------|---------|
| Unknown                  | 26       | 43.33%  |
| ASUS TUF                 | 3        | 5%      |
| Gigabyte X570            | 2        | 3.33%   |
| ASUS PRIME               | 2        | 3.33%   |
| ASRock 970               | 2        | 3.33%   |
| MSI MS-7B86              | 1        | 1.67%   |
| MSI MS-7551              | 1        | 1.67%   |
| Lenovo ThinkCentre       | 1        | 1.67%   |
| Lenovo IdeaCentre        | 1        | 1.67%   |
| KLLISRE X99-B5           | 1        | 1.67%   |
| Intel DN2820FYK          | 1        | 1.67%   |
| HP Vectra                | 1        | 1.67%   |
| HP EliteDesk             | 1        | 1.67%   |
| Google Monroe            | 1        | 1.67%   |
| Gigabyte Z170X-Gaming    | 1        | 1.67%   |
| Gigabyte P75-D3          | 1        | 1.67%   |
| Gigabyte H61M-S2PV       | 1        | 1.67%   |
| Gigabyte GA-990FX-GAMING | 1        | 1.67%   |
| Gigabyte B360M-D2V       | 1        | 1.67%   |
| Gigabyte A320M-H         | 1        | 1.67%   |
| Gigabyte 970A-D3P        | 1        | 1.67%   |
| GEEKOM Mini              | 1        | 1.67%   |
| Dell OptiPlex            | 1        | 1.67%   |
| ASUS E45M1-I             | 1        | 1.67%   |
| ASUS B150M-K             | 1        | 1.67%   |
| ASUS All                 | 1        | 1.67%   |
| ASRock X470              | 1        | 1.67%   |
| ASRock N68-VS3           | 1        | 1.67%   |
| ASRock H270              | 1        | 1.67%   |
| Acer Revo                | 1        | 1.67%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart_bsd/node_year.svg)


| Year    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 23       | 38.33%  |
| 2020    | 6        | 10%     |
| 2018    | 6        | 10%     |
| 2022    | 3        | 5%      |
| 2021    | 3        | 5%      |
| 2017    | 3        | 5%      |
| 2013    | 3        | 5%      |
| 2019    | 2        | 3.33%   |
| 2016    | 2        | 3.33%   |
| 2014    | 2        | 3.33%   |
| 2012    | 2        | 3.33%   |
| 2024    | 1        | 1.67%   |
| 2015    | 1        | 1.67%   |
| 2011    | 1        | 1.67%   |
| 2010    | 1        | 1.67%   |
| 2001    | 1        | 1.67%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart_bsd/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 60       | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart_bsd/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 59       | 98.33%  |
| Yes  | 1        | 1.67%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart_bsd/node_ram_total.svg)


| Size in GB  | Desktops | Percent |
|-------------|----------|---------|
| 4.01-8.0    | 11       | 18.33%  |
| 16.01-24.0  | 11       | 18.33%  |
| 8.01-16.0   | 10       | 16.67%  |
| 32.01-64.0  | 8        | 13.33%  |
| 3.01-4.0    | 5        | 8.33%   |
| 0.01-0.5    | 5        | 8.33%   |
| 1.01-2.0    | 3        | 5%      |
| 0.51-1.0    | 3        | 5%      |
| 24.01-32.0  | 2        | 3.33%   |
| 64.01-256.0 | 2        | 3.33%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart_bsd/node_ram_used.svg)


| Used GB | Desktops | Percent |
|---------|----------|---------|
| Unknown | 60       | 100%    |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart_bsd/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 0      | 25       | 39.68%  |
| 1      | 20       | 31.75%  |
| 2      | 13       | 20.63%  |
| 3      | 3        | 4.76%   |
| 4      | 2        | 3.17%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart_bsd/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 59       | 98.33%  |
| Yes       | 1        | 1.67%   |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart_bsd/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 49       | 81.67%  |
| No        | 11       | 18.33%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart_bsd/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 34       | 56.67%  |
| Yes       | 26       | 43.33%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart_bsd/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 38       | 63.33%  |
| Yes       | 22       | 36.67%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart_bsd/node_location.svg)


| Country                | Desktops | Percent |
|------------------------|----------|---------|
| Russia                 | 11       | 18.33%  |
| USA                    | 6        | 10%     |
| Germany                | 6        | 10%     |
| France                 | 5        | 8.33%   |
| Italy                  | 4        | 6.67%   |
| UK                     | 3        | 5%      |
| Spain                  | 3        | 5%      |
| Romania                | 3        | 5%      |
| Poland                 | 2        | 3.33%   |
| Latvia                 | 2        | 3.33%   |
| Japan                  | 2        | 3.33%   |
| Hungary                | 2        | 3.33%   |
| Finland                | 2        | 3.33%   |
| Denmark                | 2        | 3.33%   |
| Brazil                 | 2        | 3.33%   |
| Saudi Arabia           | 1        | 1.67%   |
| Netherlands            | 1        | 1.67%   |
| Czechia                | 1        | 1.67%   |
| Bosnia and Herzegovina | 1        | 1.67%   |
| Australia              | 1        | 1.67%   |

City
----

Geographic location (city)

![City](./images/pie_chart_bsd/node_city.svg)


| City                  | Desktops | Percent |
|-----------------------|----------|---------|
| Ozersk                | 6        | 10%     |
| Rome                  | 3        | 5%      |
| Moscow                | 3        | 5%      |
| Lille                 | 3        | 5%      |
| Bucharest             | 3        | 5%      |
| Tampere               | 2        | 3.33%   |
| Riga                  | 2        | 3.33%   |
| Higashihatsuishi      | 2        | 3.33%   |
| Frederiksberg         | 2        | 3.33%   |
| Berlin                | 2        | 3.33%   |
| Urupes                | 1        | 1.67%   |
| Unterhaching          | 1        | 1.67%   |
| Ulan-Ude              | 1        | 1.67%   |
| Turin                 | 1        | 1.67%   |
| Sydney                | 1        | 1.67%   |
| Stourbridge           | 1        | 1.67%   |
| Sopron                | 1        | 1.67%   |
| Sarajevo              | 1        | 1.67%   |
| Royal Tunbridge Wells | 1        | 1.67%   |
| Riyadh                | 1        | 1.67%   |
| Reno                  | 1        | 1.67%   |
| Prague                | 1        | 1.67%   |
| Poznan                | 1        | 1.67%   |
| Portland              | 1        | 1.67%   |
| Poitiers              | 1        | 1.67%   |
| Noyon                 | 1        | 1.67%   |
| Novosibirsk           | 1        | 1.67%   |
| Murcia                | 1        | 1.67%   |
| Lohr a. Main          | 1        | 1.67%   |
| Kwidzyn               | 1        | 1.67%   |
| Hayward               | 1        | 1.67%   |
| Hamilton              | 1        | 1.67%   |
| Gardony               | 1        | 1.67%   |
| Fortaleza             | 1        | 1.67%   |
| Fort Wayne            | 1        | 1.67%   |
| Dallas                | 1        | 1.67%   |
| Bormujos              | 1        | 1.67%   |
| Borken                | 1        | 1.67%   |
| Bloomsbury            | 1        | 1.67%   |
| Amersfoort            | 1        | 1.67%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart_bsd/drive_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 11       | 14     | 19.3%   |
| Seagate             | 9        | 10     | 15.79%  |
| SanDisk             | 6        | 7      | 10.53%  |
| Samsung Electronics | 5        | 5      | 8.77%   |
| Toshiba             | 4        | 6      | 7.02%   |
| Kingston            | 4        | 5      | 7.02%   |
| Maxtor              | 3        | 4      | 5.26%   |
| JetFlash            | 2        | 2      | 3.51%   |
| Crucial             | 2        | 3      | 3.51%   |
| USB                 | 1        | 1      | 1.75%   |
| SMI                 | 1        | 1      | 1.75%   |
| SK hynix            | 1        | 2      | 1.75%   |
| Lexar               | 1        | 1      | 1.75%   |
| Intenso             | 1        | 1      | 1.75%   |
| IBM/Hitachi         | 1        | 1      | 1.75%   |
| HGST                | 1        | 1      | 1.75%   |
| Hewlett-Packard     | 1        | 1      | 1.75%   |
| Generic             | 1        | 1      | 1.75%   |
| Fanxiang            | 1        | 1      | 1.75%   |
| China               | 1        | 1      | 1.75%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart_bsd/drive_model.svg)


| Model                               | Desktops | Percent |
|-------------------------------------|----------|---------|
| Toshiba DT01ACA100 1TB              | 3        | 5.17%   |
| SanDisk Extreme SSD 1TB             | 3        | 5.17%   |
| Seagate ST1000DM010-2EP102 1TB      | 2        | 3.45%   |
| Samsung SSD 860 EVO 500GB           | 2        | 3.45%   |
| Samsung HD103UJ 1TB                 | 2        | 3.45%   |
| Maxtor STM3250310AS 250GB           | 2        | 3.45%   |
| Kingston DataTraveler 3.0 64GB      | 2        | 3.45%   |
| JetFlash Transcend 16GB             | 2        | 3.45%   |
| WDC WDS240G2G0B-00EPW0 240GB        | 1        | 1.72%   |
| WDC WDS240G2G0A-00JH30 240GB        | 1        | 1.72%   |
| WDC WDS120G2G0A-00JH30 120GB        | 1        | 1.72%   |
| WDC WD5003AZEX-00K3CA0 500GB        | 1        | 1.72%   |
| WDC WD5000AAKX-753CA1 500GB         | 1        | 1.72%   |
| WDC WD5000AACS-00ZUB0 500GB         | 1        | 1.72%   |
| WDC WD2502ABYS-01B7A0 256GB         | 1        | 1.72%   |
| WDC WD20EFRX-68EUZN0 2TB            | 1        | 1.72%   |
| WDC WD200EB-00BHF0 20GB             | 1        | 1.72%   |
| WDC WD10EZRZ-00HTKB0 1TB            | 1        | 1.72%   |
| WDC WD10EZEX-60WN4A0 1TB            | 1        | 1.72%   |
| WDC WD1002FAEX-00Y9A0 1TB           | 1        | 1.72%   |
| USB SanDisk 3.2Gen1 64GB            | 1        | 1.72%   |
| Toshiba DT01ACA200 2TB              | 1        | 1.72%   |
| SMI USB DISK 16GB                   | 1        | 1.72%   |
| SK hynix HFS128G39TND-N210A 128GB   | 1        | 1.72%   |
| Seagate ST940110A 40GB              | 1        | 1.72%   |
| Seagate ST380011A 80GB              | 1        | 1.72%   |
| Seagate ST33221A 3GB                | 1        | 1.72%   |
| Seagate ST2000DM001-1CH164 2TB      | 1        | 1.72%   |
| Seagate ST2000DL003-9VT166 2TB      | 1        | 1.72%   |
| Seagate ST1000LM 024 HN-M101MBB 1TB | 1        | 1.72%   |
| Seagate ST1000DX001-1CM162 1TB      | 1        | 1.72%   |
| SanDisk SSD i110 16GB               | 1        | 1.72%   |
| SanDisk SDSSDH3512G 512GB           | 1        | 1.72%   |
| SanDisk Cruzer Glide 16GB           | 1        | 1.72%   |
| Samsung HD501LJ 500GB               | 1        | 1.72%   |
| Maxtor 6E040L0 40GB                 | 1        | 1.72%   |
| Lexar USB Flash Drive 64GB          | 1        | 1.72%   |
| Kingston SM2280S3G2120G 120GB       | 1        | 1.72%   |
| Kingston SA400S37480G 480GB         | 1        | 1.72%   |
| Intenso Rainbow Line 8GB            | 1        | 1.72%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart_bsd/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 9        | 11     | 23.68%  |
| Seagate             | 9        | 10     | 23.68%  |
| Toshiba             | 4        | 6      | 10.53%  |
| Samsung Electronics | 3        | 3      | 7.89%   |
| Maxtor              | 3        | 4      | 7.89%   |
| JetFlash            | 2        | 2      | 5.26%   |
| USB                 | 1        | 1      | 2.63%   |
| SMI                 | 1        | 1      | 2.63%   |
| Lexar               | 1        | 1      | 2.63%   |
| Intenso             | 1        | 1      | 2.63%   |
| IBM/Hitachi         | 1        | 1      | 2.63%   |
| HGST                | 1        | 1      | 2.63%   |
| Hewlett-Packard     | 1        | 1      | 2.63%   |
| Generic             | 1        | 1      | 2.63%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart_bsd/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| SanDisk             | 6        | 7      | 30%     |
| Kingston            | 4        | 5      | 20%     |
| WDC                 | 3        | 3      | 15%     |
| Samsung Electronics | 2        | 2      | 10%     |
| Crucial             | 2        | 3      | 10%     |
| SK hynix            | 1        | 2      | 5%      |
| Fanxiang            | 1        | 1      | 5%      |
| China               | 1        | 1      | 5%      |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart_bsd/drive_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 26       | 44     | 57.78%  |
| SSD  | 19       | 24     | 42.22%  |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart_bsd/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 37       | 68     | 100%    |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart_bsd/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 32       | 41     | 61.54%  |
| 0.51-1.0   | 17       | 21     | 32.69%  |
| 1.01-2.0   | 3        | 6      | 5.77%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart_bsd/drive_space_total.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| 101-250    | 18       | 29.51%  |
| 251-500    | 9        | 14.75%  |
| 501-1000   | 9        | 14.75%  |
| 1-20       | 7        | 11.48%  |
| 51-100     | 6        | 9.84%   |
| 21-50      | 5        | 8.2%    |
| 1001-2000  | 4        | 6.56%   |
| 2001-3000  | 3        | 4.92%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart_bsd/drive_space_used.svg)


| Used GB   | Desktops | Percent |
|-----------|----------|---------|
| 1-20      | 48       | 73.85%  |
| 21-50     | 7        | 10.77%  |
| 51-100    | 4        | 6.15%   |
| 251-500   | 2        | 3.08%   |
| 1001-2000 | 2        | 3.08%   |
| 101-250   | 1        | 1.54%   |
| 501-1000  | 1        | 1.54%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart_bsd/drive_malfunc.svg)


| Model                             | Desktops | Drives | Percent |
|-----------------------------------|----------|--------|---------|
| WDC WDS240G2G0A-00JH30 240GB      | 1        | 1      | 14.29%  |
| WDC WD10EZEX-60WN4A0 1TB          | 1        | 1      | 14.29%  |
| SK hynix HFS128G39TND-N210A 128GB | 1        | 1      | 14.29%  |
| Seagate ST2000DL003-9VT166 2TB    | 1        | 1      | 14.29%  |
| Seagate ST1000DX001-1CM162 1TB    | 1        | 1      | 14.29%  |
| Maxtor 6E040L0 40GB               | 1        | 1      | 14.29%  |
| IBM/Hitachi IC25N040ATMR04-0 40GB | 1        | 1      | 14.29%  |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart_bsd/drive_malfunc_vendor.svg)


| Vendor      | Desktops | Drives | Percent |
|-------------|----------|--------|---------|
| WDC         | 2        | 2      | 28.57%  |
| Seagate     | 2        | 2      | 28.57%  |
| SK hynix    | 1        | 1      | 14.29%  |
| Maxtor      | 1        | 1      | 14.29%  |
| IBM/Hitachi | 1        | 1      | 14.29%  |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart_bsd/drive_malfunc_hdd_vendor.svg)


| Vendor      | Desktops | Drives | Percent |
|-------------|----------|--------|---------|
| Seagate     | 2        | 2      | 40%     |
| WDC         | 1        | 1      | 20%     |
| Maxtor      | 1        | 1      | 20%     |
| IBM/Hitachi | 1        | 1      | 20%     |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart_bsd/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 5        | 5      | 71.43%  |
| SSD  | 2        | 2      | 28.57%  |

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
| Works    | 28       | 51     | 62.22%  |
| Detected | 10       | 10     | 22.22%  |
| Malfunc  | 7        | 7      | 15.56%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart_bsd/storage_vendor.svg)


| Vendor                    | Desktops | Percent |
|---------------------------|----------|---------|
| Intel                     | 30       | 41.1%   |
| AMD                       | 19       | 26.03%  |
| Samsung Electronics       | 6        | 8.22%   |
| Silicon Motion            | 4        | 5.48%   |
| Phison Electronics        | 4        | 5.48%   |
| SanDisk                   | 3        | 4.11%   |
| Micron/Crucial Technology | 2        | 2.74%   |
| VIA Technologies          | 1        | 1.37%   |
| ULi Electronics           | 1        | 1.37%   |
| SK hynix                  | 1        | 1.37%   |
| Nvidia                    | 1        | 1.37%   |
| ASMedia Technology        | 1        | 1.37%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart_bsd/storage_model.svg)


| Model                                                                          | Desktops | Percent |
|--------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 8        | 9.64%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 7        | 8.43%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 5        | 6.02%   |
| AMD 400 Series Chipset SATA Controller                                         | 5        | 6.02%   |
| Silicon Motion SM2263EN/SM2263XT (DRAM-less) NVMe SSD Controllers              | 4        | 4.82%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                     | 4        | 4.82%   |
| SanDisk Ultra 3D / WD PC SN530, IX SN530, Blue SN550 NVMe SSD (DRAM-less)      | 3        | 3.61%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 3        | 3.61%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                    | 3        | 3.61%   |
| Intel Alder Lake-N SATA AHCI Controller                                        | 3        | 3.61%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]   | 3        | 3.61%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                           | 3        | 3.61%   |
| AMD A320 Chipset SATA Controller [AHCI mode]                                   | 3        | 3.61%   |
| Micron/Crucial P2 [Nick P2] / P3 / P3 Plus NVMe PCIe SSD (DRAM-less)           | 2        | 2.41%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 2        | 2.41%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 2        | 2.41%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller  | 2        | 2.41%   |
| VIA VT82C586A/B/VT82C686/A/B/VT823x/A/C PIPC Bus Master IDE                    | 1        | 1.2%    |
| ULi M5229 IDE                                                                  | 1        | 1.2%    |
| SK hynix PC601 NVMe Solid State Drive                                          | 1        | 1.2%    |
| Phison PS5021-E21 PCIe4 NVMe Controller (DRAM-less)                            | 1        | 1.2%    |
| Phison PS5013-E13 PCIe3 NVMe Controller (DRAM-less)                            | 1        | 1.2%    |
| Phison E16 PCIe4 NVMe Controller                                               | 1        | 1.2%    |
| Phison E12 NVMe Controller                                                     | 1        | 1.2%    |
| Nvidia MCP61 SATA Controller                                                   | 1        | 1.2%    |
| Nvidia MCP61 IDE                                                               | 1        | 1.2%    |
| Intel Optane NVME SSD H10 with Solid State Storage [Teton Glacier]             | 1        | 1.2%    |
| Intel Jasper Lake SATA AHCI Controller                                         | 1        | 1.2%    |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 1        | 1.2%    |
| Intel Atom Processor E3800 Series SATA AHCI Controller                         | 1        | 1.2%    |
| Intel Alder Lake-P SATA AHCI Controller                                        | 1        | 1.2%    |
| Intel 82801AA IDE Controller                                                   | 1        | 1.2%    |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 1        | 1.2%    |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 1        | 1.2%    |
| Intel 400 Series Chipset Family SATA AHCI Controller                           | 1        | 1.2%    |
| Intel 200 Series PCH SATA controller [AHCI mode]                               | 1        | 1.2%    |
| ASMedia ASM1061 Serial ATA Controller                                          | 1        | 1.2%    |
| AMD 500 Series Chipset SATA Controller                                         | 1        | 1.2%    |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart_bsd/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 47       | 61.84%  |
| NVMe | 20       | 26.32%  |
| IDE  | 8        | 10.53%  |
| RAID | 1        | 1.32%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart_bsd/cpu_vendor.svg)


| Vendor          | Desktops | Percent |
|-----------------|----------|---------|
| Intel           | 31       | 51.67%  |
| AMD             | 20       | 33.33%  |
| Arm             | 3        | 5%      |
| Unknown         | 3        | 5%      |
| 7447A           | 2        | 3.33%   |
| SUNW,UltraAX-i2 | 1        | 1.67%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart_bsd/cpu_model.svg)


| Model                                           | Desktops | Percent |
|-------------------------------------------------|----------|---------|
| Intel 686-class                                 | 11       | 18.03%  |
| Arm Cortex-A53 r0p4 (v8-A)                      | 3        | 4.92%   |
|                                                 | 3        | 4.92%   |
| Intel N100                                      | 2        | 3.28%   |
| AMD Ryzen 9 3900X 12-Core Processor             | 2        | 3.28%   |
| AMD 686-class                                   | 2        | 3.28%   |
| 7447A (Revision 1.2)                            | 2        | 3.28%   |
| SUNW,UltraAX-i2 (SUNW,UltraSPARC-IIe @ 500 MHz) | 1        | 1.64%   |
| Intel Xeon CPU E5-2630L v3 @ 1.80GHz            | 1        | 1.64%   |
| Intel Pentium III                               | 1        | 1.64%   |
| Intel Core i7-9700 CPU @ 3.00GHz                | 1        | 1.64%   |
| Intel Core i7-7700 CPU @ 3.60GHz                | 1        | 1.64%   |
| Intel Core i7-6700K CPU @ 4.00GHz               | 1        | 1.64%   |
| Intel Core i7-3770 CPU @ 3.40GHz                | 1        | 1.64%   |
| Intel Core i5-9600K CPU @ 3.70GHz               | 1        | 1.64%   |
| Intel Core i5-9400T CPU @ 1.80GHz               | 1        | 1.64%   |
| Intel Core i5-9400F CPU @ 2.90GHz               | 1        | 1.64%   |
| Intel Core i5-7400 CPU @ 3.00GHz                | 1        | 1.64%   |
| Intel Core i5-6500T CPU @ 2.50GHz               | 1        | 1.64%   |
| Intel Core i5-4310M CPU @ 2.70GHz               | 1        | 1.64%   |
| Intel Core i5-2500K CPU @ 3.30GHz               | 1        | 1.64%   |
| Intel Core i5-2320 CPU @ 3.00GHz                | 1        | 1.64%   |
| Intel Core i5-1035G1 CPU @ 1.00GHz              | 1        | 1.64%   |
| Intel Core i3-4150 CPU @ 3.50GHz                | 1        | 1.64%   |
| Intel Celeron CPU N2830 @ 2.16GHz               | 1        | 1.64%   |
| Intel Celeron 2955U @ 1.40GHz                   | 1        | 1.64%   |
| Intel 13th Gen Core i7-13620H                   | 1        | 1.64%   |
| AMD Sempron 145 Processor                       | 1        | 1.64%   |
| AMD Ryzen 7 3700X 8-Core Processor              | 1        | 1.64%   |
| AMD Ryzen 7 2700 Eight-Core Processor           | 1        | 1.64%   |
| AMD Ryzen 5 5600G with Radeon Graphics          | 1        | 1.64%   |
| AMD Ryzen 5 3600 6-Core Processor               | 1        | 1.64%   |
| AMD Ryzen 5 2600 Six-Core Processor             | 1        | 1.64%   |
| AMD Ryzen 3 3200G with Radeon Vega Graphics     | 1        | 1.64%   |
| AMD Ryzen 3 2200G with Radeon Vega Graphics     | 1        | 1.64%   |
| AMD Ryzen 3 1200 Quad-Core Processor            | 1        | 1.64%   |
| AMD Phenom II X6 1055T Processor                | 1        | 1.64%   |
| AMD Phenom II X4 965 Processor                  | 1        | 1.64%   |
| AMD FX-8350 Eight-Core Processor                | 1        | 1.64%   |
| AMD FX-8320 Eight-Core Processor                | 1        | 1.64%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart_bsd/cpu_family.svg)


| Model             | Desktops | Percent |
|-------------------|----------|---------|
| Other             | 12       | 19.67%  |
| Intel 686-class   | 11       | 18.03%  |
| Intel Core i5     | 9        | 14.75%  |
| Intel Core i7     | 4        | 6.56%   |
| AMD Ryzen 5       | 3        | 4.92%   |
| AMD Ryzen 3       | 3        | 4.92%   |
| AMD FX            | 3        | 4.92%   |
| Intel Celeron     | 2        | 3.28%   |
| AMD Ryzen 9       | 2        | 3.28%   |
| AMD Ryzen 7       | 2        | 3.28%   |
| AMD 686-class     | 2        | 3.28%   |
| Intel Xeon        | 1        | 1.64%   |
| Intel Pentium III | 1        | 1.64%   |
| Intel Core i3     | 1        | 1.64%   |
| ARM Cortex        | 1        | 1.64%   |
| AMD Sempron       | 1        | 1.64%   |
| AMD Phenom II X6  | 1        | 1.64%   |
| AMD Phenom II X4  | 1        | 1.64%   |
| AMD E             | 1        | 1.64%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart_bsd/cpu_cores.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| Unknown | 30       | 49.18%  |
| 4       | 12       | 19.67%  |
| 6       | 7        | 11.48%  |
| 8       | 6        | 9.84%   |
| 2       | 3        | 4.92%   |
| 12      | 2        | 3.28%   |
| 10      | 1        | 1.64%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart_bsd/cpu_sockets.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 1       | 36       | 59.02%  |
| Unknown | 25       | 40.98%  |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart_bsd/cpu_threads.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| Unknown | 30       | 49.18%  |
| 1       | 17       | 27.87%  |
| 2       | 13       | 21.31%  |
| 6       | 1        | 1.64%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart_bsd/cpu_microarch.svg)


| Name        | Desktops | Percent |
|-------------|----------|---------|
| Unknown     | 28       | 45.9%   |
| KabyLake    | 6        | 9.84%   |
| Zen 2       | 4        | 6.56%   |
| Zen+        | 3        | 4.92%   |
| Piledriver  | 3        | 4.92%   |
| Haswell     | 3        | 4.92%   |
| Zen         | 2        | 3.28%   |
| Skylake     | 2        | 3.28%   |
| SandyBridge | 2        | 3.28%   |
| P6          | 2        | 3.28%   |
| K10         | 2        | 3.28%   |
| Zen 3       | 1        | 1.64%   |
| Silvermont  | 1        | 1.64%   |
| IvyBridge   | 1        | 1.64%   |
| Bobcat      | 1        | 1.64%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart_bsd/gpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 24       | 42.11%  |
| AMD    | 21       | 36.84%  |
| Nvidia | 12       | 21.05%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart_bsd/gpu_model.svg)


| Model                                                                     | Desktops | Percent |
|---------------------------------------------------------------------------|----------|---------|
| Intel HD Graphics 530                                                     | 4        | 6.9%    |
| Intel Alder Lake-N [UHD Graphics]                                         | 3        | 5.17%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                   | 3        | 5.17%   |
| Nvidia GF114 [GeForce GTX 560]                                            | 2        | 3.45%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                 | 2        | 3.45%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller | 2        | 3.45%   |
| AMD RV280 [Radeon 9200]                                                   | 2        | 3.45%   |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                          | 2        | 3.45%   |
| Nvidia TU116 [GeForce GTX 1660 SUPER]                                     | 1        | 1.72%   |
| Nvidia NV5 [Riva TNT2 Model 64 / Model 64 Pro]                            | 1        | 1.72%   |
| Nvidia NV18 [GeForce4 MX 440 AGP 8x]                                      | 1        | 1.72%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                   | 1        | 1.72%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                        | 1        | 1.72%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                       | 1        | 1.72%   |
| Nvidia GM206 [GeForce GTX 960]                                            | 1        | 1.72%   |
| Nvidia GM204 [GeForce GTX 970]                                            | 1        | 1.72%   |
| Nvidia G86 [GeForce 8500 GT]                                              | 1        | 1.72%   |
| Nvidia C61 [GeForce 7025 / nForce 630a]                                   | 1        | 1.72%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller          | 1        | 1.72%   |
| Intel Raptor Lake-P [UHD Graphics]                                        | 1        | 1.72%   |
| Intel JasperLake [UHD Graphics]                                           | 1        | 1.72%   |
| Intel IvyBridge GT2 [HD Graphics 4000]                                    | 1        | 1.72%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                    | 1        | 1.72%   |
| Intel Iris Graphics 6100                                                  | 1        | 1.72%   |
| Intel HD Graphics 630                                                     | 1        | 1.72%   |
| Intel Haswell-ULT Integrated Graphics Controller                          | 1        | 1.72%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                  | 1        | 1.72%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                 | 1        | 1.72%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display              | 1        | 1.72%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller               | 1        | 1.72%   |
| Intel 3rd Gen Core processor Graphics Controller                          | 1        | 1.72%   |
| AMD Wrestler [Radeon HD 6320]                                             | 1        | 1.72%   |
| AMD Wrestler [Radeon HD 6250]                                             | 1        | 1.72%   |
| AMD Tonga PRO [Radeon R9 285/380]                                         | 1        | 1.72%   |
| AMD Sun LE [Radeon HD 8550M / R5 M230]                                    | 1        | 1.72%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                  | 1        | 1.72%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]          | 1        | 1.72%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]      | 1        | 1.72%   |
| AMD Oland [Radeon HD 8570 / R5 430 OEM / R7 240/340 / Radeon 520 OEM]     | 1        | 1.72%   |
| AMD Oland PRO [Radeon R7 240/340 / Radeon 520]                            | 1        | 1.72%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart_bsd/gpu_combo.svg)


| Name           | Desktops | Percent |
|----------------|----------|---------|
| 1 x Intel      | 21       | 35%     |
| 1 x AMD        | 18       | 30%     |
| 1 x Nvidia     | 11       | 18.33%  |
| Other          | 7        | 11.67%  |
| 2 x AMD        | 1        | 1.67%   |
| Intel + Nvidia | 1        | 1.67%   |
| Intel + AMD    | 1        | 1.67%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart_bsd/gpu_driver.svg)


| Driver  | Desktops | Percent |
|---------|----------|---------|
| Free    | 38       | 60.32%  |
| Unknown | 25       | 39.68%  |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart_bsd/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 36       | 59.02%  |
| 1.01-2.0   | 8        | 13.11%  |
| 3.01-4.0   | 6        | 9.84%   |
| 0.51-1.0   | 5        | 8.2%    |
| 0.01-0.5   | 4        | 6.56%   |
| 7.01-8.0   | 1        | 1.64%   |
| 5.01-6.0   | 1        | 1.64%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart_bsd/mon_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Samsung Electronics | 6        | 23.08%  |
| Goldstar            | 5        | 19.23%  |
| Eizo                | 2        | 7.69%   |
| Acer                | 2        | 7.69%   |
| ViewSonic           | 1        | 3.85%   |
| Unknown (CDD)       | 1        | 3.85%   |
| Sony                | 1        | 3.85%   |
| Philips             | 1        | 3.85%   |
| NEC Computers       | 1        | 3.85%   |
| LG Display          | 1        | 3.85%   |
| Lenovo              | 1        | 3.85%   |
| Impression          | 1        | 3.85%   |
| Iiyama              | 1        | 3.85%   |
| Fujitsu Siemens     | 1        | 3.85%   |
| Apple               | 1        | 3.85%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart_bsd/mon_model.svg)


| Model                                                                 | Desktops | Percent |
|-----------------------------------------------------------------------|----------|---------|
| Samsung Electronics LCD Monitor SAM0C39 1920x1080 890x500mm 40.2-inch | 2        | 7.69%   |
| Eizo M170 ENC1768 1280x1024 340x270mm 17.1-inch                       | 2        | 7.69%   |
| ViewSonic VG2439 Series VSCD22B 1920x1080 520x290mm 23.4-inch         | 1        | 3.85%   |
| Unknown (CDD) VGA CDD0030 1920x1080 1150x650mm 52.0-inch              | 1        | 3.85%   |
| Sony TV SNY4D04 1920x1080                                             | 1        | 3.85%   |
| Samsung Electronics SyncMaster SAM01AE 1600x1200 410x310mm 20.2-inch  | 1        | 3.85%   |
| Samsung Electronics SMS27A350H SAM07CE 1920x1080 600x340mm 27.2-inch  | 1        | 3.85%   |
| Samsung Electronics S24C650 SAM09E9 1920x1080 520x290mm 23.4-inch     | 1        | 3.85%   |
| Samsung Electronics S23C570 SAM0A56 1920x1080 510x290mm 23.1-inch     | 1        | 3.85%   |
| Philips PHL 245E1 PHLC20B 2560x1440 530x300mm 24.0-inch               | 1        | 3.85%   |
| NEC Computers P221W NEC674A 1680x1050 470x300mm 22.0-inch             | 1        | 3.85%   |
| LG Display LCD Monitor LGD045E 1366x768 310x170mm 13.9-inch           | 1        | 3.85%   |
| Lenovo P27h-20 LEN61E9 2560x1440 600x340mm 27.2-inch                  | 1        | 3.85%   |
| Impression R19W11 IMP1911 1440x900 410x260mm 19.1-inch                | 1        | 3.85%   |
| Iiyama PL2792Q IVM6630 2560x1440 600x340mm 27.2-inch                  | 1        | 3.85%   |
| Goldstar W1952 GSM4B78 1440x900 410x260mm 19.1-inch                   | 1        | 3.85%   |
| Goldstar LG ULTRAWIDE GSM59F1 2560x1080 580x240mm 24.7-inch           | 1        | 3.85%   |
| Goldstar LG HDR 4K GSM7706 3840x2160 600x340mm 27.2-inch              | 1        | 3.85%   |
| Goldstar L226WTQ GSM564D 1680x1050 490x320mm 23.0-inch                | 1        | 3.85%   |
| Goldstar L194WT GSM4B05 1440x900 410x260mm 19.1-inch                  | 1        | 3.85%   |
| Fujitsu Siemens SL27T-1 LED FUS07E5 1920x1080 600x340mm 27.2-inch     | 1        | 3.85%   |
| Apple Color LCD APPA029 2560x1600 290x180mm 13.4-inch                 | 1        | 3.85%   |
| Acer SB220Q ACR06AB 1920x1080 480x270mm 21.7-inch                     | 1        | 3.85%   |
| Acer QG241Y ACR079C 1920x1080 520x320mm 24.0-inch                     | 1        | 3.85%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart_bsd/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 10       | 40%     |
| 2560x1440 (QHD)    | 3        | 12%     |
| 1440x900 (WXGA+)   | 3        | 12%     |
| 1680x1050 (WSXGA+) | 2        | 8%      |
| 1280x1024 (SXGA)   | 2        | 8%      |
| 3840x2160 (4K)     | 1        | 4%      |
| 2560x1600          | 1        | 4%      |
| 2560x1080          | 1        | 4%      |
| 1600x1200          | 1        | 4%      |
| 1366x768 (WXGA)    | 1        | 4%      |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart_bsd/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 27      | 5        | 19.23%  |
| 23      | 4        | 15.38%  |
| 19      | 3        | 11.54%  |
| 40      | 2        | 7.69%   |
| 24      | 2        | 7.69%   |
| 17      | 2        | 7.69%   |
| 13      | 2        | 7.69%   |
| 52      | 1        | 3.85%   |
| 34      | 1        | 3.85%   |
| 22      | 1        | 3.85%   |
| 21      | 1        | 3.85%   |
| 20      | 1        | 3.85%   |
| Unknown | 1        | 3.85%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart_bsd/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 501-600     | 10       | 38.46%  |
| 401-500     | 7        | 26.92%  |
| 301-350     | 3        | 11.54%  |
| 801-900     | 2        | 7.69%   |
| 701-800     | 1        | 3.85%   |
| 201-300     | 1        | 3.85%   |
| 1001-1500   | 1        | 3.85%   |
| Unknown     | 1        | 3.85%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart_bsd/mon_ratio.svg)


| Ratio | Desktops | Percent |
|-------|----------|---------|
| 16/9  | 14       | 56%     |
| 16/10 | 6        | 24%     |
| 5/4   | 2        | 8%      |
| 4/3   | 1        | 4%      |
| 3/2   | 1        | 4%      |
| 21/9  | 1        | 4%      |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart_bsd/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 7        | 26.92%  |
| 301-350        | 5        | 19.23%  |
| 151-200        | 4        | 15.38%  |
| 81-90          | 2        | 7.69%   |
| 141-150        | 2        | 7.69%   |
| 501-1000       | 2        | 7.69%   |
| More than 1000 | 1        | 3.85%   |
| 351-500        | 1        | 3.85%   |
| 251-300        | 1        | 3.85%   |
| Unknown        | 1        | 3.85%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart_bsd/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 16       | 64%     |
| 101-120 | 4        | 16%     |
| 161-240 | 2        | 8%      |
| 1-50    | 1        | 4%      |
| 121-160 | 1        | 4%      |
| Unknown | 1        | 4%      |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart_bsd/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 30       | 49.18%  |
| 0     | 30       | 49.18%  |
| 2     | 1        | 1.64%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart_bsd/net_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Realtek Semiconductor | 29       | 40.28%  |
| Intel                 | 24       | 33.33%  |
| Qualcomm Atheros      | 7        | 9.72%   |
| Broadcom              | 3        | 4.17%   |
| Huawei Technologies   | 2        | 2.78%   |
| 3Com                  | 2        | 2.78%   |
| Oculus VR             | 1        | 1.39%   |
| Netchip Technology    | 1        | 1.39%   |
| Mercucys              | 1        | 1.39%   |
| MediaTek              | 1        | 1.39%   |
| Davicom Semiconductor | 1        | 1.39%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart_bsd/net_model.svg)


| Model                                                                  | Desktops | Percent |
|------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 27       | 30.68%  |
| Intel I211 Gigabit Network Connection                                  | 4        | 4.55%   |
| Intel Wi-Fi 6 AX200                                                    | 3        | 3.41%   |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]                | 3        | 3.41%   |
| Intel Ethernet Controller I225-V                                       | 3        | 3.41%   |
| Intel Ethernet Connection (2) I219-LM                                  | 3        | 3.41%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 3        | 3.41%   |
| Intel CNVi: Wi-Fi                                                      | 2        | 2.27%   |
| Intel Cannon Lake PCH CNVi WiFi                                        | 2        | 2.27%   |
| Huawei USB Device                                                      | 2        | 2.27%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter               | 1        | 1.14%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter               | 1        | 1.14%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                        | 1        | 1.14%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                                 | 1        | 1.14%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                    | 1        | 1.14%   |
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller      | 1        | 1.14%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                  | 1        | 1.14%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter             | 1        | 1.14%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller              | 1        | 1.14%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller              | 1        | 1.14%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                       | 1        | 1.14%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                       | 1        | 1.14%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)         | 1        | 1.14%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                          | 1        | 1.14%   |
| Oculus VR Rift S                                                       | 1        | 1.14%   |
| Netchip Linux-USB Serial Gadget (CDC ACM mode)                         | 1        | 1.14%   |
| Mercucys MERCUSYS Wireless USB Adapter                                 | 1        | 1.14%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter          | 1        | 1.14%   |
| Intel Wireless 8265 / 8275                                             | 1        | 1.14%   |
| Intel Wireless 7260                                                    | 1        | 1.14%   |
| Intel Wi-Fi 6 AX201 160MHz                                             | 1        | 1.14%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                        | 1        | 1.14%   |
| Intel Ethernet Connection I217-V                                       | 1        | 1.14%   |
| Intel Ethernet Connection (7) I219-V                                   | 1        | 1.14%   |
| Intel Ethernet Connection (7) I219-LM                                  | 1        | 1.14%   |
| Intel Ethernet Connection (2) I219-V                                   | 1        | 1.14%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                       | 1        | 1.14%   |
| Intel Centrino Ultimate-N 6300                                         | 1        | 1.14%   |
| Intel 82574L Gigabit Network Connection                                | 1        | 1.14%   |
| Davicom DM9102 Fast Ethernet Controller                                | 1        | 1.14%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart_bsd/net_wireless_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Intel                 | 15       | 53.57%  |
| Realtek Semiconductor | 5        | 17.86%  |
| Qualcomm Atheros      | 4        | 14.29%  |
| Broadcom              | 2        | 7.14%   |
| Mercucys              | 1        | 3.57%   |
| MediaTek              | 1        | 3.57%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart_bsd/net_wireless_model.svg)


| Model                                                          | Desktops | Percent |
|----------------------------------------------------------------|----------|---------|
| Intel Wi-Fi 6 AX200                                            | 3        | 10.71%  |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]        | 3        | 10.71%  |
| Intel CNVi: Wi-Fi                                              | 2        | 7.14%   |
| Intel Cannon Lake PCH CNVi WiFi                                | 2        | 7.14%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 1        | 3.57%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter       | 1        | 3.57%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                | 1        | 3.57%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                         | 1        | 3.57%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter            | 1        | 3.57%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 1        | 3.57%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 1        | 3.57%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter               | 1        | 3.57%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 1        | 3.57%   |
| Mercucys MERCUSYS Wireless USB Adapter                         | 1        | 3.57%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter  | 1        | 3.57%   |
| Intel Wireless 8265 / 8275                                     | 1        | 3.57%   |
| Intel Wireless 7260                                            | 1        | 3.57%   |
| Intel Wi-Fi 6 AX201 160MHz                                     | 1        | 3.57%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                | 1        | 3.57%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]               | 1        | 3.57%   |
| Broadcom BCM43602 802.11ac Wireless LAN SoC                    | 1        | 3.57%   |
| Broadcom BCM4331 802.11a/b/g/n                                 | 1        | 3.57%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart_bsd/net_ethernet_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Realtek Semiconductor | 29       | 51.79%  |
| Intel                 | 17       | 30.36%  |
| Qualcomm Atheros      | 3        | 5.36%   |
| Huawei Technologies   | 2        | 3.57%   |
| Broadcom              | 2        | 3.57%   |
| 3Com                  | 2        | 3.57%   |
| Davicom Semiconductor | 1        | 1.79%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart_bsd/net_ethernet_model.svg)


| Model                                                                  | Desktops | Percent |
|------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 27       | 47.37%  |
| Intel I211 Gigabit Network Connection                                  | 4        | 7.02%   |
| Intel Ethernet Controller I225-V                                       | 3        | 5.26%   |
| Intel Ethernet Connection (2) I219-LM                                  | 3        | 5.26%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 3        | 5.26%   |
| Huawei USB Device                                                      | 2        | 3.51%   |
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller      | 1        | 1.75%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                  | 1        | 1.75%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller              | 1        | 1.75%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller              | 1        | 1.75%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                          | 1        | 1.75%   |
| Intel Ethernet Connection I217-V                                       | 1        | 1.75%   |
| Intel Ethernet Connection (7) I219-V                                   | 1        | 1.75%   |
| Intel Ethernet Connection (7) I219-LM                                  | 1        | 1.75%   |
| Intel Ethernet Connection (2) I219-V                                   | 1        | 1.75%   |
| Intel 82574L Gigabit Network Connection                                | 1        | 1.75%   |
| Davicom DM9102 Fast Ethernet Controller                                | 1        | 1.75%   |
| Broadcom NetXtreme BCM57766 Gigabit Ethernet PCIe                      | 1        | 1.75%   |
| Broadcom NetXtreme BCM5720 Gigabit Ethernet PCIe                       | 1        | 1.75%   |
| 3Com 3c905C-TX/TX-M [Tornado]                                          | 1        | 1.75%   |
| 3Com 3c905B 100BaseTX [Cyclone]                                        | 1        | 1.75%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart_bsd/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 51       | 62.96%  |
| WiFi     | 27       | 33.33%  |
| Modem    | 2        | 2.47%   |
| Unknown  | 1        | 1.23%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart_bsd/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 44       | 93.62%  |
| WiFi     | 3        | 6.38%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart_bsd/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 27       | 44.26%  |
| 2     | 19       | 31.15%  |
| 0     | 9        | 14.75%  |
| 3     | 5        | 8.2%    |
| 4     | 1        | 1.64%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart_bsd/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 48       | 78.69%  |
| Yes  | 13       | 21.31%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart_bsd/bt_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 13       | 59.09%  |
| Realtek Semiconductor           | 3        | 13.64%  |
| Apple                           | 2        | 9.09%   |
| Qualcomm Atheros Communications | 1        | 4.55%   |
| Lite-On Technology              | 1        | 4.55%   |
| IMC Networks                    | 1        | 4.55%   |
| Cambridge Silicon Radio         | 1        | 4.55%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart_bsd/bt_model.svg)


| Model                                               | Desktops | Percent |
|-----------------------------------------------------|----------|---------|
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 4        | 18.18%  |
| Realtek Bluetooth Adapter                           | 2        | 9.09%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 2        | 9.09%   |
| Intel Bluetooth wireless interface                  | 2        | 9.09%   |
| Intel AX201 Bluetooth                               | 2        | 9.09%   |
| Intel AX200 Bluetooth                               | 2        | 9.09%   |
| Realtek Bluetooth 4.0 Adapter                       | 1        | 4.55%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 1        | 4.55%   |
| Lite-On Atheros AR3012 Bluetooth                    | 1        | 4.55%   |
| Intel Wireless-AC 3168 Bluetooth                    | 1        | 4.55%   |
| IMC Networks MediaTek Bluetooth Adapter             | 1        | 4.55%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 1        | 4.55%   |
| Apple Broadcom Built-in Bluetooth                   | 1        | 4.55%   |
| Apple Bluetooth Host Controller                     | 1        | 4.55%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart_bsd/snd_vendor.svg)


| Vendor                                       | Desktops | Percent |
|----------------------------------------------|----------|---------|
| Intel                                        | 30       | 42.25%  |
| AMD                                          | 22       | 30.99%  |
| Nvidia                                       | 8        | 11.27%  |
| Zoran Co. Personal Media Division (Nogatech) | 2        | 2.82%   |
| Logitech                                     | 2        | 2.82%   |
| Yamaha                                       | 1        | 1.41%   |
| Walmart                                      | 1        | 1.41%   |
| Samsung Electronics                          | 1        | 1.41%   |
| Realtek Semiconductor                        | 1        | 1.41%   |
| Native Instruments                           | 1        | 1.41%   |
| ESS Technology                               | 1        | 1.41%   |
| Creative Labs                                | 1        | 1.41%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart_bsd/snd_model.svg)


| Model                                                                             | Desktops | Percent |
|-----------------------------------------------------------------------------------|----------|---------|
| AMD SBx00 Azalia (Intel HDA)                                                      | 7        | 7.78%   |
| Intel Cannon Lake PCH cAVS                                                        | 5        | 5.56%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                   | 5        | 5.56%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller               | 4        | 4.44%   |
| AMD Starship/Matisse HD Audio Controller                                          | 4        | 4.44%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]           | 4        | 4.44%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                               | 4        | 4.44%   |
| Intel Alder Lake-N PCH High Definition Audio Controller                           | 3        | 3.33%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller               | 3        | 3.33%   |
| AMD Family 17h/19h/1ah HD Audio Controller                                        | 3        | 3.33%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                        | 3        | 3.33%   |
| Zoran Co. Personal Media Division (Nogatech) USB Audio and HID                    | 2        | 2.22%   |
| Nvidia GP107GL High Definition Audio Controller                                   | 2        | 2.22%   |
| Nvidia GF114 HDMI Audio Controller                                                | 2        | 2.22%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller        | 2        | 2.22%   |
| AMD Wrestler HDMI Audio                                                           | 2        | 2.22%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                               | 2        | 2.22%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                            | 2        | 2.22%   |
| AMD Caicos HDMI Audio [Radeon HD 6450 / 7450/8450/8490 OEM / R5 230/235/235X OEM] | 2        | 2.22%   |
| Yamaha AG06/AG03                                                                  | 1        | 1.11%   |
| Walmart AB13X Headset Adapter                                                     | 1        | 1.11%   |
| Samsung Electronics Samsung Type-C to 3.5pi gender adapter                        | 1        | 1.11%   |
| Realtek Semiconductor ATH-M50xSTS-USB                                             | 1        | 1.11%   |
| Nvidia TU116 High Definition Audio Controller                                     | 1        | 1.11%   |
| Nvidia GP106 High Definition Audio Controller                                     | 1        | 1.11%   |
| Nvidia GM206 High Definition Audio Controller                                     | 1        | 1.11%   |
| Nvidia GM204 High Definition Audio Controller                                     | 1        | 1.11%   |
| Native Instruments Komplete Audio 1                                               | 1        | 1.11%   |
| Logitech Zone Wired Earbuds                                                       | 1        | 1.11%   |
| Logitech H600 [Wireless Headset]                                                  | 1        | 1.11%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                  | 1        | 1.11%   |
| Intel Wildcat Point-LP High Definition Audio Controller                           | 1        | 1.11%   |
| Intel Raptor Lake-P/U/H cAVS                                                      | 1        | 1.11%   |
| Intel Jasper Lake HD Audio                                                        | 1        | 1.11%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                         | 1        | 1.11%   |
| Intel Haswell-ULT HD Audio Controller                                             | 1        | 1.11%   |
| Intel Comet Lake PCH-V cAVS                                                       | 1        | 1.11%   |
| Intel Broadwell-U Audio Controller                                                | 1        | 1.11%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller        | 1        | 1.11%   |
| Intel 82801AA AC'97 Audio Controller                                              | 1        | 1.11%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart_bsd/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Crucial             | 10       | 23.81%  |
| Kingston            | 9        | 21.43%  |
| Micron Technology   | 4        | 9.52%   |
| G.Skill             | 4        | 9.52%   |
| Unknown             | 3        | 7.14%   |
| Corsair             | 3        | 7.14%   |
| Patriot             | 2        | 4.76%   |
| A-DATA Technology   | 2        | 4.76%   |
| SK hynix            | 1        | 2.38%   |
| Samsung Electronics | 1        | 2.38%   |
| Lexar Co Limited    | 1        | 2.38%   |
| AMD                 | 1        | 2.38%   |
| Unknown             | 1        | 2.38%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart_bsd/memory_model.svg)


| Model                                                         | Desktops | Percent |
|---------------------------------------------------------------|----------|---------|
| Crucial RAM CT16G4SFS832A.C8FF 16GB SODIMM DDR4 3200MT/s      | 2        | 4.17%   |
| Unknown RAM Module 8192MB DIMM 400MT/s                        | 1        | 2.08%   |
| Unknown RAM Module 2GB DIMM DDR2 800MT/s                      | 1        | 2.08%   |
| Unknown RAM Module 2048MB DIMM DDR2 800MT/s                   | 1        | 2.08%   |
| Unknown RAM Module 2048MB DIMM 400MT/s                        | 1        | 2.08%   |
| Unknown RAM Module 128MB DIMM DRAM                            | 1        | 2.08%   |
| SK hynix RAM HMT351U6CFR8C 4GB DIMM DDR3 667MT/s              | 1        | 2.08%   |
| Samsung RAM M378A1K43EB2-CWE 8GB DIMM DDR4 3200MT/s           | 1        | 2.08%   |
| Patriot RAM PSD44G213382 4096MB DIMM DDR4 2133MT/s            | 1        | 2.08%   |
| Patriot RAM PSD34G13332 4GB DIMM DDR3 1333MT/s                | 1        | 2.08%   |
| Micron RAM 36ASF2G72PZ-2G1A2 16GB DIMM DDR4 2133MT/s          | 1        | 2.08%   |
| Micron RAM 16JTF51264AZ 4GB DIMM DDR3 667MT/s                 | 1        | 2.08%   |
| Micron RAM 16JTF1G64AZ-1G6J1 8GB DIMM DDR3 1333MT/s           | 1        | 2.08%   |
| Micron RAM 16ATF1G64HZ-2G1B1 8GB SODIMM DDR4 2133MT/s         | 1        | 2.08%   |
| Lexar Co Limited RAM LD4S16G32C22ST 16GB SODIMM DDR4 3200MT/s | 1        | 2.08%   |
| Kingston RAM KHX3000C15D4/8GX 8GB DIMM DDR4 2933MT/s          | 1        | 2.08%   |
| Kingston RAM KHX2400C15/8G 8GB DIMM DDR4 2400MT/s             | 1        | 2.08%   |
| Kingston RAM KHX1600C9D3/4GX 4GB DIMM DDR3 1600MT/s           | 1        | 2.08%   |
| Kingston RAM KF2666C16D4/16G 16GB DIMM DDR4 2667MT/s          | 1        | 2.08%   |
| Kingston RAM ACR26D4S9S8ME-8 8GB SODIMM DDR4 2667MT/s         | 1        | 2.08%   |
| Kingston RAM ACR16D3LS1KFG/4G 4GB DIMM DDR3 1600MT/s          | 1        | 2.08%   |
| Kingston RAM 99U5701-077.A00G 16GB DIMM DDR4 2667MT/s         | 1        | 2.08%   |
| Kingston RAM 99U5584-007.A 4GB DIMM DDR3 667MT/s              | 1        | 2.08%   |
| Kingston RAM 99U5471-028.A00LF 4GB DIMM DDR3 667MT/s          | 1        | 2.08%   |
| Kingston RAM 9905471-011.A00LF 4GB DIMM DDR3 1333MT/s         | 1        | 2.08%   |
| G.Skill RAM F4-3200C16-16GVK 16GB DIMM DDR4 3200MT/s          | 1        | 2.08%   |
| G.Skill RAM F4-3200C16-16GTZKW 16GB DIMM DDR4 3200MT/s        | 1        | 2.08%   |
| G.Skill RAM F4-2800C17-8GVR 8192MB DIMM DDR4 2133MT/s         | 1        | 2.08%   |
| G.Skill RAM F3-1600C11-8G 8GB DIMM DDR3 1600MT/s              | 1        | 2.08%   |
| Crucial RAM CT8G4DFS8266.M8FD 8GB DIMM DDR4 2667MT/s          | 1        | 2.08%   |
| Crucial RAM CT8G4DFS824A.M8FE 8GB DIMM DDR4 2933MT/s          | 1        | 2.08%   |
| Crucial RAM CT8G4DFS8213.C8FDR1 8GB DIMM DDR4 2133MT/s        | 1        | 2.08%   |
| Crucial RAM CT8G4DFS8213.C8FBD1 8GB DIMM DDR4 2133MT/s        | 1        | 2.08%   |
| Crucial RAM CT51264BD160BJ.C8F 4GB DIMM DDR3 1600MT/s         | 1        | 2.08%   |
| Crucial RAM CT51264BA160B.C16F 4GB DIMM DDR3 1600MT/s         | 1        | 2.08%   |
| Crucial RAM CT102464BA160B.C16 8GB DIMM DDR3 1600MT/s         | 1        | 2.08%   |
| Crucial RAM BLS4G4D240FSE.8FBD 4GB DIMM DDR4 2400MT/s         | 1        | 2.08%   |
| Crucial RAM BLS4G4D240FSB.8FBD2 4GB DIMM DDR4 2400MT/s        | 1        | 2.08%   |
| Crucial RAM BLS4G4D240FSB.8FBD 4GB DIMM DDR4 2400MT/s         | 1        | 2.08%   |
| Corsair RAM CMZ8GX3M2A1600C9 4GB DIMM DDR3 1600MT/s           | 1        | 2.08%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart_bsd/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR4    | 23       | 62.16%  |
| DDR3    | 11       | 29.73%  |
| DRAM    | 1        | 2.7%    |
| DDR2    | 1        | 2.7%    |
| Unknown | 1        | 2.7%    |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart_bsd/memory_formfactor.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| DIMM   | 30       | 81.08%  |
| SODIMM | 7        | 18.92%  |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart_bsd/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 8192  | 16       | 41.03%  |
| 4096  | 10       | 25.64%  |
| 16384 | 8        | 20.51%  |
| 2048  | 3        | 7.69%   |
| 32768 | 1        | 2.56%   |
| 128   | 1        | 2.56%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart_bsd/memory_speed.svg)


| Speed   | Desktops | Percent |
|---------|----------|---------|
| 3200    | 9        | 21.95%  |
| 1600    | 6        | 14.63%  |
| 2133    | 5        | 12.2%   |
| 2667    | 4        | 9.76%   |
| 2400    | 4        | 9.76%   |
| 1333    | 3        | 7.32%   |
| 2933    | 2        | 4.88%   |
| 800     | 2        | 4.88%   |
| 667     | 2        | 4.88%   |
| 3000    | 1        | 2.44%   |
| 2666    | 1        | 2.44%   |
| 400     | 1        | 2.44%   |
| Unknown | 1        | 2.44%   |

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
| Silicon Motion                   | 2        | 22.22%  |
| Logitech                         | 2        | 22.22%  |
| Chicony Electronics              | 2        | 22.22%  |
| Shenzhen Kingcome Optoelectronic | 1        | 11.11%  |
| IMC Networks                     | 1        | 11.11%  |
| ARC International                | 1        | 11.11%  |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart_bsd/camera_model.svg)


| Model                                                         | Desktops | Percent |
|---------------------------------------------------------------|----------|---------|
| Silicon Motion LG HD WebCam                                   | 1        | 11.11%  |
| Silicon Motion 300k Pixel Camera                              | 1        | 11.11%  |
| Shenzhen Kingcome Optoelectronic NexiGo HelloCam N930W Camera | 1        | 11.11%  |
| Logitech Webcam C270                                          | 1        | 11.11%  |
| Logitech C922 Pro Stream Webcam                               | 1        | 11.11%  |
| IMC Networks Realtek PC Camera                                | 1        | 11.11%  |
| Chicony USB2.0 VGA UVC WebCam                                 | 1        | 11.11%  |
| Chicony HP HD Webcam [Fixed]                                  | 1        | 11.11%  |
| ARC International Camera                                      | 1        | 11.11%  |

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
| 0     | 24       | 39.34%  |
| 1     | 19       | 31.15%  |
| 2     | 10       | 16.39%  |
| 3     | 7        | 11.48%  |
| 5     | 1        | 1.64%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart_bsd/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Communication controller | 28       | 49.12%  |
| Net/wireless             | 21       | 36.84%  |
| Net/ethernet             | 2        | 3.51%   |
| Card reader              | 2        | 3.51%   |
| Wireless                 | 1        | 1.75%   |
| Storage                  | 1        | 1.75%   |
| Graphics card            | 1        | 1.75%   |
| Bluetooth                | 1        | 1.75%   |

