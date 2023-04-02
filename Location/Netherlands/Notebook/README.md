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

Total: 76

| Vendor        | Model                       | Probe                                                     | Date         |
|---------------|-----------------------------|-----------------------------------------------------------|--------------|
| Dell          | Inspiron 7437               | [2c4de59558](https://bsd-hardware.info/?probe=2c4de59558) | Mar 27, 2023 |
| Notebook      | N2x0WU                      | [9545f36dee](https://bsd-hardware.info/?probe=9545f36dee) | Feb 27, 2023 |
| SLIMBOOK      | PROX-AMD5                   | [8083410c50](https://bsd-hardware.info/?probe=8083410c50) | Feb 06, 2023 |
| Deciso        | OPNsense Appliance          | [62452eaaaa](https://bsd-hardware.info/?probe=62452eaaaa) | Feb 05, 2023 |
| Deciso        | OPNsense Appliance          | [96df89832f](https://bsd-hardware.info/?probe=96df89832f) | Feb 04, 2023 |
| Unknown       | Unknown                     | [a7d54d41c8](https://bsd-hardware.info/?probe=a7d54d41c8) | Feb 02, 2023 |
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
| helloSystem 0.7.0    | 8         | 12.31%  |
| helloSystem 0.5.0    | 6         | 9.23%   |
| FreeBSD 13.0-STABLE  | 5         | 7.69%   |
| helloSystem 0.8.0    | 4         | 6.15%   |
| helloSystem 0.6.0    | 3         | 4.62%   |
| helloSystem 0.3.0    | 3         | 4.62%   |
| OPNsense 22.10       | 2         | 3.08%   |
| OpenBSD 7.1          | 2         | 3.08%   |
| OpenBSD 6.9          | 2         | 3.08%   |
| OpenBSD 6.8          | 2         | 3.08%   |
| helloSystem 0.4.0    | 2         | 3.08%   |
| GhostBSD 22.06.18    | 2         | 3.08%   |
| FreeBSD 13.1-p4      | 2         | 3.08%   |
| FreeBSD 13.1         | 2         | 3.08%   |
| FreeBSD 13.0-p5      | 2         | 3.08%   |
| OPNsense 22.7.4      | 1         | 1.54%   |
| OPNsense 22.7.2      | 1         | 1.54%   |
| OPNsense 22.7.10     | 1         | 1.54%   |
| OPNsense 22.10.1     | 1         | 1.54%   |
| OPNsense 22.1.7      | 1         | 1.54%   |
| OPNsense 22.1.6      | 1         | 1.54%   |
| OPNsense 22.1        | 1         | 1.54%   |
| OPNsense 21.7.7      | 1         | 1.54%   |
| OPNsense 21.1.9      | 1         | 1.54%   |
| OpenBSD 7.2          | 1         | 1.54%   |
| OpenBSD 7.0          | 1         | 1.54%   |
| helloSystem 0.8.1    | 1         | 1.54%   |
| FreeBSD 14.0-CURRENT | 1         | 1.54%   |
| FreeBSD 13.0-p2      | 1         | 1.54%   |
| FreeBSD 13.0-BETA1   | 1         | 1.54%   |
| FreeBSD 13.0         | 1         | 1.54%   |
| FreeBSD 12.2-p2      | 1         | 1.54%   |
| FreeBSD 12.2         | 1         | 1.54%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart_bsd/os_family.svg)


| Name        | Notebooks | Percent |
|-------------|-----------|---------|
| helloSystem | 26        | 43.33%  |
| FreeBSD     | 16        | 26.67%  |
| OPNsense    | 8         | 13.33%  |
| OpenBSD     | 8         | 13.33%  |
| GhostBSD    | 2         | 3.33%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart_bsd/os_arch.svg)


| Name  | Notebooks | Percent |
|-------|-----------|---------|
| amd64 | 60        | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart_bsd/os_de.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| helloDesktop | 28        | 46.67%  |
| Console      | 10        | 16.67%  |
| fvwm         | 5         | 8.33%   |
| MATE         | 4         | 6.67%   |
| GNOME        | 3         | 5%      |
| TWM          | 2         | 3.33%   |
| KDE5         | 2         | 3.33%   |
| i3           | 2         | 3.33%   |
| XFCE         | 1         | 1.67%   |
| LXQt         | 1         | 1.67%   |
| GNUstep      | 1         | 1.67%   |
| AwesomeWM    | 1         | 1.67%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart_bsd/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 50        | 83.33%  |
| Console | 9         | 15%     |
| Wayland | 1         | 1.67%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart_bsd/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| SLiM    | 29        | 48.33%  |
| Console | 20        | 33.33%  |
| XDM     | 4         | 6.67%   |
| LightDM | 3         | 5%      |
| SDDM    | 2         | 3.33%   |
| GDM     | 2         | 3.33%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart_bsd/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| en_US   | 27        | 45%     |
| C       | 13        | 21.67%  |
| Unknown | 13        | 21.67%  |
| en      | 3         | 5%      |
| nl_NL   | 2         | 3.33%   |
| nl      | 1         | 1.67%   |
| fr_FR   | 1         | 1.67%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart_bsd/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 50        | 81.97%  |
| BIOS | 11        | 18.03%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart_bsd/os_filesystem.svg)


| Type   | Notebooks | Percent |
|--------|-----------|---------|
| Zfs    | 36        | 60%     |
| Ufs    | 8         | 13.33%  |
| Ffs    | 8         | 13.33%  |
| Cd9660 | 8         | 13.33%  |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart_bsd/os_part_scheme.svg)


| Type | Notebooks | Percent |
|------|-----------|---------|
| GPT  | 56        | 93.33%  |
| MBR  | 4         | 6.67%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart_bsd/node_vendor.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| Lenovo           | 19        | 31.67%  |
| Dell             | 9         | 15%     |
| Hewlett-Packard  | 4         | 6.67%   |
| Deciso           | 4         | 6.67%   |
| Apple            | 4         | 6.67%   |
| Notebook         | 3         | 5%      |
| ASUSTek Computer | 3         | 5%      |
| SLIMBOOK         | 2         | 3.33%   |
| Acer             | 2         | 3.33%   |
| Unknown          | 2         | 3.33%   |
| WYSE             | 1         | 1.67%   |
| TUXEDO           | 1         | 1.67%   |
| TOXIC by BTO     | 1         | 1.67%   |
| Toshiba          | 1         | 1.67%   |
| Star Labs        | 1         | 1.67%   |
| Sony             | 1         | 1.67%   |
| Intel            | 1         | 1.67%   |
| Google           | 1         | 1.67%   |

Model
-----

Motherboard model

![Model](./images/pie_chart_bsd/node_model.svg)


| Name                                     | Notebooks | Percent |
|------------------------------------------|-----------|---------|
| Unknown                                  | 3         | 5%      |
| Dell Latitude E4300                      | 2         | 3.33%   |
| Deciso OPNsense Appliance                | 2         | 3.33%   |
| Deciso NetBoard-A10                      | 2         | 3.33%   |
| WYSE Z CLASS                             | 1         | 1.67%   |
| TUXEDO Pulse 15 Gen1                     | 1         | 1.67%   |
| TOXIC by BTO 15CL872 1050TI              | 1         | 1.67%   |
| Toshiba Satellite C50-B                  | 1         | 1.67%   |
| Star Labs LabTop                         | 1         | 1.67%   |
| Sony SVZ1311C5E                          | 1         | 1.67%   |
| SLIMBOOK PROX-AMD5                       | 1         | 1.67%   |
| Notebook NS5x_NS7xPU                     | 1         | 1.67%   |
| Notebook NL5xRU                          | 1         | 1.67%   |
| Notebook N2x0WU                          | 1         | 1.67%   |
| Lenovo Yoga 500-14IBD 80N4               | 1         | 1.67%   |
| Lenovo ThinkPad X61s 76693KG             | 1         | 1.67%   |
| Lenovo ThinkPad X280 20KESA000B          | 1         | 1.67%   |
| Lenovo ThinkPad X250 20CLS5BU00          | 1         | 1.67%   |
| Lenovo ThinkPad X250 20CLS59400          | 1         | 1.67%   |
| Lenovo ThinkPad X250 20CLS4WV08          | 1         | 1.67%   |
| Lenovo ThinkPad X230 2325IG2             | 1         | 1.67%   |
| Lenovo ThinkPad X230 23255Y4             | 1         | 1.67%   |
| Lenovo ThinkPad X200s 7470W1V            | 1         | 1.67%   |
| Lenovo ThinkPad X1 Carbon 7th 20QDCTO1WW | 1         | 1.67%   |
| Lenovo ThinkPad X1 Carbon 5th 20HRCTO1WW | 1         | 1.67%   |
| Lenovo ThinkPad T490 20N2CTO1WW          | 1         | 1.67%   |
| Lenovo ThinkPad T440s 20ARS1B704         | 1         | 1.67%   |
| Lenovo ThinkPad T440 20B7S2LT00          | 1         | 1.67%   |
| Lenovo ThinkPad T430 2347G7G             | 1         | 1.67%   |
| Lenovo ThinkPad S1 Yoga 20CD0038MB       | 1         | 1.67%   |
| Lenovo ThinkPad A285 20MW000JMH          | 1         | 1.67%   |
| Lenovo IdeaPad 130-15AST 81H5            | 1         | 1.67%   |
| Lenovo G505s 20255                       | 1         | 1.67%   |
| Intel Milstead Platform                  | 1         | 1.67%   |
| HP EliteBook 8460p                       | 1         | 1.67%   |
| HP EliteBook 840 G3                      | 1         | 1.67%   |
| HP EliteBook 2530p                       | 1         | 1.67%   |
| HP 625                                   | 1         | 1.67%   |
| Google Cave                              | 1         | 1.67%   |
| Dell XPS 15 9560                         | 1         | 1.67%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart_bsd/node_model_family.svg)


| Name                 | Notebooks | Percent |
|----------------------|-----------|---------|
| Lenovo ThinkPad      | 16        | 26.67%  |
| Dell Latitude        | 7         | 11.67%  |
| HP EliteBook         | 3         | 5%      |
| Unknown              | 3         | 5%      |
| Deciso OPNsense      | 2         | 3.33%   |
| Deciso NetBoard-A10  | 2         | 3.33%   |
| Acer Aspire          | 2         | 3.33%   |
| WYSE Z               | 1         | 1.67%   |
| TUXEDO Pulse         | 1         | 1.67%   |
| TOXIC by BTO 15CL872 | 1         | 1.67%   |
| Toshiba Satellite    | 1         | 1.67%   |
| Star Labs LabTop     | 1         | 1.67%   |
| Sony SVZ1311C5E      | 1         | 1.67%   |
| SLIMBOOK PROX-AMD5   | 1         | 1.67%   |
| Notebook NS5x        | 1         | 1.67%   |
| Notebook NL5xRU      | 1         | 1.67%   |
| Notebook N2x0WU      | 1         | 1.67%   |
| Lenovo Yoga          | 1         | 1.67%   |
| Lenovo IdeaPad       | 1         | 1.67%   |
| Lenovo G505s         | 1         | 1.67%   |
| Intel Milstead       | 1         | 1.67%   |
| HP 625               | 1         | 1.67%   |
| Google Cave          | 1         | 1.67%   |
| Dell XPS             | 1         | 1.67%   |
| Dell Inspiron        | 1         | 1.67%   |
| ASUS X751LB          | 1         | 1.67%   |
| ASUS X556UA          | 1         | 1.67%   |
| ASUS K53TA           | 1         | 1.67%   |
| Apple MacBookPro9    | 1         | 1.67%   |
| Apple MacBookPro8    | 1         | 1.67%   |
| Apple MacBookPro10   | 1         | 1.67%   |
| Apple MacBookAir1    | 1         | 1.67%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart_bsd/node_year.svg)


