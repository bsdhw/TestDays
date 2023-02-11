BSD in Netherlands - Tested Hardware & Statistics (Notebooks)
-------------------------------------------------------------

A project to collect tested hardware configurations for BSD in Netherlands.

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

Total: 70

| Vendor        | Model                       | Probe                                                     | Date         |
|---------------|-----------------------------|-----------------------------------------------------------|--------------|
| Acer          | Aspire ES1-520              | [efac696b1a](https://bsd-hardware.info/?probe=efac696b1a) | Jan 31, 2023 |
| Google        | Cave                        | [76ac12f1e2](https://bsd-hardware.info/?probe=76ac12f1e2) | Jan 25, 2023 |
| Lenovo        | ThinkPad S1 Yoga 20CD003... | [17fd94a4c0](https://bsd-hardware.info/?probe=17fd94a4c0) | Jan 23, 2023 |
| Intel         | Milstead Platform           | [21ec3118ef](https://bsd-hardware.info/?probe=21ec3118ef) | Jan 02, 2023 |
| Notebook      | NS5x_NS7xPU                 | [7dc1fdfadb](https://bsd-hardware.info/?probe=7dc1fdfadb) | Jan 02, 2023 |
| Lenovo        | ThinkPad T490 20N2CTO1WW    | [32207ea5d9](https://bsd-hardware.info/?probe=32207ea5d9) | Dec 19, 2022 |
| Deciso        | NetBoard-A10                | [79b2a5d3a5](https://bsd-hardware.info/?probe=79b2a5d3a5) | Dec 08, 2022 |
| Deciso        | NetBoard-A10                | [575d201794](https://bsd-hardware.info/?probe=575d201794) | Dec 07, 2022 |
| Lenovo        | ThinkPad X250 20CLS5BU00    | [10619ac217](https://bsd-hardware.info/?probe=10619ac217) | Dec 03, 2022 |
| Lenovo        | ThinkPad T430 2347G7G       | [640540cd67](https://bsd-hardware.info/?probe=640540cd67) | Nov 29, 2022 |
| Deciso        | NetBoard-A10                | [20058331ef](https://bsd-hardware.info/?probe=20058331ef) | Nov 19, 2022 |
| ASUSTek       | K53TA                       | [521283b723](https://bsd-hardware.info/?probe=521283b723) | Oct 22, 2022 |
| HP            | EliteBook 840 G3            | [7bf7249432](https://bsd-hardware.info/?probe=7bf7249432) | Sep 16, 2022 |
| Lenovo        | ThinkPad T440 20B7S2LT00    | [5104875f94](https://bsd-hardware.info/?probe=5104875f94) | Sep 06, 2022 |
| HP            | EliteBook 840 G3            | [28929cae10](https://bsd-hardware.info/?probe=28929cae10) | Aug 17, 2022 |
| Lenovo        | ThinkPad X61s 76693KG       | [445446cc28](https://bsd-hardware.info/?probe=445446cc28) | Jul 18, 2022 |
| ASUSTek       | X751LB                      | [5c2ef28301](https://bsd-hardware.info/?probe=5c2ef28301) | Jul 12, 2022 |
| Acer          | Aspire E1-522               | [d680e0d05d](https://bsd-hardware.info/?probe=d680e0d05d) | Jul 10, 2022 |
| Star Labs     | LabTop                      | [390c4c4d55](https://bsd-hardware.info/?probe=390c4c4d55) | Jul 03, 2022 |
| Lenovo        | IdeaPad 130-15AST 81H5      | [9f33082ffa](https://bsd-hardware.info/?probe=9f33082ffa) | Jun 08, 2022 |
| Dell          | Latitude E7240              | [970234b430](https://bsd-hardware.info/?probe=970234b430) | May 22, 2022 |
| HP            | EliteBook 8460p             | [b9350aeb55](https://bsd-hardware.info/?probe=b9350aeb55) | May 21, 2022 |
| Deciso        | OPNsense Appliance          | [c78d18300d](https://bsd-hardware.info/?probe=c78d18300d) | Apr 18, 2022 |
| Sony          | SVZ1311C5E                  | [c1c429a7e6](https://bsd-hardware.info/?probe=c1c429a7e6) | Apr 15, 2022 |
| Apple         | MacBookPro10,1              | [64ccf1e6a0](https://bsd-hardware.info/?probe=64ccf1e6a0) | Feb 18, 2022 |
| Lenovo        | ThinkPad X250 20CLS59400    | [92333ad60b](https://bsd-hardware.info/?probe=92333ad60b) | Feb 17, 2022 |
| HP            | EliteBook 840 G3            | [f259f73c17](https://bsd-hardware.info/?probe=f259f73c17) | Feb 14, 2022 |
| Dell          | Latitude E5430 non-vPro     | [e795c7ec91](https://bsd-hardware.info/?probe=e795c7ec91) | Jan 17, 2022 |
| Dell          | Latitude E5430 non-vPro     | [877bb1b29f](https://bsd-hardware.info/?probe=877bb1b29f) | Jan 10, 2022 |
| Unknown       | Unknown                     | [974e1f4e5e](https://bsd-hardware.info/?probe=974e1f4e5e) | Jan 07, 2022 |
| Toshiba       | Satellite C50-B             | [6b03a2c4c2](https://bsd-hardware.info/?probe=6b03a2c4c2) | Dec 22, 2021 |
| TOXIC by B... | 15CL872 1050TI              | [0a1683170a](https://bsd-hardware.info/?probe=0a1683170a) | Dec 20, 2021 |
| Lenovo        | ThinkPad A285 20MW000JMH    | [ff53f0763c](https://bsd-hardware.info/?probe=ff53f0763c) | Dec 12, 2021 |
| Apple         | MacBookAir1,1               | [61c7028e83](https://bsd-hardware.info/?probe=61c7028e83) | Dec 07, 2021 |
| TOXIC by B... | 15CL872 1050TI              | [4fbb430947](https://bsd-hardware.info/?probe=4fbb430947) | Dec 05, 2021 |
| Lenovo        | ThinkPad T430 2347G7G       | [66c64c1af9](https://bsd-hardware.info/?probe=66c64c1af9) | Nov 23, 2021 |
| Apple         | MacBookPro9,2               | [04cc56305c](https://bsd-hardware.info/?probe=04cc56305c) | Nov 11, 2021 |
| TUXEDO        | Pulse 15 Gen1               | [6f779d5170](https://bsd-hardware.info/?probe=6f779d5170) | Nov 03, 2021 |
| TUXEDO        | Pulse 15 Gen1               | [72f0937505](https://bsd-hardware.info/?probe=72f0937505) | Nov 02, 2021 |
| HP            | 625                         | [606d75e6a1](https://bsd-hardware.info/?probe=606d75e6a1) | Aug 11, 2021 |
| Unknown       | Unknown                     | [d4122c5eb0](https://bsd-hardware.info/?probe=d4122c5eb0) | Aug 03, 2021 |
| Lenovo        | ThinkPad X230 2325IG2       | [158ecc5e0b](https://bsd-hardware.info/?probe=158ecc5e0b) | Jul 14, 2021 |
| Lenovo        | Yoga 500-14IBD 80N4         | [9fda78d739](https://bsd-hardware.info/?probe=9fda78d739) | Jun 23, 2021 |
| Lenovo        | ThinkPad T440s 20ARS1B70... | [46dca136f6](https://bsd-hardware.info/?probe=46dca136f6) | Jun 21, 2021 |
| WYSE          | Z CLASS                     | [571fdbf390](https://bsd-hardware.info/?probe=571fdbf390) | Jun 19, 2021 |
| Lenovo        | ThinkPad T440s 20ARS1B70... | [9ae8146589](https://bsd-hardware.info/?probe=9ae8146589) | Jun 15, 2021 |
| Dell          | Latitude E4300              | [7855973957](https://bsd-hardware.info/?probe=7855973957) | Jun 12, 2021 |
| SLIMBOOK      | Unknown                     | [80a9ba918e](https://bsd-hardware.info/?probe=80a9ba918e) | Jun 11, 2021 |
| Notebook      | NL5xRU                      | [792fb07dd9](https://bsd-hardware.info/?probe=792fb07dd9) | May 10, 2021 |
| Lenovo        | ThinkPad T440s 20ARS1B70... | [b644ed3914](https://bsd-hardware.info/?probe=b644ed3914) | Mar 31, 2021 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | [4376accb5e](https://bsd-hardware.info/?probe=4376accb5e) | Mar 29, 2021 |
| Lenovo        | ThinkPad X230 23255Y4       | [ab871769f0](https://bsd-hardware.info/?probe=ab871769f0) | Mar 27, 2021 |
| Lenovo        | ThinkPad T440s 20ARS1B70... | [d856b5bf95](https://bsd-hardware.info/?probe=d856b5bf95) | Mar 23, 2021 |
| Dell          | Latitude E7270              | [5ba79f9aa5](https://bsd-hardware.info/?probe=5ba79f9aa5) | Mar 19, 2021 |
| Lenovo        | ThinkPad X280 20KESA000B    | [e2b586d597](https://bsd-hardware.info/?probe=e2b586d597) | Mar 17, 2021 |
| Lenovo        | ThinkPad X200s 7470W1V      | [926fe13d8f](https://bsd-hardware.info/?probe=926fe13d8f) | Mar 09, 2021 |
| ASUSTek       | X556UA                      | [57018edd10](https://bsd-hardware.info/?probe=57018edd10) | Mar 07, 2021 |
| Dell          | Latitude E4300              | [d5051ef185](https://bsd-hardware.info/?probe=d5051ef185) | Feb 16, 2021 |
| Lenovo        | G505s 20255                 | [8bfcff9039](https://bsd-hardware.info/?probe=8bfcff9039) | Feb 16, 2021 |
| Dell          | Latitude E4300              | [981de7fd20](https://bsd-hardware.info/?probe=981de7fd20) | Feb 14, 2021 |
| Apple         | MacBookPro8,1               | [8f93b4146d](https://bsd-hardware.info/?probe=8f93b4146d) | Feb 12, 2021 |
| Apple         | MacBookPro8,1               | [e74d76ecb3](https://bsd-hardware.info/?probe=e74d76ecb3) | Feb 12, 2021 |
| Dell          | Latitude 7280               | [defaee0e5c](https://bsd-hardware.info/?probe=defaee0e5c) | Feb 12, 2021 |
| Dell          | XPS 15 9560                 | [687008da4f](https://bsd-hardware.info/?probe=687008da4f) | Feb 11, 2021 |
| Dell          | Latitude 7280               | [d62b7120c8](https://bsd-hardware.info/?probe=d62b7120c8) | Feb 11, 2021 |
| Dell          | Latitude 7370               | [8ec8d28024](https://bsd-hardware.info/?probe=8ec8d28024) | Feb 08, 2021 |
| Dell          | Latitude E4300              | [84925c014a](https://bsd-hardware.info/?probe=84925c014a) | Feb 01, 2021 |
| HP            | EliteBook 2530p             | [1fd927e2cd](https://bsd-hardware.info/?probe=1fd927e2cd) | Jan 11, 2021 |
| Lenovo        | ThinkPad X250 20CLS4WV08    | [2808d1dd6a](https://bsd-hardware.info/?probe=2808d1dd6a) | Oct 20, 2020 |
| Lenovo        | ThinkPad X1 Carbon 5th 2... | [bee732e516](https://bsd-hardware.info/?probe=bee732e516) | Oct 19, 2020 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart_bsd/os_name.svg)


| Name                 | Notebooks | Percent |
|----------------------|-----------|---------|
| helloSystem 0.7.0    | 8         | 13.33%  |
| helloSystem 0.5.0    | 6         | 10%     |
| FreeBSD 13.0-STABLE  | 5         | 8.33%   |
| helloSystem 0.6.0    | 3         | 5%      |
| helloSystem 0.3.0    | 3         | 5%      |
| OPNsense 22.10       | 2         | 3.33%   |
| OpenBSD 7.1          | 2         | 3.33%   |
| OpenBSD 6.9          | 2         | 3.33%   |
| OpenBSD 6.8          | 2         | 3.33%   |
| helloSystem 0.4.0    | 2         | 3.33%   |
| GhostBSD 22.06.18    | 2         | 3.33%   |
| FreeBSD 13.1-p4      | 2         | 3.33%   |
| FreeBSD 13.1         | 2         | 3.33%   |
| FreeBSD 13.0-p5      | 2         | 3.33%   |
| OPNsense 22.7.4      | 1         | 1.67%   |
| OPNsense 22.7.2      | 1         | 1.67%   |
| OPNsense 22.7.10     | 1         | 1.67%   |
| OPNsense 22.1.7      | 1         | 1.67%   |
| OPNsense 22.1.6      | 1         | 1.67%   |
| OPNsense 22.1        | 1         | 1.67%   |
| OPNsense 21.7.7      | 1         | 1.67%   |
| OPNsense 21.1.9      | 1         | 1.67%   |
| OpenBSD 7.2          | 1         | 1.67%   |
| OpenBSD 7.0          | 1         | 1.67%   |
| helloSystem 0.8.0    | 1         | 1.67%   |
| FreeBSD 14.0-CURRENT | 1         | 1.67%   |
| FreeBSD 13.0-p2      | 1         | 1.67%   |
| FreeBSD 13.0-BETA1   | 1         | 1.67%   |
| FreeBSD 13.0         | 1         | 1.67%   |
| FreeBSD 12.2-p2      | 1         | 1.67%   |
| FreeBSD 12.2         | 1         | 1.67%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart_bsd/os_family.svg)


| Name        | Notebooks | Percent |
|-------------|-----------|---------|
| helloSystem | 22        | 40%     |
| FreeBSD     | 16        | 29.09%  |
| OpenBSD     | 8         | 14.55%  |
| OPNsense    | 7         | 12.73%  |
| GhostBSD    | 2         | 3.64%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart_bsd/os_arch.svg)


| Name  | Notebooks | Percent |
|-------|-----------|---------|
| amd64 | 55        | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart_bsd/os_de.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| helloDesktop | 24        | 43.64%  |
| Console      | 9         | 16.36%  |
| fvwm         | 5         | 9.09%   |
| MATE         | 4         | 7.27%   |
| GNOME        | 3         | 5.45%   |
| TWM          | 2         | 3.64%   |
| KDE5         | 2         | 3.64%   |
| i3           | 2         | 3.64%   |
| XFCE         | 1         | 1.82%   |
| LXQt         | 1         | 1.82%   |
| GNUstep      | 1         | 1.82%   |
| AwesomeWM    | 1         | 1.82%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart_bsd/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 46        | 83.64%  |
| Console | 8         | 14.55%  |
| Wayland | 1         | 1.82%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart_bsd/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| SLiM    | 25        | 45.45%  |
| Console | 19        | 34.55%  |
| XDM     | 4         | 7.27%   |
| LightDM | 3         | 5.45%   |
| SDDM    | 2         | 3.64%   |
| GDM     | 2         | 3.64%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart_bsd/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| en_US   | 27        | 49.09%  |
| C       | 13        | 23.64%  |
| Unknown | 12        | 21.82%  |
| nl_NL   | 1         | 1.82%   |
| fr_FR   | 1         | 1.82%   |
| en      | 1         | 1.82%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart_bsd/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 45        | 80.36%  |
| BIOS | 11        | 19.64%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart_bsd/os_filesystem.svg)


| Type   | Notebooks | Percent |
|--------|-----------|---------|
| Zfs    | 33        | 60%     |
| Ufs    | 8         | 14.55%  |
| Ffs    | 8         | 14.55%  |
| Cd9660 | 6         | 10.91%  |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart_bsd/os_part_scheme.svg)


| Type | Notebooks | Percent |
|------|-----------|---------|
| GPT  | 51        | 92.73%  |
| MBR  | 4         | 7.27%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart_bsd/node_vendor.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| Lenovo           | 19        | 34.55%  |
| Dell             | 8         | 14.55%  |
| Hewlett-Packard  | 4         | 7.27%   |
| Apple            | 4         | 7.27%   |
| Deciso           | 3         | 5.45%   |
| ASUSTek Computer | 3         | 5.45%   |
| Notebook         | 2         | 3.64%   |
| Acer             | 2         | 3.64%   |
| WYSE             | 1         | 1.82%   |
| TUXEDO           | 1         | 1.82%   |
| TOXIC by BTO     | 1         | 1.82%   |
| Toshiba          | 1         | 1.82%   |
| Star Labs        | 1         | 1.82%   |
| Sony             | 1         | 1.82%   |
| SLIMBOOK         | 1         | 1.82%   |
| Intel            | 1         | 1.82%   |
| Google           | 1         | 1.82%   |
| Unknown          | 1         | 1.82%   |

Model
-----

Motherboard model

![Model](./images/pie_chart_bsd/node_model.svg)


| Name                                     | Notebooks | Percent |
|------------------------------------------|-----------|---------|
| Dell Latitude E4300                      | 2         | 3.64%   |
| Deciso NetBoard-A10                      | 2         | 3.64%   |
| Unknown                                  | 2         | 3.64%   |
| WYSE Z CLASS                             | 1         | 1.82%   |
| TUXEDO Pulse 15 Gen1                     | 1         | 1.82%   |
| TOXIC by BTO 15CL872 1050TI              | 1         | 1.82%   |
| Toshiba Satellite C50-B                  | 1         | 1.82%   |
| Star Labs LabTop                         | 1         | 1.82%   |
| Sony SVZ1311C5E                          | 1         | 1.82%   |
| Notebook NS5x_NS7xPU                     | 1         | 1.82%   |
| Notebook NL5xRU                          | 1         | 1.82%   |
| Lenovo Yoga 500-14IBD 80N4               | 1         | 1.82%   |
| Lenovo ThinkPad X61s 76693KG             | 1         | 1.82%   |
| Lenovo ThinkPad X280 20KESA000B          | 1         | 1.82%   |
| Lenovo ThinkPad X250 20CLS5BU00          | 1         | 1.82%   |
| Lenovo ThinkPad X250 20CLS59400          | 1         | 1.82%   |
| Lenovo ThinkPad X250 20CLS4WV08          | 1         | 1.82%   |
| Lenovo ThinkPad X230 2325IG2             | 1         | 1.82%   |
| Lenovo ThinkPad X230 23255Y4             | 1         | 1.82%   |
| Lenovo ThinkPad X200s 7470W1V            | 1         | 1.82%   |
| Lenovo ThinkPad X1 Carbon 7th 20QDCTO1WW | 1         | 1.82%   |
| Lenovo ThinkPad X1 Carbon 5th 20HRCTO1WW | 1         | 1.82%   |
| Lenovo ThinkPad T490 20N2CTO1WW          | 1         | 1.82%   |
| Lenovo ThinkPad T440s 20ARS1B704         | 1         | 1.82%   |
| Lenovo ThinkPad T440 20B7S2LT00          | 1         | 1.82%   |
| Lenovo ThinkPad T430 2347G7G             | 1         | 1.82%   |
| Lenovo ThinkPad S1 Yoga 20CD0038MB       | 1         | 1.82%   |
| Lenovo ThinkPad A285 20MW000JMH          | 1         | 1.82%   |
| Lenovo IdeaPad 130-15AST 81H5            | 1         | 1.82%   |
| Lenovo G505s 20255                       | 1         | 1.82%   |
| Intel Milstead Platform                  | 1         | 1.82%   |
| HP EliteBook 8460p                       | 1         | 1.82%   |
| HP EliteBook 840 G3                      | 1         | 1.82%   |
| HP EliteBook 2530p                       | 1         | 1.82%   |
| HP 625                                   | 1         | 1.82%   |
| Google Cave                              | 1         | 1.82%   |
| Dell XPS 15 9560                         | 1         | 1.82%   |
| Dell Latitude E7270                      | 1         | 1.82%   |
| Dell Latitude E7240                      | 1         | 1.82%   |
| Dell Latitude E5430 non-vPro             | 1         | 1.82%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart_bsd/node_model_family.svg)


| Name                 | Notebooks | Percent |
|----------------------|-----------|---------|
| Lenovo ThinkPad      | 16        | 29.09%  |
| Dell Latitude        | 7         | 12.73%  |
| HP EliteBook         | 3         | 5.45%   |
| Deciso NetBoard-A10  | 2         | 3.64%   |
| Acer Aspire          | 2         | 3.64%   |
| Unknown              | 2         | 3.64%   |
| WYSE Z               | 1         | 1.82%   |
| TUXEDO Pulse         | 1         | 1.82%   |
| TOXIC by BTO 15CL872 | 1         | 1.82%   |
| Toshiba Satellite    | 1         | 1.82%   |
| Star Labs LabTop     | 1         | 1.82%   |
| Sony SVZ1311C5E      | 1         | 1.82%   |
| Notebook NS5x        | 1         | 1.82%   |
| Notebook NL5xRU      | 1         | 1.82%   |
| Lenovo Yoga          | 1         | 1.82%   |
| Lenovo IdeaPad       | 1         | 1.82%   |
| Lenovo G505s         | 1         | 1.82%   |
| Intel Milstead       | 1         | 1.82%   |
| HP 625               | 1         | 1.82%   |
| Google Cave          | 1         | 1.82%   |
| Dell XPS             | 1         | 1.82%   |
| Deciso OPNsense      | 1         | 1.82%   |
| ASUS X751LB          | 1         | 1.82%   |
| ASUS X556UA          | 1         | 1.82%   |
| ASUS K53TA           | 1         | 1.82%   |
| Apple MacBookPro9    | 1         | 1.82%   |
| Apple MacBookPro8    | 1         | 1.82%   |
| Apple MacBookPro10   | 1         | 1.82%   |
| Apple MacBookAir1    | 1         | 1.82%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart_bsd/node_year.svg)


| Year    | Notebooks | Percent |
|---------|-----------|---------|
| 2015    | 7         | 12.73%  |
| 2019    | 6         | 10.91%  |
| 2020    | 5         | 9.09%   |
| 2012    | 5         | 9.09%   |
| 2022    | 4         | 7.27%   |
| 2018    | 4         | 7.27%   |
| 2014    | 4         | 7.27%   |
| 2011    | 4         | 7.27%   |
| 2021    | 3         | 5.45%   |
| 2016    | 3         | 5.45%   |
| 2013    | 3         | 5.45%   |
| 2017    | 2         | 3.64%   |
| 2009    | 2         | 3.64%   |
| 2010    | 1         | 1.82%   |
| 2008    | 1         | 1.82%   |
| Unknown | 1         | 1.82%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart_bsd/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 55        | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart_bsd/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 54        | 98.18%  |
| Yes  | 1         | 1.82%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart_bsd/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 8.01-16.0   | 26        | 47.27%  |
| 4.01-8.0    | 13        | 23.64%  |
| 16.01-24.0  | 10        | 18.18%  |
| 32.01-64.0  | 3         | 5.45%   |
| 64.01-256.0 | 2         | 3.64%   |
| 2.01-3.0    | 1         | 1.82%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart_bsd/node_ram_used.svg)


| Used GB  | Notebooks | Percent |
|----------|-----------|---------|
| 0.01-0.5 | 33        | 57.89%  |
| 0.51-1.0 | 14        | 24.56%  |
| 1.01-2.0 | 7         | 12.28%  |
| 3.01-4.0 | 2         | 3.51%   |
| 2.01-3.0 | 1         | 1.75%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart_bsd/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 36        | 64.29%  |
| 2      | 14        | 25%     |
| 3      | 3         | 5.36%   |
| 0      | 3         | 5.36%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart_bsd/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 45        | 81.82%  |
| Yes       | 10        | 18.18%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart_bsd/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 47        | 85.45%  |
| No        | 8         | 14.55%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart_bsd/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 47        | 85.45%  |
| No        | 8         | 14.55%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart_bsd/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 34        | 61.82%  |
| No        | 21        | 38.18%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart_bsd/node_location.svg)


| Country     | Notebooks | Percent |
|-------------|-----------|---------|
| Netherlands | 55        | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart_bsd/node_city.svg)


| City                    | Notebooks | Percent |
|-------------------------|-----------|---------|
| Amsterdam               | 14        | 24.56%  |
| Utrecht                 | 5         | 8.77%   |
| Eindhoven               | 3         | 5.26%   |
| The Hague               | 2         | 3.51%   |
| Papendrecht             | 2         | 3.51%   |
| Oegstgeest              | 2         | 3.51%   |
| Hoogeveen               | 2         | 3.51%   |
| Groningen               | 2         | 3.51%   |
| 's-Hertogenbosch        | 2         | 3.51%   |
| Woerdense Verlaat       | 1         | 1.75%   |
| Warmond                 | 1         | 1.75%   |
| Tilburg                 | 1         | 1.75%   |
| Rozenburg               | 1         | 1.75%   |
| Roosendaal              | 1         | 1.75%   |
| Rhoon                   | 1         | 1.75%   |
| Ouderkerk aan de Amstel | 1         | 1.75%   |
| Oosterhout              | 1         | 1.75%   |
| Munnikens-Vinkel        | 1         | 1.75%   |
| Lent                    | 1         | 1.75%   |
| Leiden                  | 1         | 1.75%   |
| Leeuwarden              | 1         | 1.75%   |
| Hoek van Holland        | 1         | 1.75%   |
| Ede                     | 1         | 1.75%   |
| Dronten                 | 1         | 1.75%   |
| Diemen                  | 1         | 1.75%   |
| Deventer                | 1         | 1.75%   |
| Den Dolder              | 1         | 1.75%   |
| De Lutte                | 1         | 1.75%   |
| Cuijk                   | 1         | 1.75%   |
| Capelle aan den IJssel  | 1         | 1.75%   |
| Bergambacht             | 1         | 1.75%   |
| Alphen aan den Rijn     | 1         | 1.75%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart_bsd/drive_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 15        | 21     | 24.59%  |
| WDC                 | 7         | 7      | 11.48%  |
| Seagate             | 6         | 7      | 9.84%   |
| Transcend           | 4         | 5      | 6.56%   |
| Crucial             | 4         | 5      | 6.56%   |
| Toshiba             | 3         | 3      | 4.92%   |
| SanDisk             | 3         | 3      | 4.92%   |
| NVMe                | 3         | 4      | 4.92%   |
| Hitachi             | 2         | 2      | 3.28%   |
| Apple               | 2         | 2      | 3.28%   |
| Star Drive          | 1         | 1      | 1.64%   |
| SK hynix            | 1         | 1      | 1.64%   |
| OCZ                 | 1         | 1      | 1.64%   |
| LITEON              | 1         | 1      | 1.64%   |
| Leven               | 1         | 1      | 1.64%   |
| Kingston            | 1         | 1      | 1.64%   |
| Intel               | 1         | 1      | 1.64%   |
| HPE                 | 1         | 1      | 1.64%   |
| Hoodisk             | 1         | 2      | 1.64%   |
| HGST                | 1         | 1      | 1.64%   |
| Gigabyte Technology | 1         | 1      | 1.64%   |
| China               | 1         | 1      | 1.64%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart_bsd/drive_model.svg)


| Model                            | Notebooks | Percent |
|----------------------------------|-----------|---------|
| WDC WD5000LPVX-22V0TT0 500GB     | 2         | 3.23%   |
| Transcend TS256GMTE652T2 256GB   | 2         | 3.23%   |
| Seagate ST500LM000-SSHD-8GB      | 2         | 3.23%   |
| WDC WDS500G2B0C-00PXH0 500GB     | 1         | 1.61%   |
| WDC WDS100T2B0B-00YS70 1TB       | 1         | 1.61%   |
| WDC WD15EARS-00Z5B1 1.5TB        | 1         | 1.61%   |
| WDC WD10SPZX-24Z10 1TB           | 1         | 1.61%   |
| WDC WD10SPZX-00Z10T0 1TB         | 1         | 1.61%   |
| Transcend TS512GMTS430S 512GB    | 1         | 1.61%   |
| Transcend TS128GMTE110S 128GB    | 1         | 1.61%   |
| Toshiba THNSN5512GPUK NVMe 512GB | 1         | 1.61%   |
| Toshiba THNSFJ256GCSU 256GB      | 1         | 1.61%   |
| Toshiba MQ04ABF100 1TB           | 1         | 1.61%   |
| Star Drive PCIe SSD 1TB          | 1         | 1.61%   |
| SK hynix SC311 SATA 256GB        | 1         | 1.61%   |
| Seagate ST9250410AS 250GB        | 1         | 1.61%   |
| Seagate ST9160412ASG 160GB       | 1         | 1.61%   |
| Seagate ST500VT000-1DK142 500GB  | 1         | 1.61%   |
| Seagate ST1000LM049-2GH172 1TB   | 1         | 1.61%   |
| SanDisk SD8SBAT256G1002 256GB    | 1         | 1.61%   |
| SanDisk SD7UB3Q256G1001 256GB    | 1         | 1.61%   |
| SanDisk SD6SB1M064G 64GB         | 1         | 1.61%   |
| Samsung SSD PM851 mSATA 512GB    | 1         | 1.61%   |
| Samsung SSD 980 PRO 1TB          | 1         | 1.61%   |
| Samsung SSD 970 PRO 512GB        | 1         | 1.61%   |
| Samsung SSD 970 EVO 500GB        | 1         | 1.61%   |
| Samsung SSD 870 QVO 1TB          | 1         | 1.61%   |
| Samsung SSD 860 EVO 1TB          | 1         | 1.61%   |
| Samsung SSD 850 EVO 500GB        | 1         | 1.61%   |
| Samsung SSD 850 EVO 250GB        | 1         | 1.61%   |
| Samsung SSD 840 EVO 250GB        | 1         | 1.61%   |
| Samsung SSD 840 EVO 120GB        | 1         | 1.61%   |
| Samsung SSD 830 Series 64GB      | 1         | 1.61%   |
| Samsung MZVLB1T0HBLR-000L7 1TB   | 1         | 1.61%   |
| Samsung MZRPC256HADR-000SO 128GB | 1         | 1.61%   |
| Samsung MZNLN256HCHP-000H1 256GB | 1         | 1.61%   |
| Samsung MZ7TD256HAFV-000L9 256GB | 1         | 1.61%   |
| Samsung HS082HB 80GB             | 1         | 1.61%   |
| OCZ VERTEX PLUS 64GB             | 1         | 1.61%   |
| NVMe Samsung SSD 980 1TB         | 1         | 1.61%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart_bsd/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 6         | 7      | 37.5%   |
| WDC                 | 5         | 5      | 31.25%  |
| Hitachi             | 2         | 2      | 12.5%   |
| Toshiba             | 1         | 1      | 6.25%   |
| Samsung Electronics | 1         | 1      | 6.25%   |
| HGST                | 1         | 1      | 6.25%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart_bsd/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 10        | 15     | 30.3%   |
| Crucial             | 4         | 5      | 12.12%  |
| SanDisk             | 3         | 3      | 9.09%   |
| NVMe                | 3         | 4      | 9.09%   |
| Apple               | 2         | 2      | 6.06%   |
| WDC                 | 1         | 1      | 3.03%   |
| Transcend           | 1         | 2      | 3.03%   |
| Toshiba             | 1         | 1      | 3.03%   |
| SK hynix            | 1         | 1      | 3.03%   |
| OCZ                 | 1         | 1      | 3.03%   |
| LITEON              | 1         | 1      | 3.03%   |
| Leven               | 1         | 1      | 3.03%   |
| HPE                 | 1         | 1      | 3.03%   |
| Hoodisk             | 1         | 2      | 3.03%   |
| Gigabyte Technology | 1         | 1      | 3.03%   |
| China               | 1         | 1      | 3.03%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart_bsd/drive_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SSD  | 30        | 42     | 51.72%  |
| HDD  | 16        | 17     | 27.59%  |
| NVMe | 12        | 13     | 20.69%  |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart_bsd/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 43        | 59     | 78.18%  |
| NVMe | 12        | 13     | 21.82%  |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart_bsd/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 33        | 43     | 71.74%  |
| 0.51-1.0   | 12        | 15     | 26.09%  |
| 1.01-2.0   | 1         | 1      | 2.17%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart_bsd/drive_space_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 101-250    | 15        | 26.79%  |
| 1-20       | 14        | 25%     |
| 251-500    | 13        | 23.21%  |
| 501-1000   | 6         | 10.71%  |
| 51-100     | 5         | 8.93%   |
| 21-50      | 1         | 1.79%   |
| 1001-2000  | 1         | 1.79%   |
| Unknown    | 1         | 1.79%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart_bsd/drive_space_used.svg)


| Used GB  | Notebooks | Percent |
|----------|-----------|---------|
| 1-20     | 46        | 83.64%  |
| 251-500  | 2         | 3.64%   |
| 21-50    | 2         | 3.64%   |
| 51-100   | 2         | 3.64%   |
| 101-250  | 1         | 1.82%   |
| 501-1000 | 1         | 1.82%   |
| Unknown  | 1         | 1.82%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart_bsd/drive_malfunc.svg)


| Model                            | Notebooks | Drives | Percent |
|----------------------------------|-----------|--------|---------|
| WDC WD15EARS-00Z5B1 1.5TB        | 1         | 1      | 20%     |
| SanDisk SD7UB3Q256G1001 256GB    | 1         | 1      | 20%     |
| Samsung Electronics HS082HB 80GB | 1         | 1      | 20%     |
| Hitachi HTS545032B9A300 320GB    | 1         | 1      | 20%     |
| China SH00M128GB                 | 1         | 1      | 20%     |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart_bsd/drive_malfunc_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 1         | 1      | 20%     |
| SanDisk             | 1         | 1      | 20%     |
| Samsung Electronics | 1         | 1      | 20%     |
| Hitachi             | 1         | 1      | 20%     |
| China               | 1         | 1      | 20%     |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart_bsd/drive_malfunc_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 1         | 1      | 33.33%  |
| Samsung Electronics | 1         | 1      | 33.33%  |
| Hitachi             | 1         | 1      | 33.33%  |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart_bsd/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 3         | 3      | 60%     |
| SSD  | 2         | 2      | 40%     |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart_bsd/drive_failed.svg)


| Model                   | Notebooks | Drives | Percent |
|-------------------------|-----------|--------|---------|
| HPE MK000480GWUGF 480GB | 1         | 1      | 100%    |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart_bsd/drive_failed_vendor.svg)


| Vendor | Notebooks | Drives | Percent |
|--------|-----------|--------|---------|
| HPE    | 1         | 1      | 100%    |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart_bsd/drive_status.svg)


| Status   | Notebooks | Drives | Percent |
|----------|-----------|--------|---------|
| Works    | 45        | 60     | 81.82%  |
| Malfunc  | 5         | 5      | 9.09%   |
| Detected | 4         | 6      | 7.27%   |
| Failed   | 1         | 1      | 1.82%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart_bsd/storage_vendor.svg)


| Vendor                      | Notebooks | Percent |
|-----------------------------|-----------|---------|
| Intel                       | 37        | 61.67%  |
| AMD                         | 10        | 16.67%  |
| Samsung Electronics         | 6         | 10%     |
| Transcend                   | 3         | 5%      |
| Toshiba                     | 1         | 1.67%   |
| SanDisk                     | 1         | 1.67%   |
| Phison Electronics          | 1         | 1.67%   |
| Kingston Technology Company | 1         | 1.67%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart_bsd/storage_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                          | 8         | 12.31%  |
| Intel 82801 Mobile SATA Controller [RAID mode]                               | 6         | 9.23%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                           | 5         | 7.69%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]             | 5         | 7.69%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                | 4         | 6.15%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                 | 4         | 6.15%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                           | 3         | 4.62%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]        | 3         | 4.62%   |
| Unknown                                                                      | 3         | 4.62%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                               | 2         | 3.08%   |
| Intel SSD Pro 7600p/760p/E 6100p Series                                      | 2         | 3.08%   |
| Intel Comet Lake SATA AHCI Controller                                        | 2         | 3.08%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                | 2         | 3.08%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                             | 2         | 3.08%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller | 2         | 3.08%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                            | 2         | 3.08%   |
| Toshiba XG4 NVMe SSD Controller                                              | 1         | 1.54%   |
| SanDisk WD Blue SN550 NVMe SSD                                               | 1         | 1.54%   |
| Phison E12 NVMe Controller                                                   | 1         | 1.54%   |
| Kingston Company A2000 NVMe SSD                                              | 1         | 1.54%   |
| Intel Mobile 4 Series Chipset PT IDER Controller                             | 1         | 1.54%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                        | 1         | 1.54%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                            | 1         | 1.54%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                       | 1         | 1.54%   |
| Intel 82801JI (ICH10 Family) SATA AHCI Controller                            | 1         | 1.54%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 2 port SATA Controller [IDE mode]         | 1         | 1.54%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart_bsd/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 40        | 61.54%  |
| NVMe | 15        | 23.08%  |
| RAID | 6         | 9.23%   |
| IDE  | 4         | 6.15%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart_bsd/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 42        | 76.36%  |
| AMD    | 13        | 23.64%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart_bsd/cpu_model.svg)


| Model                                   | Notebooks | Percent |
|-----------------------------------------|-----------|---------|
| AMD Ryzen Embedded V1500B               | 3         | 5.45%   |
| Intel Core i7-7600U CPU @ 2.80GHz       | 2         | 3.64%   |
| Intel Core i7-4600U CPU @ 2.10GHz       | 2         | 3.64%   |
| Intel Core i7-3520M CPU @ 2.90GHz       | 2         | 3.64%   |
| Intel Core i5-5300U CPU @ 2.30GHz       | 2         | 3.64%   |
| Intel Core i5-3210M CPU @ 2.50GHz       | 2         | 3.64%   |
| Intel Core 2 Duo                        | 2         | 3.64%   |
| AMD E1-2500 APU with Radeon HD Graphics | 2         | 3.64%   |
| Intel Pentium CPU N3530 @ 2.16GHz       | 1         | 1.82%   |
| Intel Core m7-6Y75 CPU @ 1.20GHz        | 1         | 1.82%   |
| Intel Core m3-6Y30 CPU @ 0.90GHz        | 1         | 1.82%   |
| Intel Core i7-8750H CPU @ 2.20GHz       | 1         | 1.82%   |
| Intel Core i7-8665U CPU @ 1.90GHz       | 1         | 1.82%   |
| Intel Core i7-8565U CPU @ 1.80GHz       | 1         | 1.82%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz      | 1         | 1.82%   |
| Intel Core i7-6500U CPU @ 2.50GHz       | 1         | 1.82%   |
| Intel Core i7-5600U CPU @ 2.60GHz       | 1         | 1.82%   |
| Intel Core i7-5500U CPU @ 2.40GHz       | 1         | 1.82%   |
| Intel Core i7-4500U CPU @ 1.80GHz       | 1         | 1.82%   |
| Intel Core i7-3615QM CPU @ 2.30GHz      | 1         | 1.82%   |
| Intel Core i7-3612QM CPU @ 2.10GHz      | 1         | 1.82%   |
| Intel Core i7-10710U CPU @ 1.10GHz      | 1         | 1.82%   |
| Intel Core i5-8350U CPU @ 1.70GHz       | 1         | 1.82%   |
| Intel Core i5-6300U CPU @ 2.40GHz       | 1         | 1.82%   |
| Intel Core i5-6200U CPU @ 2.30GHz       | 1         | 1.82%   |
| Intel Core i5-4200U CPU @ 1.60GHz       | 1         | 1.82%   |
| Intel Core i5-3320M CPU @ 2.60GHz       | 1         | 1.82%   |
| Intel Core i5-2520M CPU @ 2.50GHz       | 1         | 1.82%   |
| Intel Core i5-2435M CPU @ 2.40GHz       | 1         | 1.82%   |
| Intel Core i5-10210U CPU @ 1.60GHz      | 1         | 1.82%   |
| Intel Core i3-5005U CPU @ 2.00GHz       | 1         | 1.82%   |
| Intel Core 2 Duo CPU P7500 @ 1.60GHz    | 1         | 1.82%   |
| Intel Core 2 Duo CPU L9400 @ 1.86GHz    | 1         | 1.82%   |
| Intel Core 2 Duo CPU L9300 @ 1.60GHz    | 1         | 1.82%   |
| Intel Core 2 Duo CPU L7500 @ 1.60GHz    | 1         | 1.82%   |
| Intel Celeron 2955U @ 1.40GHz           | 1         | 1.82%   |
| Intel Atom CPU D2550 @ 1.86GHz          | 1         | 1.82%   |
| Intel 12th Gen Core i7-1260P            | 1         | 1.82%   |
| AMD Ryzen 7 4800H with Radeon Graphics  | 1         | 1.82%   |
| AMD Ryzen 7 4700U with Radeon Graphics  | 1         | 1.82%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart_bsd/cpu_family.svg)


| Model              | Notebooks | Percent |
|--------------------|-----------|---------|
| Intel Core i7      | 17        | 30.91%  |
| Intel Core i5      | 12        | 21.82%  |
| Intel Core 2 Duo   | 6         | 10.91%  |
| AMD Ryzen Embedded | 3         | 5.45%   |
| AMD Ryzen 7        | 2         | 3.64%   |
| AMD E1             | 2         | 3.64%   |
| Other              | 1         | 1.82%   |
| Intel Pentium      | 1         | 1.82%   |
| Intel Core m7      | 1         | 1.82%   |
| Intel Core m3      | 1         | 1.82%   |
| Intel Core i3      | 1         | 1.82%   |
| Intel Celeron      | 1         | 1.82%   |
| Intel Atom         | 1         | 1.82%   |
| AMD Ryzen 5 PRO    | 1         | 1.82%   |
| AMD G              | 1         | 1.82%   |
| AMD E2             | 1         | 1.82%   |
| AMD Athlon II      | 1         | 1.82%   |
| AMD A8             | 1         | 1.82%   |
| AMD A6             | 1         | 1.82%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart_bsd/cpu_cores.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 32        | 58.18%  |
| 4       | 10        | 18.18%  |
| 8       | 6         | 10.91%  |
| Unknown | 4         | 7.27%   |
| 6       | 2         | 3.64%   |
| 16      | 1         | 1.82%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart_bsd/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 54        | 98.18%  |
| 2      | 1         | 1.82%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart_bsd/cpu_threads.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 34        | 61.82%  |
| 1       | 17        | 30.91%  |
| Unknown | 4         | 7.27%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart_bsd/cpu_microarch.svg)


| Name        | Notebooks | Percent |
|-------------|-----------|---------|
| KabyLake    | 8         | 14.55%  |
| IvyBridge   | 7         | 12.73%  |
| Skylake     | 5         | 9.09%   |
| Haswell     | 5         | 9.09%   |
| Broadwell   | 5         | 9.09%   |
| Zen         | 4         | 7.27%   |
| Penryn      | 4         | 7.27%   |
| Zen 2       | 2         | 3.64%   |
| SandyBridge | 2         | 3.64%   |
| Jaguar      | 2         | 3.64%   |
| Core        | 2         | 3.64%   |
| Silvermont  | 1         | 1.82%   |
| Piledriver  | 1         | 1.82%   |
| K10 Llano   | 1         | 1.82%   |
| K10         | 1         | 1.82%   |
| Excavator   | 1         | 1.82%   |
| CometLake   | 1         | 1.82%   |
| Bonnell     | 1         | 1.82%   |
| Bobcat      | 1         | 1.82%   |
| Unknown     | 1         | 1.82%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart_bsd/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 41        | 71.93%  |
| AMD    | 11        | 19.3%   |
| Nvidia | 5         | 8.77%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart_bsd/gpu_model.svg)


| Model                                                                     | Notebooks | Percent |
|---------------------------------------------------------------------------|-----------|---------|
| Intel 3rd Gen Core processor Graphics Controller                          | 7         | 11.48%  |
| Intel HD Graphics 5500                                                    | 5         | 8.2%    |
| Intel Haswell-ULT Integrated Graphics Controller                          | 5         | 8.2%    |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller              | 4         | 6.56%   |
| Intel Skylake GT2 [HD Graphics 520]                                       | 3         | 4.92%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                | 2         | 3.28%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)       | 2         | 3.28%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)         | 2         | 3.28%   |
| Intel HD Graphics 620                                                     | 2         | 3.28%   |
| Intel HD Graphics 515                                                     | 2         | 3.28%   |
| AMD Renoir                                                                | 2         | 3.28%   |
| AMD Kabini [Radeon HD 8240 / R3 Series]                                   | 2         | 3.28%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                | 1         | 1.64%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                   | 1         | 1.64%   |
| Nvidia GM108M [GeForce 940M]                                              | 1         | 1.64%   |
| Nvidia GK107M [GeForce GT 650M Mac Edition]                               | 1         | 1.64%   |
| Nvidia GF108M [NVS 5400M]                                                 | 1         | 1.64%   |
| Intel UHD Graphics 620                                                    | 1         | 1.64%   |
| Intel HD Graphics 630                                                     | 1         | 1.64%   |
| Intel CometLake-U GT2 [UHD Graphics]                                      | 1         | 1.64%   |
| Intel Comet Lake UHD Graphics                                             | 1         | 1.64%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                 | 1         | 1.64%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display              | 1         | 1.64%   |
| Intel Atom Processor D2xxx/N2xxx Integrated Graphics Controller           | 1         | 1.64%   |
| Intel Alder Lake-P Integrated Graphics Controller                         | 1         | 1.64%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller | 1         | 1.64%   |
| AMD Wrestler [Radeon HD 6310]                                             | 1         | 1.64%   |
| AMD Whistler [Radeon HD 6630M/6650M/6750M/7670M/7690M]                    | 1         | 1.64%   |
| AMD Trinity [Radeon HD 7640G]                                             | 1         | 1.64%   |
| AMD Sun PRO [Radeon HD 8570A/8570M]                                       | 1         | 1.64%   |
| AMD Sumo [Radeon HD 6520G]                                                | 1         | 1.64%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                  | 1         | 1.64%   |
| AMD Seymour [Radeon HD 6400M/7400M Series]                                | 1         | 1.64%   |
| AMD RS880M [Mobility Radeon HD 4225/4250]                                 | 1         | 1.64%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]          | 1         | 1.64%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart_bsd/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 31        | 55.36%  |
| 1 x AMD        | 9         | 16.07%  |
| 2 x Intel      | 6         | 10.71%  |
| Intel + Nvidia | 4         | 7.14%   |
| Other          | 3         | 5.36%   |
| 2 x AMD        | 2         | 3.57%   |
| 1 x Nvidia     | 1         | 1.79%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart_bsd/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 51        | 91.07%  |
| Unknown     | 3         | 5.36%   |
| Proprietary | 2         | 3.57%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart_bsd/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 47        | 83.93%  |
| 0.01-0.5   | 6         | 10.71%  |
| 0.51-1.0   | 2         | 3.57%   |
| 1.01-2.0   | 1         | 1.79%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart_bsd/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| LG Display              | 11        | 25%     |
| Chimei Innolux          | 7         | 15.91%  |
| BOE                     | 5         | 11.36%  |
| AU Optronics            | 5         | 11.36%  |
| Samsung Electronics     | 4         | 9.09%   |
| Apple                   | 3         | 6.82%   |
| Sharp                   | 2         | 4.55%   |
| Lenovo                  | 2         | 4.55%   |
| Sony                    | 1         | 2.27%   |
| Philips                 | 1         | 2.27%   |
| PANDA                   | 1         | 2.27%   |
| Chi Mei Optoelectronics | 1         | 2.27%   |
| AOC                     | 1         | 2.27%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart_bsd/mon_model.svg)


| Model                                                                    | Notebooks | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| LG Display LCD Monitor LGD11F9 1280x800 290x180mm 13.4-inch              | 2         | 4.55%   |
| Sony LCD SNY06FA 1600x900 290x160mm 13.0-inch                            | 1         | 2.27%   |
| Sharp LCD Monitor SHP1461 3200x1800 290x170mm 13.2-inch                  | 1         | 2.27%   |
| Sharp LCD Monitor SHP1453 1920x1080 350x190mm 15.7-inch                  | 1         | 2.27%   |
| Samsung Electronics LCD Monitor SEC4541 1280x800 260x160mm 12.0-inch     | 1         | 2.27%   |
| Samsung Electronics LCD Monitor SEC324C 1600x900 310x170mm 13.9-inch     | 1         | 2.27%   |
| Samsung Electronics LCD Monitor SEC3047 1366x768 280x160mm 12.7-inch     | 1         | 2.27%   |
| Samsung Electronics LCD Monitor SDC4347 1366x768 340x190mm 15.3-inch     | 1         | 2.27%   |
| Philips PHL 328E1 PHLC204 3840x2160 700x390mm 31.5-inch                  | 1         | 2.27%   |
| PANDA LC133LF1L02 NCP0019 1920x1080 290x170mm 13.2-inch                  | 1         | 2.27%   |
| LG Display LCD Monitor LGD05C0 1920x1080 344x194mm 15.5-inch             | 1         | 2.27%   |
| LG Display LCD Monitor LGD058B 2560x1440 310x170mm 13.9-inch             | 1         | 2.27%   |
| LG Display LCD Monitor LGD0450 1366x768 280x160mm 12.7-inch              | 1         | 2.27%   |
| LG Display LCD Monitor LGD0437 1920x1080 280x160mm 12.7-inch             | 1         | 2.27%   |
| LG Display LCD Monitor LGD0414 1920x1080 280x160mm 12.7-inch             | 1         | 2.27%   |
| LG Display LCD Monitor LGD0408 1920x1080 280x160mm 12.7-inch             | 1         | 2.27%   |
| LG Display LCD Monitor LGD03ED 1366x768 280x160mm 12.7-inch              | 1         | 2.27%   |
| LG Display LCD Monitor LGD02D8 1366x768 280x160mm 12.7-inch              | 1         | 2.27%   |
| LG Display LCD Monitor LGD02AD 1366x768 340x190mm 15.3-inch              | 1         | 2.27%   |
| Lenovo LCD Monitor LEN4010 1280x800 260x160mm 12.0-inch                  | 1         | 2.27%   |
| Lenovo LCD Monitor LEN4000 1024x768 250x180mm 12.1-inch                  | 1         | 2.27%   |
| Chimei Innolux LCD Monitor CMN1734 1600x900 380x210mm 17.1-inch          | 1         | 2.27%   |
| Chimei Innolux LCD Monitor CMN15C9 1366x768 340x190mm 15.3-inch          | 1         | 2.27%   |
| Chimei Innolux LCD Monitor CMN15BF 1366x768 340x190mm 15.3-inch          | 1         | 2.27%   |
| Chimei Innolux LCD Monitor CMN15B5 1366x768 340x190mm 15.3-inch          | 1         | 2.27%   |
| Chimei Innolux LCD Monitor CMN1490 1366x768 310x170mm 13.9-inch          | 1         | 2.27%   |
| Chimei Innolux LCD Monitor CMN1404 1920x1080 310x170mm 13.9-inch         | 1         | 2.27%   |
| Chimei Innolux LCD Monitor CMN1239 1920x1080 280x160mm 12.7-inch         | 1         | 2.27%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A7 1366x768 350x190mm 15.7-inch | 1         | 2.27%   |
| BOE LCD Monitor BOE07F7 1920x1080 310x170mm 13.9-inch                    | 1         | 2.27%   |
| BOE LCD Monitor BOE07D8 1920x1080 340x190mm 15.3-inch                    | 1         | 2.27%   |
| BOE LCD Monitor BOE07C8 3840x2160 310x170mm 13.9-inch                    | 1         | 2.27%   |
| BOE LCD Monitor BOE06BF 1920x1080 280x160mm 12.7-inch                    | 1         | 2.27%   |
| BOE LCD Monitor BOE0675 1366x768 340x190mm 15.3-inch                     | 1         | 2.27%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 340x190mm 15.3-inch           | 1         | 2.27%   |
| AU Optronics LCD Monitor AUO313E 1600x900 310x170mm 13.9-inch            | 1         | 2.27%   |
| AU Optronics LCD Monitor AUO226D 1920x1080 280x160mm 12.7-inch           | 1         | 2.27%   |
| AU Optronics LCD Monitor AUO2036 2560x1440 310x170mm 13.9-inch           | 1         | 2.27%   |
| AU Optronics LCD Monitor AUO106C 1366x768 280x160mm 12.7-inch            | 1         | 2.27%   |
| Apple LCD Monitor APP9CC3 1280x800 290x180mm 13.4-inch                   | 1         | 2.27%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart_bsd/mon_resolution.svg)


| Resolution       | Notebooks | Percent |
|------------------|-----------|---------|
| 1920x1080 (FHD)  | 14        | 31.82%  |
| 1366x768 (WXGA)  | 13        | 29.55%  |
| 1280x800 (WXGA)  | 7         | 15.91%  |
| 1600x900 (HD+)   | 4         | 9.09%   |
| 3840x2160 (4K)   | 3         | 6.82%   |
| 2560x1440 (QHD)  | 2         | 4.55%   |
| 3200x1800 (QHD+) | 1         | 2.27%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart_bsd/mon_diagonal.svg)


| Inches | Notebooks | Percent |
|--------|-----------|---------|
| 13     | 16        | 36.36%  |
| 12     | 13        | 29.55%  |
| 15     | 11        | 25%     |
| 31     | 1         | 2.27%   |
| 27     | 1         | 2.27%   |
| 23     | 1         | 2.27%   |
| 17     | 1         | 2.27%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart_bsd/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 201-300     | 21        | 47.73%  |
| 301-350     | 19        | 43.18%  |
| 601-700     | 2         | 4.55%   |
| 501-600     | 1         | 2.27%   |
| 351-400     | 1         | 2.27%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart_bsd/mon_ratio.svg)


| Ratio | Notebooks | Percent |
|-------|-----------|---------|
| 16/9  | 36        | 83.72%  |
| 16/10 | 6         | 13.95%  |
| 3/2   | 1         | 2.33%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart_bsd/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 81-90          | 13        | 29.55%  |
| 61-70          | 13        | 29.55%  |
| 91-100         | 8         | 18.18%  |
| 71-80          | 3         | 6.82%   |
| 101-110        | 3         | 6.82%   |
| 351-500        | 1         | 2.27%   |
| 301-350        | 1         | 2.27%   |
| 201-250        | 1         | 2.27%   |
| 121-130        | 1         | 2.27%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart_bsd/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 17        | 39.53%  |
| 101-120       | 13        | 30.23%  |
| 161-240       | 9         | 20.93%  |
| More than 240 | 2         | 4.65%   |
| 51-100        | 2         | 4.65%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart_bsd/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 43        | 78.18%  |
| 0     | 11        | 20%     |
| 2     | 1         | 1.82%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart_bsd/net_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 41        | 48.24%  |
| Realtek Semiconductor             | 19        | 22.35%  |
| Broadcom                          | 7         | 8.24%   |
| Qualcomm Atheros                  | 6         | 7.06%   |
| AMD                               | 3         | 3.53%   |
| TP-Link                           | 2         | 2.35%   |
| Sierra Wireless                   | 1         | 1.18%   |
| Ralink Technology                 | 1         | 1.18%   |
| Ralink                            | 1         | 1.18%   |
| HMD Global                        | 1         | 1.18%   |
| Hewlett-Packard                   | 1         | 1.18%   |
| Fibocom                           | 1         | 1.18%   |
| Ericsson Business Mobile Networks | 1         | 1.18%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart_bsd/net_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 12        | 10.91%  |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 5         | 4.55%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter               | 4         | 3.64%   |
| Intel Wireless 7265                                               | 4         | 3.64%   |
| Intel Wireless 7260                                               | 4         | 3.64%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 4         | 3.64%   |
| Intel 82567LM Gigabit Network Connection                          | 4         | 3.64%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 3         | 2.73%   |
| Intel Wireless 8265 / 8275                                        | 3         | 2.73%   |
| Intel Wi-Fi 6 AX200                                               | 3         | 2.73%   |
| Intel I211 Gigabit Network Connection                             | 3         | 2.73%   |
| Intel Ethernet Connection (3) I218-LM                             | 3         | 2.73%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 3         | 2.73%   |
| Broadcom BCM4331 802.11a/b/g/n                                    | 3         | 2.73%   |
| AMD Family 17h Processor 10 Gb Ethernet Controller Port 0         | 3         | 2.73%   |
| Intel Wireless-AC 9260                                            | 2         | 1.82%   |
| Intel Wireless 8260                                               | 2         | 1.82%   |
| Intel WiFi Link 5100                                              | 2         | 1.82%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection           | 2         | 1.82%   |
| Intel Ethernet Connection I218-LM                                 | 2         | 1.82%   |
| Intel Ethernet Connection (4) I219-LM                             | 2         | 1.82%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 2         | 1.82%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 2         | 1.82%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 2         | 1.82%   |
| TP-Link TP-LINK Wireless USB Adapter                              | 1         | 0.91%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]        | 1         | 0.91%   |
| Sierra Wireless EM7455                                            | 1         | 0.91%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 1         | 0.91%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                           | 1         | 0.91%   |
| Ralink RT5370 Wireless Adapter                                    | 1         | 0.91%   |
| Ralink RT3592 Wireless 802.11abgn 2T/2R PCIe                      | 1         | 0.91%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                            | 1         | 0.91%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 1         | 0.91%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 1         | 0.91%   |
| Intel Wireless 3160                                               | 1         | 0.91%   |
| Intel I210 Gigabit Network Connection                             | 1         | 0.91%   |
| Intel Ethernet Connection I219-V                                  | 1         | 0.91%   |
| Intel Ethernet Connection I219-LM                                 | 1         | 0.91%   |
| Intel Ethernet Connection I218-V                                  | 1         | 0.91%   |
| Intel Ethernet Connection (6) I219-V                              | 1         | 0.91%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart_bsd/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 33        | 58.93%  |
| Realtek Semiconductor | 6         | 10.71%  |
| Qualcomm Atheros      | 6         | 10.71%  |
| Broadcom              | 6         | 10.71%  |
| TP-Link               | 2         | 3.57%   |
| Sierra Wireless       | 1         | 1.79%   |
| Ralink Technology     | 1         | 1.79%   |
| Ralink                | 1         | 1.79%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart_bsd/net_wireless_model.svg)


| Model                                                          | Notebooks | Percent |
|----------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 5         | 8.93%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter            | 4         | 7.14%   |
| Intel Wireless 7265                                            | 4         | 7.14%   |
| Intel Wireless 7260                                            | 4         | 7.14%   |
| Intel Wireless 8265 / 8275                                     | 3         | 5.36%   |
| Intel Wi-Fi 6 AX200                                            | 3         | 5.36%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 3         | 5.36%   |
| Broadcom BCM4331 802.11a/b/g/n                                 | 3         | 5.36%   |
| Intel Wireless-AC 9260                                         | 2         | 3.57%   |
| Intel Wireless 8260                                            | 2         | 3.57%   |
| Intel WiFi Link 5100                                           | 2         | 3.57%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection        | 2         | 3.57%   |
| Intel Comet Lake PCH-LP CNVi WiFi                              | 2         | 3.57%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                       | 2         | 3.57%   |
| TP-Link TP-LINK Wireless USB Adapter                           | 1         | 1.79%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]     | 1         | 1.79%   |
| Sierra Wireless EM7455                                         | 1         | 1.79%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 1         | 1.79%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                        | 1         | 1.79%   |
| Ralink RT5370 Wireless Adapter                                 | 1         | 1.79%   |
| Ralink RT3592 Wireless 802.11abgn 2T/2R PCIe                   | 1         | 1.79%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 1         | 1.79%   |
| Intel Wireless 3160                                            | 1         | 1.79%   |
| Intel Centrino Ultimate-N 6300                                 | 1         | 1.79%   |
| Intel Centrino Advanced-N 6235                                 | 1         | 1.79%   |
| Intel Cannon Lake PCH CNVi WiFi                                | 1         | 1.79%   |
| Broadcom BCM4321 802.11a/b/g/n                                 | 1         | 1.79%   |
| Broadcom BCM43142 802.11b/g/n                                  | 1         | 1.79%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter            | 1         | 1.79%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart_bsd/net_ethernet_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 26        | 50.98%  |
| Realtek Semiconductor | 15        | 29.41%  |
| Broadcom              | 4         | 7.84%   |
| AMD                   | 3         | 5.88%   |
| Qualcomm Atheros      | 2         | 3.92%   |
| HMD Global            | 1         | 1.96%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart_bsd/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 12        | 23.53%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 4         | 7.84%   |
| Intel 82567LM Gigabit Network Connection                          | 4         | 7.84%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 3         | 5.88%   |
| Intel I211 Gigabit Network Connection                             | 3         | 5.88%   |
| Intel Ethernet Connection (3) I218-LM                             | 3         | 5.88%   |
| AMD Family 17h Processor 10 Gb Ethernet Controller Port 0         | 3         | 5.88%   |
| Intel Ethernet Connection I218-LM                                 | 2         | 3.92%   |
| Intel Ethernet Connection (4) I219-LM                             | 2         | 3.92%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 2         | 3.92%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                            | 1         | 1.96%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 1         | 1.96%   |
| Intel I210 Gigabit Network Connection                             | 1         | 1.96%   |
| Intel Ethernet Connection I219-V                                  | 1         | 1.96%   |
| Intel Ethernet Connection I219-LM                                 | 1         | 1.96%   |
| Intel Ethernet Connection I218-V                                  | 1         | 1.96%   |
| Intel Ethernet Connection (6) I219-V                              | 1         | 1.96%   |
| Intel Ethernet Connection (6) I219-LM                             | 1         | 1.96%   |
| Intel 82574L Gigabit Network Connection                           | 1         | 1.96%   |
| Intel 82566MM Gigabit Network Connection                          | 1         | 1.96%   |
| HMD Global Nokia 5.3 RNDIS Control RNDIS Ethernet Data            | 1         | 1.96%   |
| Broadcom NetXtreme BCM57786 Gigabit Ethernet PCIe                 | 1         | 1.96%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                  | 1         | 1.96%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart_bsd/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 47        | 48.45%  |
| Ethernet | 47        | 48.45%  |
| Modem    | 2         | 2.06%   |
| Unknown  | 1         | 1.03%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart_bsd/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 37        | 51.39%  |
| Ethernet | 35        | 48.61%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart_bsd/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 40        | 72.73%  |
| 1     | 11        | 20%     |
| 5     | 3         | 5.45%   |
| 6     | 1         | 1.82%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart_bsd/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 45        | 80.36%  |
| Yes  | 11        | 19.64%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart_bsd/bt_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 20        | 58.82%  |
| Apple                 | 4         | 11.76%  |
| Broadcom              | 3         | 8.82%   |
| IMC Networks          | 2         | 5.88%   |
| Realtek Semiconductor | 1         | 2.94%   |
| Lite-On Technology    | 1         | 2.94%   |
| Hewlett-Packard       | 1         | 2.94%   |
| Foxconn / Hon Hai     | 1         | 2.94%   |
| Dell                  | 1         | 2.94%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart_bsd/bt_model.svg)


| Model                                            | Notebooks | Percent |
|--------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface               | 9         | 26.47%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)   | 4         | 11.76%  |
| Intel AX200 Bluetooth                            | 3         | 8.82%   |
| Intel Wireless-AC 9260 Bluetooth Adapter         | 2         | 5.88%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]       | 2         | 5.88%   |
| Apple Bluetooth Host Controller                  | 2         | 5.88%   |
| Realtek  Bluetooth Adapter                       | 1         | 2.94%   |
| Lite-On Atheros AR3012 Bluetooth                 | 1         | 2.94%   |
| Intel Centrino Bluetooth Wireless Transceiver    | 1         | 2.94%   |
| Intel AX201 Bluetooth                            | 1         | 2.94%   |
| IMC Networks Qualcomm Atheros Bluetooth 4.0 + HS | 1         | 2.94%   |
| IMC Networks Qualcomm Atheros Bluetooth 4.0      | 1         | 2.94%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]    | 1         | 2.94%   |
| Foxconn / Hon Hai BCM43142A0 broadcom bluetooth  | 1         | 2.94%   |
| Dell Dell Wireless 380 Bluetooth 4.0 Module      | 1         | 2.94%   |
| Broadcom BCM2070 Bluetooth 2.1 + EDR             | 1         | 2.94%   |
| Apple Broadcom Bluetooth 2.1 module              | 1         | 2.94%   |
| Apple Apple Broadcom Built-in Bluetooth          | 1         | 2.94%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart_bsd/snd_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 41        | 71.93%  |
| AMD    | 14        | 24.56%  |
| Nvidia | 2         | 3.51%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart_bsd/snd_model.svg)


| Model                                                                             | Notebooks | Percent |
|-----------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                                   | 7         | 9.09%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller               | 7         | 9.09%   |
| AMD Family 17h/19h HD Audio Controller                                            | 6         | 7.79%   |
| Intel Wildcat Point-LP High Definition Audio Controller                           | 5         | 6.49%   |
| Intel Haswell-ULT HD Audio Controller                                             | 5         | 6.49%   |
| Intel Broadwell-U Audio Controller                                                | 5         | 6.49%   |
| Intel 8 Series HD Audio Controller                                                | 5         | 6.49%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                    | 4         | 5.19%   |
| AMD FCH Azalia Controller                                                         | 4         | 5.19%   |
| Intel Comet Lake PCH-LP cAVS                                                      | 2         | 2.6%    |
| Intel Cannon Point-LP High Definition Audio Controller                            | 2         | 2.6%    |
| Intel 82801H (ICH8 Family) HD Audio Controller                                    | 2         | 2.6%    |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller        | 2         | 2.6%    |
| AMD SBx00 Azalia (Intel HDA)                                                      | 2         | 2.6%    |
| AMD Renoir Radeon High Definition Audio Controller                                | 2         | 2.6%    |
| AMD Kabini HDMI/DP Audio                                                          | 2         | 2.6%    |
| Nvidia GK107 HDMI Audio Controller                                                | 1         | 1.3%    |
| Nvidia GF108 High Definition Audio Controller                                     | 1         | 1.3%    |
| Intel CM238 HD Audio Controller                                                   | 1         | 1.3%    |
| Intel Cannon Lake PCH cAVS                                                        | 1         | 1.3%    |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller        | 1         | 1.3%    |
| Intel Alder Lake PCH-P High Definition Audio Controller                           | 1         | 1.3%    |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                  | 1         | 1.3%    |
| AMD Wrestler HDMI Audio                                                           | 1         | 1.3%    |
| AMD Trinity HDMI Audio Controller                                                 | 1         | 1.3%    |
| AMD RS880 HDMI Audio [Radeon HD 4200 Series]                                      | 1         | 1.3%    |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                               | 1         | 1.3%    |
| AMD High Definition Audio Controller                                              | 1         | 1.3%    |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                  | 1         | 1.3%    |
| AMD Caicos HDMI Audio [Radeon HD 6450 / 7450/8450/8490 OEM / R5 230/235/235X OEM] | 1         | 1.3%    |
| AMD BeaverCreek HDMI Audio [Radeon HD 6500D and 6400G-6600G series]               | 1         | 1.3%    |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart_bsd/memory_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Samsung Electronics   | 12        | 21.82%  |
| Micron Technology     | 10        | 18.18%  |
| SK hynix              | 8         | 14.55%  |
| Unknown               | 4         | 7.27%   |
| Crucial               | 4         | 7.27%   |
| Transcend             | 3         | 5.45%   |
| Kingston              | 3         | 5.45%   |
| Elpida                | 3         | 5.45%   |
| Ramaxel Technology    | 2         | 3.64%   |
| Apacer                | 2         | 3.64%   |
| Nanya Technology      | 1         | 1.82%   |
| Kingmax Semiconductor | 1         | 1.82%   |
| G.Skill               | 1         | 1.82%   |
| Corsair               | 1         | 1.82%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart_bsd/memory_model.svg)


| Model                                                   | Notebooks | Percent |
|---------------------------------------------------------|-----------|---------|
| Transcend RAM TS1GLH64V6BL 8GB SODIMM DDR4 2667MT/s     | 2         | 3.64%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s   | 2         | 3.64%   |
| Elpida RAM EBJ41UF8BCS0-DJ-F 4GB SODIMM DDR3 1334MT/s   | 2         | 3.64%   |
| Unknown RAM Module 8GB SODIMM LPDDR3 1867MT/s           | 1         | 1.82%   |
| Unknown RAM Module 4GB SODIMM DDR3                      | 1         | 1.82%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s              | 1         | 1.82%   |
| Unknown RAM Module 1GB SODIMM DDR2 667MT/s              | 1         | 1.82%   |
| Transcend RAM TS512MLH64V6HL 4GB SODIMM DDR4 2667MT/s   | 1         | 1.82%   |
| SK hynix RAM Module 4GB SODIMM DDR3 1600MT/s            | 1         | 1.82%   |
| SK hynix RAM Module 4096MB SODIMM DDR3 1333MT/s         | 1         | 1.82%   |
| SK hynix RAM HMT451S6MFR8A-PB 4GB SODIMM DDR3 800MT/s   | 1         | 1.82%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s  | 1         | 1.82%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s  | 1         | 1.82%   |
| SK hynix RAM HMT41GS6AFR8A-PB 8GB SODIMM DDR3 1600MT/s  | 1         | 1.82%   |
| SK hynix RAM HMT351S6EFR8C-PB 4GB SODIMM DDR3 1600MT/s  | 1         | 1.82%   |
| SK hynix RAM HMT351S6CFR8A-PB 4GB SODIMM DDR3 1333MT/s  | 1         | 1.82%   |
| Samsung RAM Module 8GB SODIMM DDR4 2133MT/s             | 1         | 1.82%   |
| Samsung RAM Module 8GB Row Of Chips LPDDR3 2133MT/s     | 1         | 1.82%   |
| Samsung RAM M471B5673FH0-CH9 2GB SODIMM DDR3 1334MT/s   | 1         | 1.82%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s   | 1         | 1.82%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1867MT/s   | 1         | 1.82%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s   | 1         | 1.82%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 2667MT/s   | 1         | 1.82%   |
| Samsung RAM M471A4G43AB1-CWE 32GB SODIMM DDR4 3200MT/s  | 1         | 1.82%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s   | 1         | 1.82%   |
| Samsung RAM K4E6E304EB-EGCF 4GB 1867MT/s                | 1         | 1.82%   |
| Ramaxel RAM RMT3170MN68F9F1600 4GB SODIMM DDR3 1600MT/s | 1         | 1.82%   |
| Ramaxel RAM RMT3020EF48E8W1333 2GB SODIMM DDR3 1334MT/s | 1         | 1.82%   |
| Nanya RAM NT2GC64B8HA1NS-BE 2GB SODIMM DDR3 1067MT/s    | 1         | 1.82%   |
| Micron RAM MT41K512M16TNA-125 4GB Chip DDR3 1600MT/s    | 1         | 1.82%   |
| Micron RAM 8KTS51264HDZ-1G6E1 4GB Chip DDR3 1600MT/s    | 1         | 1.82%   |
| Micron RAM 8KTF51264HDZ-1G6E1 4GB SODIMM DDR3 1600MT/s  | 1         | 1.82%   |
| Micron RAM 4ATS1G64HZ-2G6E1 8GB SODIMM DDR4 2667MT/s    | 1         | 1.82%   |
| Micron RAM 4ATF51264HZ-2G3BZ 8GB SODIMM DDR4 2667MT/s   | 1         | 1.82%   |
| Micron RAM 16KTF51264HZ-1G6M1 4GB SODIMM DDR3 1600MT/s  | 1         | 1.82%   |
| Micron RAM 16KTF1G64HZ-1G9P1 8GB SODIMM DDR3 1866MT/s   | 1         | 1.82%   |
| Micron RAM 16KTF1G64HZ-1G9P1 8GB Chip DDR3 1867MT/s     | 1         | 1.82%   |
| Micron RAM 16HTF51264HZ-800C1 4GB SODIMM DDR2 800MT/s   | 1         | 1.82%   |
| Micron RAM 16ATF2G64HZ-2G3H1 16GB SODIMM DDR4 2400MT/s  | 1         | 1.82%   |
| Kingston RAM 99U5663-007.A00G 16GB SODIMM DDR4 2667MT/s | 1         | 1.82%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart_bsd/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR3    | 27        | 57.45%  |
| DDR4    | 14        | 29.79%  |
| DDR2    | 3         | 6.38%   |
| LPDDR3  | 2         | 4.26%   |
| Unknown | 1         | 2.13%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart_bsd/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 43        | 89.58%  |
| Chip         | 3         | 6.25%   |
| Row Of Chips | 1         | 2.08%   |
| Unknown      | 1         | 2.08%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart_bsd/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 4096  | 22        | 42.31%  |
| 8192  | 16        | 30.77%  |
| 2048  | 7         | 13.46%  |
| 16384 | 5         | 9.62%   |
| 32768 | 1         | 1.92%   |
| 1024  | 1         | 1.92%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart_bsd/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 1600    | 14        | 28.57%  |
| 2667    | 8         | 16.33%  |
| 1867    | 4         | 8.16%   |
| 1334    | 4         | 8.16%   |
| 1333    | 4         | 8.16%   |
| 2400    | 3         | 6.12%   |
| 2133    | 2         | 4.08%   |
| 1866    | 2         | 4.08%   |
| 800     | 2         | 4.08%   |
| 667     | 2         | 4.08%   |
| 3200    | 1         | 2.04%   |
| 1067    | 1         | 2.04%   |
| 1066    | 1         | 2.04%   |
| Unknown | 1         | 2.04%   |

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

Zero info for selected period =(

Scanner Model
-------------

Scanner device models

Zero info for selected period =(

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart_bsd/camera_vendor.svg)


| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 12        | 32.43%  |
| Realtek Semiconductor                  | 6         | 16.22%  |
| IMC Networks                           | 4         | 10.81%  |
| Lite-On Technology                     | 3         | 8.11%   |
| Apple                                  | 3         | 8.11%   |
| Acer                                   | 3         | 8.11%   |
| Microdia                               | 2         | 5.41%   |
| Sunplus Innovation Technology          | 1         | 2.7%    |
| Ricoh                                  | 1         | 2.7%    |
| Cheng Uei Precision Industry (Foxlink) | 1         | 2.7%    |
| Alcor Micro                            | 1         | 2.7%    |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart_bsd/camera_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Chicony Integrated Camera                     | 3         | 8.11%   |
| Realtek USB Camera                            | 2         | 5.41%   |
| Realtek Integrated_Webcam_HD                  | 2         | 5.41%   |
| Lite-On Integrated Camera                     | 2         | 5.41%   |
| IMC Networks Integrated Camera                | 2         | 5.41%   |
| Chicony HD Webcam                             | 2         | 5.41%   |
| Chicony Chicony USB2.0 Camera                 | 2         | 5.41%   |
| Apple FaceTime HD Camera                      | 2         | 5.41%   |
| Acer Integrated Camera                        | 2         | 5.41%   |
| Sunplus Laptop Integrated Webcam HD           | 1         | 2.7%    |
| Ricoh USB2.0 Camera                           | 1         | 2.7%    |
| Realtek Lenovo EasyCamera                     | 1         | 2.7%    |
| Realtek Integrated Webcam HD                  | 1         | 2.7%    |
| Microdia Integrated_Webcam_HD                 | 1         | 2.7%    |
| Microdia Dell Integrated HD Webcam            | 1         | 2.7%    |
| Lite-On TOSHIBA Web Camera - HD               | 1         | 2.7%    |
| IMC Networks USB2.0 HD UVC WebCam             | 1         | 2.7%    |
| IMC Networks EasyCamera                       | 1         | 2.7%    |
| Chicony VGA Webcam                            | 1         | 2.7%    |
| Chicony thinkpad t430s camera                 | 1         | 2.7%    |
| Chicony Integrated Camera (1280x720@30)       | 1         | 2.7%    |
| Chicony HP Webcam [2 MP]                      | 1         | 2.7%    |
| Chicony HD WebCam (Acer)                      | 1         | 2.7%    |
| Cheng Uei Precision Industry (Foxlink) Webcam | 1         | 2.7%    |
| Apple FaceTime HD Camera (Built-in)           | 1         | 2.7%    |
| Alcor Micro ASUS USB2.0 WebCam                | 1         | 2.7%    |
| Acer Lenovo EasyCamera                        | 1         | 2.7%    |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart_bsd/fingerprint_vendor.svg)


| Vendor             | Notebooks | Percent |
|--------------------|-----------|---------|
| Validity Sensors   | 2         | 28.57%  |
| Synaptics          | 2         | 28.57%  |
| AuthenTec          | 2         | 28.57%  |
| STMicroelectronics | 1         | 14.29%  |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart_bsd/fingerprint_model.svg)


| Model                                             | Notebooks | Percent |
|---------------------------------------------------|-----------|---------|
| Validity Sensors VFS 5011 fingerprint sensor      | 1         | 14.29%  |
| Validity Sensors Synaptics WBDI                   | 1         | 14.29%  |
| Synaptics Prometheus MIS Touch Fingerprint Reader | 1         | 14.29%  |
| Synaptics Metallica MIS Touch Fingerprint Reader  | 1         | 14.29%  |
| STMicroelectronics Fingerprint Reader             | 1         | 14.29%  |
| AuthenTec AES2810                                 | 1         | 14.29%  |
| AuthenTec AES1660 Fingerprint Sensor              | 1         | 14.29%  |

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


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 26        | 46.43%  |
| 0     | 11        | 19.64%  |
| 2     | 9         | 16.07%  |
| 3     | 6         | 10.71%  |
| 4     | 4         | 7.14%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart_bsd/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Communication controller | 35        | 49.3%   |
| Card reader              | 10        | 14.08%  |
| Net/wireless             | 9         | 12.68%  |
| Fingerprint reader       | 6         | 8.45%   |
| Bluetooth                | 6         | 8.45%   |
| Firewire controller      | 2         | 2.82%   |
| Sound                    | 1         | 1.41%   |
| Net/ethernet             | 1         | 1.41%   |
| Graphics card            | 1         | 1.41%   |