| Year    | Notebooks | Percent |
|---------|-----------|---------|
| 2019    | 7         | 11.67%  |
| 2015    | 7         | 11.67%  |
| 2022    | 6         | 10%     |
| 2020    | 5         | 8.33%   |
| 2018    | 5         | 8.33%   |
| 2012    | 5         | 8.33%   |
| 2014    | 4         | 6.67%   |
| 2021    | 3         | 5%      |
| 2016    | 3         | 5%      |
| 2013    | 3         | 5%      |
| 2011    | 3         | 5%      |
| 2017    | 2         | 3.33%   |
| 2009    | 2         | 3.33%   |
| 2008    | 2         | 3.33%   |
| Unknown | 2         | 3.33%   |
| 2010    | 1         | 1.67%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart_bsd/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 60        | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart_bsd/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 59        | 98.33%  |
| Yes  | 1         | 1.67%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart_bsd/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 8.01-16.0   | 29        | 48.33%  |
| 4.01-8.0    | 13        | 21.67%  |
| 16.01-24.0  | 12        | 20%     |
| 32.01-64.0  | 3         | 5%      |
| 64.01-256.0 | 2         | 3.33%   |
| 2.01-3.0    | 1         | 1.67%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart_bsd/node_ram_used.svg)


| Used GB  | Notebooks | Percent |
|----------|-----------|---------|
| 0.01-0.5 | 36        | 58.06%  |
| 0.51-1.0 | 15        | 24.19%  |
| 1.01-2.0 | 8         | 12.9%   |
| 3.01-4.0 | 2         | 3.23%   |
| 2.01-3.0 | 1         | 1.61%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart_bsd/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 39        | 63.93%  |
| 2      | 16        | 26.23%  |
| 3      | 3         | 4.92%   |
| 0      | 3         | 4.92%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart_bsd/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 49        | 81.67%  |
| Yes       | 11        | 18.33%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart_bsd/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 51        | 85%     |
| No        | 9         | 15%     |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart_bsd/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 51        | 85%     |
| No        | 9         | 15%     |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart_bsd/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 38        | 63.33%  |
| No        | 22        | 36.67%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart_bsd/node_location.svg)


| Country     | Notebooks | Percent |
|-------------|-----------|---------|
| Netherlands | 60        | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart_bsd/node_city.svg)


| City                    | Notebooks | Percent |
|-------------------------|-----------|---------|
| Amsterdam               | 14        | 22.58%  |
| Utrecht                 | 5         | 8.06%   |
| Eindhoven               | 3         | 4.84%   |
| The Hague               | 2         | 3.23%   |
| Papendrecht             | 2         | 3.23%   |
| Oegstgeest              | 2         | 3.23%   |
| Hoogeveen               | 2         | 3.23%   |
| Groningen               | 2         | 3.23%   |
| 's-Hertogenbosch        | 2         | 3.23%   |
| Zwolle                  | 1         | 1.61%   |
| Woerdense Verlaat       | 1         | 1.61%   |
| Warmond                 | 1         | 1.61%   |
| Tilburg                 | 1         | 1.61%   |
| Rozenburg               | 1         | 1.61%   |
| Roosendaal              | 1         | 1.61%   |
| Rhoon                   | 1         | 1.61%   |
| Ouderkerk aan de Amstel | 1         | 1.61%   |
| Oosterhout              | 1         | 1.61%   |
| Norg                    | 1         | 1.61%   |
| Munnikens-Vinkel        | 1         | 1.61%   |
| Lent                    | 1         | 1.61%   |
| Leiden                  | 1         | 1.61%   |
| Leeuwarden              | 1         | 1.61%   |
| Hoek van Holland        | 1         | 1.61%   |
| Hilversum               | 1         | 1.61%   |
| Ede                     | 1         | 1.61%   |
| Dronten                 | 1         | 1.61%   |
| Dordrecht               | 1         | 1.61%   |
| Diemen                  | 1         | 1.61%   |
| Deventer                | 1         | 1.61%   |
| Den Dolder              | 1         | 1.61%   |
| De Lutte                | 1         | 1.61%   |
| Cuijk                   | 1         | 1.61%   |
| Capelle aan den IJssel  | 1         | 1.61%   |
| Bergambacht             | 1         | 1.61%   |
| Apeldoorn               | 1         | 1.61%   |
| Alphen aan den Rijn     | 1         | 1.61%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart_bsd/drive_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 16        | 22     | 23.53%  |
| WDC                 | 8         | 8      | 11.76%  |
| Seagate             | 6         | 7      | 8.82%   |
| Crucial             | 6         | 7      | 8.82%   |
| Transcend           | 5         | 6      | 7.35%   |
| Toshiba             | 3         | 3      | 4.41%   |
| SanDisk             | 3         | 3      | 4.41%   |
| NVMe                | 3         | 4      | 4.41%   |
| Intel               | 2         | 2      | 2.94%   |
| Hitachi             | 2         | 2      | 2.94%   |
| Gigabyte Technology | 2         | 2      | 2.94%   |
| Apple               | 2         | 2      | 2.94%   |
| Star Drive          | 1         | 1      | 1.47%   |
| SK hynix            | 1         | 1      | 1.47%   |
| OCZ                 | 1         | 1      | 1.47%   |
| LITEON              | 1         | 1      | 1.47%   |
| Leven               | 1         | 1      | 1.47%   |
| Kingston            | 1         | 1      | 1.47%   |
| HPE                 | 1         | 1      | 1.47%   |
| Hoodisk             | 1         | 2      | 1.47%   |
| HGST                | 1         | 1      | 1.47%   |
| China               | 1         | 1      | 1.47%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart_bsd/drive_model.svg)


| Model                            | Notebooks | Percent |
|----------------------------------|-----------|---------|
| WDC WD5000LPVX-22V0TT0 500GB     | 2         | 2.9%    |
| Transcend TS256GMTE652T2 256GB   | 2         | 2.9%    |
| Seagate ST500LM000-SSHD-8GB      | 2         | 2.9%    |
| WDC WDS500G2B0C-00PXH0 500GB     | 1         | 1.45%   |
| WDC WDS500G2B0A 500GB            | 1         | 1.45%   |
| WDC WDS100T2B0B-00YS70 1TB       | 1         | 1.45%   |
| WDC WD15EARS-00Z5B1 1.5TB        | 1         | 1.45%   |
| WDC WD10SPZX-24Z10 1TB           | 1         | 1.45%   |
| WDC WD10SPZX-00Z10T0 1TB         | 1         | 1.45%   |
| Transcend TS512GMTS430S 512GB    | 1         | 1.45%   |
| Transcend TS256GMTS952T2 256GB   | 1         | 1.45%   |
| Transcend TS128GMTE110S 128GB    | 1         | 1.45%   |
| Toshiba THNSN5512GPUK NVMe 512GB | 1         | 1.45%   |
| Toshiba THNSFJ256GCSU 256GB      | 1         | 1.45%   |
| Toshiba MQ04ABF100 1TB           | 1         | 1.45%   |
| Star Drive PCIe SSD 960GB        | 1         | 1.45%   |
| SK hynix SC311 SATA 256GB        | 1         | 1.45%   |
| Seagate ST9250410AS 250GB        | 1         | 1.45%   |
| Seagate ST9160412ASG 160GB       | 1         | 1.45%   |
| Seagate ST500VT000-1DK142 500GB  | 1         | 1.45%   |
| Seagate ST1000LM049-2GH172 1TB   | 1         | 1.45%   |
| SanDisk SD8SBAT256G1002 256GB    | 1         | 1.45%   |
| SanDisk SD7UB3Q256G1001 256GB    | 1         | 1.45%   |
| SanDisk SD6SB1M064G 64GB         | 1         | 1.45%   |
| Samsung SSD PM851 mSATA 512GB    | 1         | 1.45%   |
| Samsung SSD PM841 mSATA 256GB    | 1         | 1.45%   |
| Samsung SSD 980 PRO 1TB          | 1         | 1.45%   |
| Samsung SSD 970 PRO 512GB        | 1         | 1.45%   |
| Samsung SSD 970 EVO 500GB        | 1         | 1.45%   |
| Samsung SSD 870 QVO 1TB          | 1         | 1.45%   |
| Samsung SSD 860 EVO 1TB          | 1         | 1.45%   |
| Samsung SSD 850 EVO 500GB        | 1         | 1.45%   |
| Samsung SSD 850 EVO 250GB        | 1         | 1.45%   |
| Samsung SSD 840 EVO 250GB        | 1         | 1.45%   |
| Samsung SSD 840 EVO 120GB        | 1         | 1.45%   |
| Samsung SSD 830 Series 64GB      | 1         | 1.45%   |
| Samsung MZVLB1T0HBLR-000L7 1TB   | 1         | 1.45%   |
| Samsung MZRPC256HADR-000SO 128GB | 1         | 1.45%   |
| Samsung MZNLN256HCHP-000H1 256GB | 1         | 1.45%   |
| Samsung MZ7TD256HAFV-000L9 256GB | 1         | 1.45%   |

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
| Samsung Electronics | 11        | 16     | 28.95%  |
| Crucial             | 5         | 6      | 13.16%  |
| SanDisk             | 3         | 3      | 7.89%   |
| NVMe                | 3         | 4      | 7.89%   |
| WDC                 | 2         | 2      | 5.26%   |
| Transcend           | 2         | 3      | 5.26%   |
| Apple               | 2         | 2      | 5.26%   |
| Toshiba             | 1         | 1      | 2.63%   |
| SK hynix            | 1         | 1      | 2.63%   |
| OCZ                 | 1         | 1      | 2.63%   |
| LITEON              | 1         | 1      | 2.63%   |
| Leven               | 1         | 1      | 2.63%   |
| Intel               | 1         | 1      | 2.63%   |
| HPE                 | 1         | 1      | 2.63%   |
| Hoodisk             | 1         | 2      | 2.63%   |
| Gigabyte Technology | 1         | 1      | 2.63%   |
| China               | 1         | 1      | 2.63%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart_bsd/drive_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SSD  | 34        | 47     | 53.97%  |
| HDD  | 16        | 17     | 25.4%   |
| NVMe | 13        | 15     | 20.63%  |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart_bsd/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 47        | 64     | 78.33%  |
| NVMe | 13        | 15     | 21.67%  |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart_bsd/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 38        | 49     | 74.51%  |
| 0.51-1.0   | 12        | 14     | 23.53%  |
| 1.01-2.0   | 1         | 1      | 1.96%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart_bsd/drive_space_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 101-250    | 18        | 29.51%  |
| 1-20       | 15        | 24.59%  |
| 251-500    | 13        | 21.31%  |
| 501-1000   | 6         | 9.84%   |
| 51-100     | 5         | 8.2%    |
| 21-50      | 2         | 3.28%   |
| 1001-2000  | 1         | 1.64%   |
| Unknown    | 1         | 1.64%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart_bsd/drive_space_used.svg)


| Used GB  | Notebooks | Percent |
|----------|-----------|---------|
| 1-20     | 51        | 85%     |
| 251-500  | 2         | 3.33%   |
| 21-50    | 2         | 3.33%   |
| 51-100   | 2         | 3.33%   |
| 101-250  | 1         | 1.67%   |
| 501-1000 | 1         | 1.67%   |
| Unknown  | 1         | 1.67%   |

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
| Works    | 50        | 67     | 83.33%  |
| Malfunc  | 5         | 5      | 8.33%   |
| Detected | 4         | 6      | 6.67%   |
| Failed   | 1         | 1      | 1.67%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart_bsd/storage_vendor.svg)


| Vendor                      | Notebooks | Percent |
|-----------------------------|-----------|---------|
| Intel                       | 40        | 60.61%  |
| AMD                         | 11        | 16.67%  |
| Samsung Electronics         | 6         | 9.09%   |
| Transcend                   | 3         | 4.55%   |
| Phison Electronics          | 2         | 3.03%   |
| Toshiba                     | 1         | 1.52%   |
| SanDisk                     | 1         | 1.52%   |
| Micron/Crucial Technology   | 1         | 1.52%   |
| Kingston Technology Company | 1         | 1.52%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart_bsd/storage_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                          | 9         | 12.68%  |
| Intel 82801 Mobile SATA Controller [RAID mode]                               | 7         | 9.86%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                           | 5         | 7.04%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                 | 5         | 7.04%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]             | 5         | 7.04%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                | 4         | 5.63%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                           | 3         | 4.23%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]        | 3         | 4.23%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller | 3         | 4.23%   |
| Unknown                                                                      | 3         | 4.23%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                               | 2         | 2.82%   |
| Intel SSD Pro 7600p/760p/E 6100p Series                                      | 2         | 2.82%   |
| Intel Comet Lake SATA AHCI Controller                                        | 2         | 2.82%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                | 2         | 2.82%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                             | 2         | 2.82%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                            | 2         | 2.82%   |
| Toshiba XG4 NVMe SSD Controller                                              | 1         | 1.41%   |
| SanDisk WD Blue SN550 NVMe SSD                                               | 1         | 1.41%   |
| Phison PS5013 E13 NVMe Controller                                            | 1         | 1.41%   |
| Phison E12 NVMe Controller                                                   | 1         | 1.41%   |
| Micron/Crucial P2 NVMe PCIe SSD                                              | 1         | 1.41%   |
| Kingston Company A2000 NVMe SSD                                              | 1         | 1.41%   |
| Intel Mobile 4 Series Chipset PT IDER Controller                             | 1         | 1.41%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                        | 1         | 1.41%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                            | 1         | 1.41%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                       | 1         | 1.41%   |
| Intel 82801JI (ICH10 Family) SATA AHCI Controller                            | 1         | 1.41%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 2 port SATA Controller [IDE mode]         | 1         | 1.41%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart_bsd/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 43        | 61.43%  |
| NVMe | 16        | 22.86%  |
| RAID | 7         | 10%     |
| IDE  | 4         | 5.71%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart_bsd/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 45        | 75%     |
| AMD    | 15        | 25%     |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart_bsd/cpu_model.svg)


| Model                                   | Notebooks | Percent |
|-----------------------------------------|-----------|---------|
| AMD Ryzen Embedded V1500B               | 3         | 5%      |
| Intel Core i7-7600U CPU @ 2.80GHz       | 2         | 3.33%   |
| Intel Core i7-4600U CPU @ 2.10GHz       | 2         | 3.33%   |
| Intel Core i7-4500U CPU @ 1.80GHz       | 2         | 3.33%   |
| Intel Core i7-3520M CPU @ 2.90GHz       | 2         | 3.33%   |
| Intel Core i5-5300U CPU @ 2.30GHz       | 2         | 3.33%   |
| Intel Core i5-3210M CPU @ 2.50GHz       | 2         | 3.33%   |
| Intel Core 2 Duo                        | 2         | 3.33%   |
| AMD E1-2500 APU with Radeon HD Graphics | 2         | 3.33%   |
| Intel Pentium CPU N3530 @ 2.16GHz       | 1         | 1.67%   |
| Intel Core m7-6Y75 CPU @ 1.20GHz        | 1         | 1.67%   |
| Intel Core m3-6Y30 CPU @ 0.90GHz        | 1         | 1.67%   |
| Intel Core i7-8750H CPU @ 2.20GHz       | 1         | 1.67%   |
| Intel Core i7-8665U CPU @ 1.90GHz       | 1         | 1.67%   |
| Intel Core i7-8565U CPU @ 1.80GHz       | 1         | 1.67%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz      | 1         | 1.67%   |
| Intel Core i7-6500U CPU @ 2.50GHz       | 1         | 1.67%   |
| Intel Core i7-5600U CPU @ 2.60GHz       | 1         | 1.67%   |
| Intel Core i7-5500U CPU @ 2.40GHz       | 1         | 1.67%   |
| Intel Core i7-3615QM CPU @ 2.30GHz      | 1         | 1.67%   |
| Intel Core i7-3612QM CPU @ 2.10GHz      | 1         | 1.67%   |
| Intel Core i7-2630QM CPU @ 2.00GHz      | 1         | 1.67%   |
| Intel Core i7-10710U CPU @ 1.10GHz      | 1         | 1.67%   |
| Intel Core i5-8350U CPU @ 1.70GHz       | 1         | 1.67%   |
| Intel Core i5-6300U CPU @ 2.40GHz       | 1         | 1.67%   |
| Intel Core i5-6200U CPU @ 2.30GHz       | 1         | 1.67%   |
| Intel Core i5-4200U CPU @ 1.60GHz       | 1         | 1.67%   |
| Intel Core i5-3320M CPU @ 2.60GHz       | 1         | 1.67%   |
| Intel Core i5-2520M CPU @ 2.50GHz       | 1         | 1.67%   |
| Intel Core i5-2435M CPU @ 2.40GHz       | 1         | 1.67%   |
| Intel Core i5-10210U CPU @ 1.60GHz      | 1         | 1.67%   |
| Intel Core i3-7100U CPU @ 2.40GHz       | 1         | 1.67%   |
| Intel Core i3-5005U CPU @ 2.00GHz       | 1         | 1.67%   |
| Intel Core 2 Duo CPU P7500 @ 1.60GHz    | 1         | 1.67%   |
| Intel Core 2 Duo CPU L9400 @ 1.86GHz    | 1         | 1.67%   |
| Intel Core 2 Duo CPU L9300 @ 1.60GHz    | 1         | 1.67%   |
| Intel Core 2 Duo CPU L7500 @ 1.60GHz    | 1         | 1.67%   |
| Intel Celeron 2955U @ 1.40GHz           | 1         | 1.67%   |
| Intel Atom CPU D2550 @ 1.86GHz          | 1         | 1.67%   |
| Intel 12th Gen Core i7-1260P            | 1         | 1.67%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart_bsd/cpu_family.svg)


| Model              | Notebooks | Percent |
|--------------------|-----------|---------|
| Intel Core i7      | 19        | 31.67%  |
| Intel Core i5      | 12        | 20%     |
| Intel Core 2 Duo   | 6         | 10%     |
| AMD Ryzen Embedded | 3         | 5%      |
| AMD Ryzen 7        | 3         | 5%      |
| Intel Core i3      | 2         | 3.33%   |
| AMD E1             | 2         | 3.33%   |
| Other              | 1         | 1.67%   |
| Intel Pentium      | 1         | 1.67%   |
| Intel Core m7      | 1         | 1.67%   |
| Intel Core m3      | 1         | 1.67%   |
| Intel Celeron      | 1         | 1.67%   |
| Intel Atom         | 1         | 1.67%   |
| AMD Ryzen 5 PRO    | 1         | 1.67%   |
| AMD G              | 1         | 1.67%   |
| AMD EPYC           | 1         | 1.67%   |
| AMD E2             | 1         | 1.67%   |
| AMD Athlon II      | 1         | 1.67%   |
| AMD A8             | 1         | 1.67%   |
| AMD A6             | 1         | 1.67%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart_bsd/cpu_cores.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 34        | 56.67%  |
| 4       | 11        | 18.33%  |
| 8       | 7         | 11.67%  |
| Unknown | 4         | 6.67%   |
| 16      | 2         | 3.33%   |
| 6       | 2         | 3.33%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart_bsd/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 59        | 98.33%  |
| 2      | 1         | 1.67%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart_bsd/cpu_threads.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 37        | 61.67%  |
| 1       | 19        | 31.67%  |
| Unknown | 4         | 6.67%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart_bsd/cpu_microarch.svg)


| Name        | Notebooks | Percent |
|-------------|-----------|---------|
| KabyLake    | 9         | 15%     |
| IvyBridge   | 7         | 11.67%  |
| Haswell     | 6         | 10%     |
| Zen         | 5         | 8.33%   |
| Skylake     | 5         | 8.33%   |
| Broadwell   | 5         | 8.33%   |
| Penryn      | 4         | 6.67%   |
| SandyBridge | 3         | 5%      |
| Zen 2       | 2         | 3.33%   |
| Jaguar      | 2         | 3.33%   |
| Core        | 2         | 3.33%   |
| Unknown     | 2         | 3.33%   |
| Silvermont  | 1         | 1.67%   |
| Piledriver  | 1         | 1.67%   |
| K10 Llano   | 1         | 1.67%   |
| K10         | 1         | 1.67%   |
| Excavator   | 1         | 1.67%   |
| CometLake   | 1         | 1.67%   |
| Bonnell     | 1         | 1.67%   |
| Bobcat      | 1         | 1.67%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart_bsd/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 44        | 70.97%  |
| AMD    | 12        | 19.35%  |
| Nvidia | 6         | 9.68%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart_bsd/gpu_model.svg)


| Model                                                                     | Notebooks | Percent |
|---------------------------------------------------------------------------|-----------|---------|
| Intel 3rd Gen Core processor Graphics Controller                          | 7         | 10.61%  |
| Intel Haswell-ULT Integrated Graphics Controller                          | 6         | 9.09%   |
| Intel HD Graphics 5500                                                    | 5         | 7.58%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller              | 4         | 6.06%   |
| Intel Skylake GT2 [HD Graphics 520]                                       | 3         | 4.55%   |
| Intel HD Graphics 620                                                     | 3         | 4.55%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                | 2         | 3.03%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)       | 2         | 3.03%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)         | 2         | 3.03%   |
| Intel HD Graphics 515                                                     | 2         | 3.03%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller | 2         | 3.03%   |
| AMD Renoir                                                                | 2         | 3.03%   |
| AMD Kabini [Radeon HD 8240 / R3 Series]                                   | 2         | 3.03%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                | 1         | 1.52%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                   | 1         | 1.52%   |
| Nvidia GM108M [GeForce 940M]                                              | 1         | 1.52%   |
| Nvidia GK107M [GeForce GT 650M Mac Edition]                               | 1         | 1.52%   |
| Nvidia GF108M [NVS 5400M]                                                 | 1         | 1.52%   |
| Nvidia GF108M [GeForce GT 540M]                                           | 1         | 1.52%   |
| Intel UHD Graphics 620                                                    | 1         | 1.52%   |
| Intel HD Graphics 630                                                     | 1         | 1.52%   |
| Intel CometLake-U GT2 [UHD Graphics]                                      | 1         | 1.52%   |
| Intel Comet Lake UHD Graphics                                             | 1         | 1.52%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                 | 1         | 1.52%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display              | 1         | 1.52%   |
| Intel Atom Processor D2xxx/N2xxx Integrated Graphics Controller           | 1         | 1.52%   |
| Intel Alder Lake-P Integrated Graphics Controller                         | 1         | 1.52%   |
| AMD Wrestler [Radeon HD 6310]                                             | 1         | 1.52%   |
| AMD Whistler [Radeon HD 6630M/6650M/6750M/7670M/7690M]                    | 1         | 1.52%   |
| AMD Trinity [Radeon HD 7640G]                                             | 1         | 1.52%   |
| AMD Sun PRO [Radeon HD 8570A/8570M]                                       | 1         | 1.52%   |
| AMD Sumo [Radeon HD 6520G]                                                | 1         | 1.52%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                  | 1         | 1.52%   |
| AMD Seymour [Radeon HD 6400M/7400M Series]                                | 1         | 1.52%   |
| AMD RS880M [Mobility Radeon HD 4225/4250]                                 | 1         | 1.52%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]          | 1         | 1.52%   |
| AMD Lucienne                                                              | 1         | 1.52%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart_bsd/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 33        | 54.1%   |
| 1 x AMD        | 10        | 16.39%  |
| 2 x Intel      | 6         | 9.84%   |
| Intel + Nvidia | 5         | 8.2%    |
| Other          | 4         | 6.56%   |
| 2 x AMD        | 2         | 3.28%   |
| 1 x Nvidia     | 1         | 1.64%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart_bsd/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 54        | 88.52%  |
| Unknown     | 5         | 8.2%    |
| Proprietary | 2         | 3.28%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart_bsd/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 52        | 85.25%  |
| 0.01-0.5   | 6         | 9.84%   |
| 0.51-1.0   | 2         | 3.28%   |
| 1.01-2.0   | 1         | 1.64%   |

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
| 1     | 46        | 76.67%  |
| 0     | 12        | 20%     |
| 2     | 2         | 3.33%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart_bsd/net_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 45        | 47.87%  |
| Realtek Semiconductor             | 22        | 23.4%   |
| Qualcomm Atheros                  | 7         | 7.45%   |
| Broadcom                          | 7         | 7.45%   |
| AMD                               | 4         | 4.26%   |
| TP-Link                           | 2         | 2.13%   |
| Sierra Wireless                   | 1         | 1.06%   |
| Ralink Technology                 | 1         | 1.06%   |
| Ralink                            | 1         | 1.06%   |
| HMD Global                        | 1         | 1.06%   |
| Hewlett-Packard                   | 1         | 1.06%   |
| Fibocom                           | 1         | 1.06%   |
| Ericsson Business Mobile Networks | 1         | 1.06%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart_bsd/net_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 15        | 12.61%  |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 5         | 4.2%    |
| Intel Wireless 7260                                               | 5         | 4.2%    |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter               | 4         | 3.36%   |
| Intel Wireless 8265 / 8275                                        | 4         | 3.36%   |
| Intel Wireless 7265                                               | 4         | 3.36%   |
| Intel Wi-Fi 6 AX200                                               | 4         | 3.36%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 4         | 3.36%   |
| Intel 82567LM Gigabit Network Connection                          | 4         | 3.36%   |
| AMD Family 17h Processor 10 Gb Ethernet Controller Port 0         | 4         | 3.36%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 3         | 2.52%   |
| Intel I211 Gigabit Network Connection                             | 3         | 2.52%   |
| Intel Ethernet Connection (3) I218-LM                             | 3         | 2.52%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 3         | 2.52%   |
| Broadcom BCM4331 802.11a/b/g/n                                    | 3         | 2.52%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 2         | 1.68%   |
| Intel Wireless-AC 9260                                            | 2         | 1.68%   |
| Intel Wireless 8260                                               | 2         | 1.68%   |
| Intel WiFi Link 5100                                              | 2         | 1.68%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection           | 2         | 1.68%   |
| Intel I210 Gigabit Network Connection                             | 2         | 1.68%   |
| Intel Ethernet Connection I218-LM                                 | 2         | 1.68%   |
| Intel Ethernet Connection (4) I219-LM                             | 2         | 1.68%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 2         | 1.68%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 2         | 1.68%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 2         | 1.68%   |
| TP-Link Wireless USB Adapter                                      | 1         | 0.84%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]        | 1         | 0.84%   |
| Sierra Wireless EM7455                                            | 1         | 0.84%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 1         | 0.84%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                           | 1         | 0.84%   |
| Ralink RT5370 Wireless Adapter                                    | 1         | 0.84%   |
| Ralink RT3592 Wireless 802.11abgn 2T/2R PCIe                      | 1         | 0.84%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                            | 1         | 0.84%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 1         | 0.84%   |
| Intel Wireless 3160                                               | 1         | 0.84%   |
| Intel Ethernet Connection I219-V                                  | 1         | 0.84%   |
| Intel Ethernet Connection I219-LM                                 | 1         | 0.84%   |
| Intel Ethernet Connection I218-V                                  | 1         | 0.84%   |
| Intel Ethernet Connection (6) I219-V                              | 1         | 0.84%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart_bsd/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 36        | 60%     |
| Qualcomm Atheros      | 7         | 11.67%  |
| Realtek Semiconductor | 6         | 10%     |
| Broadcom              | 6         | 10%     |
| TP-Link               | 2         | 3.33%   |
| Sierra Wireless       | 1         | 1.67%   |
| Ralink Technology     | 1         | 1.67%   |
| Ralink                | 1         | 1.67%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart_bsd/net_wireless_model.svg)


| Model                                                          | Notebooks | Percent |
|----------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 5         | 8.33%   |
| Intel Wireless 7260                                            | 5         | 8.33%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter            | 4         | 6.67%   |
| Intel Wireless 8265 / 8275                                     | 4         | 6.67%   |
| Intel Wireless 7265                                            | 4         | 6.67%   |
| Intel Wi-Fi 6 AX200                                            | 4         | 6.67%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 3         | 5%      |
| Broadcom BCM4331 802.11a/b/g/n                                 | 3         | 5%      |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 2         | 3.33%   |
| Intel Wireless-AC 9260                                         | 2         | 3.33%   |
| Intel Wireless 8260                                            | 2         | 3.33%   |
| Intel WiFi Link 5100                                           | 2         | 3.33%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection        | 2         | 3.33%   |
| Intel Comet Lake PCH-LP CNVi WiFi                              | 2         | 3.33%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                       | 2         | 3.33%   |
| TP-Link Wireless USB Adapter                                   | 1         | 1.67%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]     | 1         | 1.67%   |
| Sierra Wireless EM7455                                         | 1         | 1.67%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 1         | 1.67%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                        | 1         | 1.67%   |
| Ralink RT5370 Wireless Adapter                                 | 1         | 1.67%   |
| Ralink RT3592 Wireless 802.11abgn 2T/2R PCIe                   | 1         | 1.67%   |
| Intel Wireless 3160                                            | 1         | 1.67%   |
| Intel Centrino Ultimate-N 6300                                 | 1         | 1.67%   |
| Intel Centrino Advanced-N 6235                                 | 1         | 1.67%   |
| Intel Cannon Lake PCH CNVi WiFi                                | 1         | 1.67%   |
| Broadcom BCM4321 802.11a/b/g/n                                 | 1         | 1.67%   |
| Broadcom BCM43142 802.11b/g/n                                  | 1         | 1.67%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter            | 1         | 1.67%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart_bsd/net_ethernet_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 27        | 48.21%  |
| Realtek Semiconductor | 18        | 32.14%  |
| Broadcom              | 4         | 7.14%   |
| AMD                   | 4         | 7.14%   |
| Qualcomm Atheros      | 2         | 3.57%   |
| HMD Global            | 1         | 1.79%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart_bsd/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 15        | 26.79%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 4         | 7.14%   |
| Intel 82567LM Gigabit Network Connection                          | 4         | 7.14%   |
| AMD Family 17h Processor 10 Gb Ethernet Controller Port 0         | 4         | 7.14%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 3         | 5.36%   |
| Intel I211 Gigabit Network Connection                             | 3         | 5.36%   |
| Intel Ethernet Connection (3) I218-LM                             | 3         | 5.36%   |
| Intel I210 Gigabit Network Connection                             | 2         | 3.57%   |
| Intel Ethernet Connection I218-LM                                 | 2         | 3.57%   |
| Intel Ethernet Connection (4) I219-LM                             | 2         | 3.57%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 2         | 3.57%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                            | 1         | 1.79%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 1         | 1.79%   |
| Intel Ethernet Connection I219-V                                  | 1         | 1.79%   |
| Intel Ethernet Connection I219-LM                                 | 1         | 1.79%   |
| Intel Ethernet Connection I218-V                                  | 1         | 1.79%   |
| Intel Ethernet Connection (6) I219-V                              | 1         | 1.79%   |
| Intel Ethernet Connection (6) I219-LM                             | 1         | 1.79%   |
| Intel 82574L Gigabit Network Connection                           | 1         | 1.79%   |
| Intel 82566MM Gigabit Network Connection                          | 1         | 1.79%   |
| HMD Global Nokia 5.3 RNDIS Control RNDIS Ethernet Data            | 1         | 1.79%   |
| Broadcom NetXtreme BCM57786 Gigabit Ethernet PCIe                 | 1         | 1.79%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                  | 1         | 1.79%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart_bsd/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 51        | 48.57%  |
| Ethernet | 51        | 48.57%  |
| Modem    | 2         | 1.9%    |
| Unknown  | 1         | 0.95%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart_bsd/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 39        | 50.65%  |
| Ethernet | 38        | 49.35%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart_bsd/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 43        | 71.67%  |
| 1     | 12        | 20%     |
| 5     | 3         | 5%      |
| 6     | 2         | 3.33%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart_bsd/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 48        | 78.69%  |
| Yes  | 13        | 21.31%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart_bsd/bt_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 23        | 60.53%  |
| Apple                 | 4         | 10.53%  |
| IMC Networks          | 3         | 7.89%   |
| Broadcom              | 3         | 7.89%   |
| Realtek Semiconductor | 1         | 2.63%   |
| Lite-On Technology    | 1         | 2.63%   |
| Hewlett-Packard       | 1         | 2.63%   |
| Foxconn / Hon Hai     | 1         | 2.63%   |
| Dell                  | 1         | 2.63%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart_bsd/bt_model.svg)


| Model                                                  | Notebooks | Percent |
|--------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                     | 11        | 28.95%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)         | 4         | 10.53%  |
| Intel AX200 Bluetooth                                  | 4         | 10.53%  |
| Intel Wireless-AC 9260 Bluetooth Adapter               | 2         | 5.26%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]             | 2         | 5.26%   |
| Apple Bluetooth Host Controller                        | 2         | 5.26%   |
| Realtek Bluetooth Adapter                              | 1         | 2.63%   |
| Lite-On Atheros AR3012 Bluetooth                       | 1         | 2.63%   |
| Intel Centrino Bluetooth Wireless Transceiver          | 1         | 2.63%   |
| Intel AX201 Bluetooth                                  | 1         | 2.63%   |
| IMC Networks Qualcomm Atheros Bluetooth 4.0 + HS       | 1         | 2.63%   |
| IMC Networks Qualcomm Atheros Bluetooth 4.0            | 1         | 2.63%   |
| IMC Networks Asus Integrated Bluetooth module [AR3011] | 1         | 2.63%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]          | 1         | 2.63%   |
| Foxconn / Hon Hai BCM43142A0 broadcom bluetooth        | 1         | 2.63%   |
| Dell Dell Wireless 380 Bluetooth 4.0 Module            | 1         | 2.63%   |
| Broadcom BCM2070 Bluetooth 2.1 + EDR                   | 1         | 2.63%   |
| Apple Broadcom Built-in Bluetooth                      | 1         | 2.63%   |
| Apple Broadcom Bluetooth 2.1 module                    | 1         | 2.63%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart_bsd/snd_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 44        | 70.97%  |
| AMD    | 16        | 25.81%  |
| Nvidia | 2         | 3.23%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart_bsd/snd_model.svg)


| Model                                                                             | Notebooks | Percent |
|-----------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                                   | 8         | 9.52%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller               | 7         | 8.33%   |
| AMD Family 17h/19h HD Audio Controller                                            | 7         | 8.33%   |
| Intel Haswell-ULT HD Audio Controller                                             | 6         | 7.14%   |
| Intel 8 Series HD Audio Controller                                                | 6         | 7.14%   |
| Intel Wildcat Point-LP High Definition Audio Controller                           | 5         | 5.95%   |
| Intel Broadwell-U Audio Controller                                                | 5         | 5.95%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                    | 4         | 4.76%   |
| AMD FCH Azalia Controller                                                         | 4         | 4.76%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller        | 3         | 3.57%   |
| AMD Renoir Radeon High Definition Audio Controller                                | 3         | 3.57%   |
| Intel Comet Lake PCH-LP cAVS                                                      | 2         | 2.38%   |
| Intel Cannon Point-LP High Definition Audio Controller                            | 2         | 2.38%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                    | 2         | 2.38%   |
| AMD SBx00 Azalia (Intel HDA)                                                      | 2         | 2.38%   |
| AMD Kabini HDMI/DP Audio                                                          | 2         | 2.38%   |
| Nvidia GK107 HDMI Audio Controller                                                | 1         | 1.19%   |
| Nvidia GF108 High Definition Audio Controller                                     | 1         | 1.19%   |
| Intel CM238 HD Audio Controller                                                   | 1         | 1.19%   |
| Intel Cannon Lake PCH cAVS                                                        | 1         | 1.19%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller        | 1         | 1.19%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                           | 1         | 1.19%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                  | 1         | 1.19%   |
| AMD Wrestler HDMI Audio                                                           | 1         | 1.19%   |
| AMD Trinity HDMI Audio Controller                                                 | 1         | 1.19%   |
| AMD RS880 HDMI Audio [Radeon HD 4200 Series]                                      | 1         | 1.19%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                               | 1         | 1.19%   |
| AMD High Definition Audio Controller                                              | 1         | 1.19%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                               | 1         | 1.19%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                  | 1         | 1.19%   |
| AMD Caicos HDMI Audio [Radeon HD 6450 / 7450/8450/8490 OEM / R5 230/235/235X OEM] | 1         | 1.19%   |
| AMD BeaverCreek HDMI Audio [Radeon HD 6500D and 6400G-6600G series]               | 1         | 1.19%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart_bsd/memory_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Samsung Electronics   | 13        | 22.03%  |
| Micron Technology     | 10        | 16.95%  |
| SK hynix              | 8         | 13.56%  |
| Unknown               | 4         | 6.78%   |
| Transcend             | 4         | 6.78%   |
| Crucial               | 4         | 6.78%   |
| Kingston              | 3         | 5.08%   |
| Elpida                | 3         | 5.08%   |
| Ramaxel Technology    | 2         | 3.39%   |
| Apacer                | 2         | 3.39%   |
| Team                  | 1         | 1.69%   |
| Nanya Technology      | 1         | 1.69%   |
| Kingmax Semiconductor | 1         | 1.69%   |
| G.Skill               | 1         | 1.69%   |
| Corsair               | 1         | 1.69%   |
| A-DATA Technology     | 1         | 1.69%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart_bsd/memory_model.svg)


| Model                                                   | Notebooks | Percent |
|---------------------------------------------------------|-----------|---------|
| Transcend RAM TS1GLH64V6BL 8GB SODIMM DDR4 2667MT/s     | 3         | 5.08%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s   | 2         | 3.39%   |
| Elpida RAM EBJ41UF8BCS0-DJ-F 4GB SODIMM DDR3 1334MT/s   | 2         | 3.39%   |
| Unknown RAM Module 8GB SODIMM LPDDR3 1867MT/s           | 1         | 1.69%   |
| Unknown RAM Module 4GB SODIMM DDR3                      | 1         | 1.69%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s              | 1         | 1.69%   |
| Unknown RAM Module 1GB SODIMM DDR2 667MT/s              | 1         | 1.69%   |
| Transcend RAM TS512MLH64V6HL 4GB SODIMM DDR4 2667MT/s   | 1         | 1.69%   |
| Team RAM TEAMGROUP-SD4-2400 8GB SODIMM DDR4 2400MT/s    | 1         | 1.69%   |
| SK hynix RAM Module 4GB SODIMM DDR3 1600MT/s            | 1         | 1.69%   |
| SK hynix RAM Module 4096MB SODIMM DDR3 1333MT/s         | 1         | 1.69%   |
| SK hynix RAM HMT451S6MFR8A-PB 4GB SODIMM DDR3 800MT/s   | 1         | 1.69%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s  | 1         | 1.69%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s  | 1         | 1.69%   |
| SK hynix RAM HMT41GS6AFR8A-PB 8GB SODIMM DDR3 1600MT/s  | 1         | 1.69%   |
| SK hynix RAM HMT351S6EFR8C-PB 4GB SODIMM DDR3 1600MT/s  | 1         | 1.69%   |
| SK hynix RAM HMT351S6CFR8A-PB 4GB SODIMM DDR3 1333MT/s  | 1         | 1.69%   |
| Samsung RAM Module 8GB SODIMM DDR4 2133MT/s             | 1         | 1.69%   |
| Samsung RAM Module 8GB Row Of Chips LPDDR3 2133MT/s     | 1         | 1.69%   |
| Samsung RAM M471B5673FH0-CH9 2GB SODIMM DDR3 1334MT/s   | 1         | 1.69%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s   | 1         | 1.69%   |
| Samsung RAM M471B5174BM0-YK0 4GB SODIMM DDR3 1600MT/s   | 1         | 1.69%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1867MT/s   | 1         | 1.69%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s   | 1         | 1.69%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 2667MT/s   | 1         | 1.69%   |
| Samsung RAM M471A4G43AB1-CWE 32GB SODIMM DDR4 3200MT/s  | 1         | 1.69%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s   | 1         | 1.69%   |
| Samsung RAM K4E6E304EB-EGCF 4GB 1867MT/s                | 1         | 1.69%   |
| Ramaxel RAM RMT3170MN68F9F1600 4GB SODIMM DDR3 1600MT/s | 1         | 1.69%   |
| Ramaxel RAM RMT3020EF48E8W1333 2GB SODIMM DDR3 1334MT/s | 1         | 1.69%   |
| Nanya RAM NT2GC64B8HA1NS-BE 2GB SODIMM DDR3 1067MT/s    | 1         | 1.69%   |
| Micron RAM MT41K512M16TNA-125 4GB Chip DDR3 1600MT/s    | 1         | 1.69%   |
| Micron RAM 8KTS51264HDZ-1G6E1 4GB Chip DDR3 1600MT/s    | 1         | 1.69%   |
| Micron RAM 8KTF51264HDZ-1G6E1 4GB SODIMM DDR3 1600MT/s  | 1         | 1.69%   |
| Micron RAM 4ATS1G64HZ-2G6E1 8GB SODIMM DDR4 2667MT/s    | 1         | 1.69%   |
| Micron RAM 4ATF51264HZ-2G3BZ 8GB SODIMM DDR4 2667MT/s   | 1         | 1.69%   |
| Micron RAM 16KTF51264HZ-1G6M1 4GB SODIMM DDR3 1600MT/s  | 1         | 1.69%   |
| Micron RAM 16KTF1G64HZ-1G9P1 8GB SODIMM DDR3 1866MT/s   | 1         | 1.69%   |
| Micron RAM 16KTF1G64HZ-1G9P1 8GB Chip DDR3 1867MT/s     | 1         | 1.69%   |
| Micron RAM 16HTF51264HZ-800C1 4GB SODIMM DDR2 800MT/s   | 1         | 1.69%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart_bsd/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR3    | 28        | 54.9%   |
| DDR4    | 17        | 33.33%  |
| DDR2    | 3         | 5.88%   |
| LPDDR3  | 2         | 3.92%   |
| Unknown | 1         | 1.96%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart_bsd/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 47        | 90.38%  |
| Chip         | 3         | 5.77%   |
| Row Of Chips | 1         | 1.92%   |
| Unknown      | 1         | 1.92%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart_bsd/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 4096  | 23        | 41.07%  |
| 8192  | 18        | 32.14%  |
| 2048  | 7         | 12.5%   |
| 16384 | 6         | 10.71%  |
| 32768 | 1         | 1.79%   |
| 1024  | 1         | 1.79%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart_bsd/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 1600    | 15        | 28.3%   |
| 2667    | 9         | 16.98%  |
| 2400    | 4         | 7.55%   |
| 1867    | 4         | 7.55%   |
| 1334    | 4         | 7.55%   |
| 1333    | 4         | 7.55%   |
| 3200    | 2         | 3.77%   |
| 2133    | 2         | 3.77%   |
| 1866    | 2         | 3.77%   |
| 800     | 2         | 3.77%   |
| 667     | 2         | 3.77%   |
| 1067    | 1         | 1.89%   |
| 1066    | 1         | 1.89%   |
| Unknown | 1         | 1.89%   |

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
| Chicony Electronics                    | 14        | 34.15%  |
| Realtek Semiconductor                  | 6         | 14.63%  |
| IMC Networks                           | 4         | 9.76%   |
| Microdia                               | 3         | 7.32%   |
| Lite-On Technology                     | 3         | 7.32%   |
| Bison Electronics                      | 3         | 7.32%   |
| Apple                                  | 3         | 7.32%   |
| Alcor Micro                            | 2         | 4.88%   |
| Sunplus Innovation Technology          | 1         | 2.44%   |
| Ricoh                                  | 1         | 2.44%   |
| Cheng Uei Precision Industry (Foxlink) | 1         | 2.44%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart_bsd/camera_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Chicony Integrated Camera                     | 3         | 7.32%   |
| Realtek USB Camera                            | 2         | 4.88%   |
| Realtek Integrated_Webcam_HD                  | 2         | 4.88%   |
| Microdia Integrated_Webcam_HD                 | 2         | 4.88%   |
| Lite-On Integrated Camera                     | 2         | 4.88%   |
| IMC Networks Integrated Camera                | 2         | 4.88%   |
| Chicony Realtek DMFT RGB                      | 2         | 4.88%   |
| Chicony Chicony USB2.0 Camera                 | 2         | 4.88%   |
| Bison Integrated Camera                       | 2         | 4.88%   |
| Apple FaceTime HD Camera                      | 2         | 4.88%   |
| Sunplus Laptop Integrated Webcam HD           | 1         | 2.44%   |
| Ricoh USB2.0 Camera                           | 1         | 2.44%   |
| Realtek Lenovo EasyCamera                     | 1         | 2.44%   |
| Realtek Integrated Webcam HD                  | 1         | 2.44%   |
| Microdia Dell Integrated HD Webcam            | 1         | 2.44%   |
| Lite-On TOSHIBA Web Camera - HD               | 1         | 2.44%   |
| IMC Networks USB2.0 HD UVC WebCam             | 1         | 2.44%   |
| IMC Networks EasyCamera                       | 1         | 2.44%   |
| Chicony VGA Webcam                            | 1         | 2.44%   |
| Chicony thinkpad t430s camera                 | 1         | 2.44%   |
| Chicony Integrated IR Camera                  | 1         | 2.44%   |
| Chicony Integrated Camera (1280x720@30)       | 1         | 2.44%   |
| Chicony HP Webcam [2 MP]                      | 1         | 2.44%   |
| Chicony HD WebCam (Acer)                      | 1         | 2.44%   |
| Chicony HD Webcam                             | 1         | 2.44%   |
| Cheng Uei Precision Industry (Foxlink) Webcam | 1         | 2.44%   |
| Bison Lenovo EasyCamera                       | 1         | 2.44%   |
| Apple FaceTime HD Camera (Built-in)           | 1         | 2.44%   |
| Alcor Micro ASUS USB2.0 WebCam                | 1         | 2.44%   |
| Alcor Micro Asus Integrated Webcam            | 1         | 2.44%   |

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
| 1     | 28        | 45.9%   |
| 0     | 13        | 21.31%  |
| 2     | 9         | 14.75%  |
| 3     | 7         | 11.48%  |
| 4     | 4         | 6.56%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart_bsd/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Communication controller | 38        | 50%     |
| Card reader              | 11        | 14.47%  |
| Net/wireless             | 9         | 11.84%  |
| Bluetooth                | 7         | 9.21%   |
| Fingerprint reader       | 6         | 7.89%   |
| Firewire controller      | 2         | 2.63%   |
| Sound                    | 1         | 1.32%   |
| Net/ethernet             | 1         | 1.32%   |
| Graphics card            | 1         | 1.32%   |

