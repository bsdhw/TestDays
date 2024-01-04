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

Total: 98

| Vendor        | Model                       | Probe                                                     | Date         |
|---------------|-----------------------------|-----------------------------------------------------------|--------------|
| Lenovo        | IdeaPad 5 15ALC05 82LN      | [f34b5d84dd](https://bsd-hardware.info/?probe=f34b5d84dd) | Dec 28, 2023 |
| Lenovo        | ThinkPad W520 4284GZ1       | [533a831b97](https://bsd-hardware.info/?probe=533a831b97) | Dec 26, 2023 |
| Deciso        | NetBoard-A10                | [c728132d77](https://bsd-hardware.info/?probe=c728132d77) | Dec 20, 2023 |
| ASUSTek       | ZenBook UX482EA_UX482EA     | [b5bbc08efe](https://bsd-hardware.info/?probe=b5bbc08efe) | Dec 07, 2023 |
| Deciso        | OPNsense Appliance          | [cb6b022d45](https://bsd-hardware.info/?probe=cb6b022d45) | Dec 04, 2023 |
| Deciso        | OPNsense Appliance          | [9508bd06f5](https://bsd-hardware.info/?probe=9508bd06f5) | Oct 28, 2023 |
| Deciso        | OPNsense Appliance          | [d9f0644c56](https://bsd-hardware.info/?probe=d9f0644c56) | Oct 24, 2023 |
| HP            | OMEN by Laptop              | [f0fc4f47b8](https://bsd-hardware.info/?probe=f0fc4f47b8) | Sep 10, 2023 |
| Lenovo        | IdeaPad Gaming 3 15IHU6 ... | [a308c3a87b](https://bsd-hardware.info/?probe=a308c3a87b) | Aug 31, 2023 |
| SLIMBOOK      | PROX-AMD5                   | [d4265533e2](https://bsd-hardware.info/?probe=d4265533e2) | Jul 15, 2023 |
| Lenovo        | ThinkPad W520 4284GZ1       | [7119cd7ae3](https://bsd-hardware.info/?probe=7119cd7ae3) | Jul 08, 2023 |
| Lenovo        | ThinkPad W520 4284GZ1       | [f74b33bc25](https://bsd-hardware.info/?probe=f74b33bc25) | Jul 03, 2023 |
| Lenovo        | ThinkPad W520 4284GZ1       | [f9f815c60e](https://bsd-hardware.info/?probe=f9f815c60e) | Jul 02, 2023 |
| Lenovo        | ThinkPad W520 4284GZ1       | [39e46fd477](https://bsd-hardware.info/?probe=39e46fd477) | Jul 02, 2023 |
| HP            | EliteBook 840 G3            | [17834256ca](https://bsd-hardware.info/?probe=17834256ca) | Jun 28, 2023 |
| Deciso        | OPNsense Appliance          | [be0008eb2a](https://bsd-hardware.info/?probe=be0008eb2a) | Jun 26, 2023 |
| Lenovo        | ThinkPad W520 4284GZ1       | [d194e8bc0d](https://bsd-hardware.info/?probe=d194e8bc0d) | Jun 22, 2023 |
| Deciso        | OPNsense Appliance          | [43936f5f1c](https://bsd-hardware.info/?probe=43936f5f1c) | Jun 15, 2023 |
| Deciso        | OPNsense Appliance          | [c47f62b522](https://bsd-hardware.info/?probe=c47f62b522) | May 28, 2023 |
| Apple         | MacBookPro10,1              | [643f7277de](https://bsd-hardware.info/?probe=643f7277de) | May 21, 2023 |
| Medion        | Major X10                   | [99228fd9da](https://bsd-hardware.info/?probe=99228fd9da) | May 10, 2023 |
| Deciso        | OPNsense Appliance          | [2745eadfd9](https://bsd-hardware.info/?probe=2745eadfd9) | May 07, 2023 |
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
| helloSystem 0.7.0    | 8         | 10.13%  |
| helloSystem 0.5.0    | 6         | 7.59%   |
| FreeBSD 13.0-STABLE  | 5         | 6.33%   |
| helloSystem 0.8.1    | 4         | 5.06%   |
| helloSystem 0.8.0    | 4         | 5.06%   |
| helloSystem 0.6.0    | 3         | 3.8%    |
| helloSystem 0.3.0    | 3         | 3.8%    |
| OPNsense 22.10       | 2         | 2.53%   |
| OpenBSD 7.1          | 2         | 2.53%   |
| OpenBSD 6.9          | 2         | 2.53%   |
| OpenBSD 6.8          | 2         | 2.53%   |
| helloSystem 0.8.2    | 2         | 2.53%   |
| helloSystem 0.4.0    | 2         | 2.53%   |
| GhostBSD 22.06.18    | 2         | 2.53%   |
| FreeBSD 14.0-p4      | 2         | 2.53%   |
| FreeBSD 13.1-p4      | 2         | 2.53%   |
| FreeBSD 13.1         | 2         | 2.53%   |
| FreeBSD 13.0-p5      | 2         | 2.53%   |
| OPNsense 23.7.10     | 1         | 1.27%   |
| OPNsense 23.4.1      | 1         | 1.27%   |
| OPNsense 23.4        | 1         | 1.27%   |
| OPNsense 23.10       | 1         | 1.27%   |
| OPNsense 22.7.4      | 1         | 1.27%   |
| OPNsense 22.7.2      | 1         | 1.27%   |
| OPNsense 22.7.10     | 1         | 1.27%   |
| OPNsense 22.10.1     | 1         | 1.27%   |
| OPNsense 22.1.7      | 1         | 1.27%   |
| OPNsense 22.1.6      | 1         | 1.27%   |
| OPNsense 22.1        | 1         | 1.27%   |
| OPNsense 21.7.7      | 1         | 1.27%   |
| OPNsense 21.1.9      | 1         | 1.27%   |
| OpenBSD 7.2          | 1         | 1.27%   |
| OpenBSD 7.0          | 1         | 1.27%   |
| helloSystem 0.9.0    | 1         | 1.27%   |
| FreeBSD 14.0-CURRENT | 1         | 1.27%   |
| FreeBSD 13.2-p1      | 1         | 1.27%   |
| FreeBSD 13.2         | 1         | 1.27%   |
| FreeBSD 13.0-p2      | 1         | 1.27%   |
| FreeBSD 13.0-BETA1   | 1         | 1.27%   |
| FreeBSD 13.0         | 1         | 1.27%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart_bsd/os_family.svg)


| Name        | Notebooks | Percent |
|-------------|-----------|---------|
| helloSystem | 31        | 45.59%  |
| FreeBSD     | 19        | 27.94%  |
| OPNsense    | 8         | 11.76%  |
| OpenBSD     | 8         | 11.76%  |
| GhostBSD    | 2         | 2.94%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart_bsd/os_arch.svg)


| Name  | Notebooks | Percent |
|-------|-----------|---------|
| amd64 | 67        | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart_bsd/os_de.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| helloDesktop | 33        | 47.14%  |
| Console      | 11        | 15.71%  |
| MATE         | 5         | 7.14%   |
| fvwm         | 5         | 7.14%   |
| TWM          | 3         | 4.29%   |
| KDE5         | 3         | 4.29%   |
| GNOME        | 3         | 4.29%   |
| LXQt         | 2         | 2.86%   |
| i3           | 2         | 2.86%   |
| XFCE         | 1         | 1.43%   |
| GNUstep      | 1         | 1.43%   |
| AwesomeWM    | 1         | 1.43%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart_bsd/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 56        | 83.58%  |
| Console | 10        | 14.93%  |
| Wayland | 1         | 1.49%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart_bsd/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| SLiM    | 34        | 50%     |
| Console | 22        | 32.35%  |
| XDM     | 4         | 5.88%   |
| SDDM    | 3         | 4.41%   |
| LightDM | 3         | 4.41%   |
| GDM     | 2         | 2.94%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart_bsd/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| en_US   | 29        | 42.03%  |
| C       | 16        | 23.19%  |
| Unknown | 14        | 20.29%  |
| nl_NL   | 5         | 7.25%   |
| en      | 3         | 4.35%   |
| nl      | 1         | 1.45%   |
| fr_FR   | 1         | 1.45%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart_bsd/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 56        | 82.35%  |
| BIOS | 12        | 17.65%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart_bsd/os_filesystem.svg)


| Type   | Notebooks | Percent |
|--------|-----------|---------|
| Zfs    | 41        | 60.29%  |
| Cd9660 | 10        | 14.71%  |
| Ufs    | 9         | 13.24%  |
| Ffs    | 8         | 11.76%  |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart_bsd/os_part_scheme.svg)


| Type | Notebooks | Percent |
|------|-----------|---------|
| GPT  | 63        | 94.03%  |
| MBR  | 4         | 5.97%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart_bsd/node_vendor.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| Lenovo           | 22        | 32.84%  |
| Dell             | 9         | 13.43%  |
| Hewlett-Packard  | 6         | 8.96%   |
| Deciso           | 4         | 5.97%   |
| ASUSTek Computer | 4         | 5.97%   |
| Apple            | 4         | 5.97%   |
| Notebook         | 3         | 4.48%   |
| SLIMBOOK         | 2         | 2.99%   |
| Acer             | 2         | 2.99%   |
| Unknown          | 2         | 2.99%   |
| WYSE             | 1         | 1.49%   |
| TUXEDO           | 1         | 1.49%   |
| TOXIC by BTO     | 1         | 1.49%   |
| Toshiba          | 1         | 1.49%   |
| Star Labs        | 1         | 1.49%   |
| Sony             | 1         | 1.49%   |
| Medion           | 1         | 1.49%   |
| Intel            | 1         | 1.49%   |
| Google           | 1         | 1.49%   |

Model
-----

Motherboard model

![Model](./images/pie_chart_bsd/node_model.svg)


| Name                                     | Notebooks | Percent |
|------------------------------------------|-----------|---------|
| Unknown                                  | 3         | 4.48%   |
| HP EliteBook 840 G3                      | 2         | 2.99%   |
| Dell Latitude E4300                      | 2         | 2.99%   |
| Deciso OPNsense Appliance                | 2         | 2.99%   |
| Deciso NetBoard-A10                      | 2         | 2.99%   |
| WYSE Z CLASS                             | 1         | 1.49%   |
| TUXEDO Pulse 15 Gen1                     | 1         | 1.49%   |
| TOXIC by BTO 15CL872 1050TI              | 1         | 1.49%   |
| Toshiba Satellite C50-B                  | 1         | 1.49%   |
| Star Labs LabTop                         | 1         | 1.49%   |
| Sony SVZ1311C5E                          | 1         | 1.49%   |
| SLIMBOOK PROX-AMD5                       | 1         | 1.49%   |
| Notebook NS5x_NS7xPU                     | 1         | 1.49%   |
| Notebook NL5xRU                          | 1         | 1.49%   |
| Notebook N2x0WU                          | 1         | 1.49%   |
| Medion Major X10                         | 1         | 1.49%   |
| Lenovo Yoga 500-14IBD 80N4               | 1         | 1.49%   |
| Lenovo ThinkPad X61s 76693KG             | 1         | 1.49%   |
| Lenovo ThinkPad X280 20KESA000B          | 1         | 1.49%   |
| Lenovo ThinkPad X250 20CLS5BU00          | 1         | 1.49%   |
| Lenovo ThinkPad X250 20CLS59400          | 1         | 1.49%   |
| Lenovo ThinkPad X250 20CLS4WV08          | 1         | 1.49%   |
| Lenovo ThinkPad X230 2325IG2             | 1         | 1.49%   |
| Lenovo ThinkPad X230 23255Y4             | 1         | 1.49%   |
| Lenovo ThinkPad X200s 7470W1V            | 1         | 1.49%   |
| Lenovo ThinkPad X1 Carbon 7th 20QDCTO1WW | 1         | 1.49%   |
| Lenovo ThinkPad X1 Carbon 5th 20HRCTO1WW | 1         | 1.49%   |
| Lenovo ThinkPad W520 4284GZ1             | 1         | 1.49%   |
| Lenovo ThinkPad T490 20N2CTO1WW          | 1         | 1.49%   |
| Lenovo ThinkPad T440s 20ARS1B704         | 1         | 1.49%   |
| Lenovo ThinkPad T440 20B7S2LT00          | 1         | 1.49%   |
| Lenovo ThinkPad T430 2347G7G             | 1         | 1.49%   |
| Lenovo ThinkPad S1 Yoga 20CD0038MB       | 1         | 1.49%   |
| Lenovo ThinkPad A285 20MW000JMH          | 1         | 1.49%   |
| Lenovo IdeaPad Gaming 3 15IHU6 82K1      | 1         | 1.49%   |
| Lenovo IdeaPad 5 15ALC05 82LN            | 1         | 1.49%   |
| Lenovo IdeaPad 130-15AST 81H5            | 1         | 1.49%   |
| Lenovo G505s 20255                       | 1         | 1.49%   |
| Intel Milstead Platform                  | 1         | 1.49%   |
| HP OMEN by Laptop                        | 1         | 1.49%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart_bsd/node_model_family.svg)


| Name                 | Notebooks | Percent |
|----------------------|-----------|---------|
| Lenovo ThinkPad      | 17        | 25.37%  |
| Dell Latitude        | 7         | 10.45%  |
| HP EliteBook         | 4         | 5.97%   |
| Lenovo IdeaPad       | 3         | 4.48%   |
| Unknown              | 3         | 4.48%   |
| Deciso OPNsense      | 2         | 2.99%   |
| Deciso NetBoard-A10  | 2         | 2.99%   |
| Acer Aspire          | 2         | 2.99%   |
| WYSE Z               | 1         | 1.49%   |
| TUXEDO Pulse         | 1         | 1.49%   |
| TOXIC by BTO 15CL872 | 1         | 1.49%   |
| Toshiba Satellite    | 1         | 1.49%   |
| Star Labs LabTop     | 1         | 1.49%   |
| Sony SVZ1311C5E      | 1         | 1.49%   |
| SLIMBOOK PROX-AMD5   | 1         | 1.49%   |
| Notebook NS5x        | 1         | 1.49%   |
| Notebook NL5xRU      | 1         | 1.49%   |
| Notebook N2x0WU      | 1         | 1.49%   |
| Medion Major         | 1         | 1.49%   |
| Lenovo Yoga          | 1         | 1.49%   |
| Lenovo G505s         | 1         | 1.49%   |
| Intel Milstead       | 1         | 1.49%   |
| HP OMEN              | 1         | 1.49%   |
| HP 625               | 1         | 1.49%   |
| Google Cave          | 1         | 1.49%   |
| Dell XPS             | 1         | 1.49%   |
| Dell Inspiron        | 1         | 1.49%   |
| ASUS ZenBook         | 1         | 1.49%   |
| ASUS X751LB          | 1         | 1.49%   |
| ASUS X556UA          | 1         | 1.49%   |
| ASUS K53TA           | 1         | 1.49%   |
| Apple MacBookPro9    | 1         | 1.49%   |
| Apple MacBookPro8    | 1         | 1.49%   |
| Apple MacBookPro10   | 1         | 1.49%   |
| Apple MacBookAir1    | 1         | 1.49%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart_bsd/node_year.svg)


| Year    | Notebooks | Percent |
|---------|-----------|---------|
| 2022    | 9         | 13.43%  |
| 2019    | 6         | 8.96%   |
| 2018    | 6         | 8.96%   |
| 2015    | 6         | 8.96%   |
| 2012    | 6         | 8.96%   |
| 2021    | 5         | 7.46%   |
| 2020    | 5         | 7.46%   |
| 2014    | 5         | 7.46%   |
| 2016    | 4         | 5.97%   |
| 2013    | 3         | 4.48%   |
| 2011    | 3         | 4.48%   |
| 2017    | 2         | 2.99%   |
| 2009    | 2         | 2.99%   |
| 2008    | 2         | 2.99%   |
| Unknown | 2         | 2.99%   |
| 2010    | 1         | 1.49%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart_bsd/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 67        | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart_bsd/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 66        | 98.51%  |
| Yes  | 1         | 1.49%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart_bsd/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 8.01-16.0   | 31        | 46.27%  |
| 16.01-24.0  | 16        | 23.88%  |
| 4.01-8.0    | 13        | 19.4%   |
| 32.01-64.0  | 4         | 5.97%   |
| 64.01-256.0 | 2         | 2.99%   |
| 2.01-3.0    | 1         | 1.49%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart_bsd/node_ram_used.svg)


| Used GB  | Notebooks | Percent |
|----------|-----------|---------|
| 0.01-0.5 | 37        | 53.62%  |
| 0.51-1.0 | 19        | 27.54%  |
| 1.01-2.0 | 9         | 13.04%  |
| 3.01-4.0 | 2         | 2.9%    |
| 2.01-3.0 | 2         | 2.9%    |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart_bsd/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 43        | 62.32%  |
| 2      | 18        | 26.09%  |
| 3      | 4         | 5.8%    |
| 0      | 4         | 5.8%    |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart_bsd/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 55        | 82.09%  |
| Yes       | 12        | 17.91%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart_bsd/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 56        | 83.58%  |
| No        | 11        | 16.42%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart_bsd/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 58        | 86.57%  |
| No        | 9         | 13.43%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart_bsd/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 45        | 67.16%  |
| No        | 22        | 32.84%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart_bsd/node_location.svg)


| Country     | Notebooks | Percent |
|-------------|-----------|---------|
| Netherlands | 67        | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart_bsd/node_city.svg)


| City                    | Notebooks | Percent |
|-------------------------|-----------|---------|
| Amsterdam               | 15        | 20.83%  |
| Utrecht                 | 5         | 6.94%   |
| The Hague               | 3         | 4.17%   |
| Eindhoven               | 3         | 4.17%   |
| Papendrecht             | 2         | 2.78%   |
| Oosterhout              | 2         | 2.78%   |
| Oegstgeest              | 2         | 2.78%   |
| Hoogeveen               | 2         | 2.78%   |
| Groningen               | 2         | 2.78%   |
| 's-Hertogenbosch        | 2         | 2.78%   |
| Zwolle                  | 1         | 1.39%   |
| Woerdense Verlaat       | 1         | 1.39%   |
| Warmond                 | 1         | 1.39%   |
| Veendam                 | 1         | 1.39%   |
| Tilburg                 | 1         | 1.39%   |
| Rozenburg               | 1         | 1.39%   |
| Roosendaal              | 1         | 1.39%   |
| Rhoon                   | 1         | 1.39%   |
| Ouderkerk aan de Amstel | 1         | 1.39%   |
| Norg                    | 1         | 1.39%   |
| Munnikens-Vinkel        | 1         | 1.39%   |
| Lent                    | 1         | 1.39%   |
| Leiden                  | 1         | 1.39%   |
| Leeuwarden              | 1         | 1.39%   |
| Hoek van Holland        | 1         | 1.39%   |
| Hilversum               | 1         | 1.39%   |
| Haarlem                 | 1         | 1.39%   |
| Gouda                   | 1         | 1.39%   |
| Elim                    | 1         | 1.39%   |
| Ede                     | 1         | 1.39%   |
| Dronten                 | 1         | 1.39%   |
| Dordrecht               | 1         | 1.39%   |
| Diemen                  | 1         | 1.39%   |
| Deventer                | 1         | 1.39%   |
| Den Dolder              | 1         | 1.39%   |
| De Lutte                | 1         | 1.39%   |
| Cuijk                   | 1         | 1.39%   |
| Capelle aan den IJssel  | 1         | 1.39%   |
| Berghem                 | 1         | 1.39%   |
| Bergambacht             | 1         | 1.39%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart_bsd/drive_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 19        | 27     | 24.68%  |
| WDC                 | 8         | 8      | 10.39%  |
| Seagate             | 7         | 8      | 9.09%   |
| Crucial             | 6         | 8      | 7.79%   |
| Transcend           | 5         | 11     | 6.49%   |
| Toshiba             | 4         | 4      | 5.19%   |
| SanDisk             | 4         | 4      | 5.19%   |
| NVMe                | 3         | 4      | 3.9%    |
| Kingston            | 2         | 2      | 2.6%    |
| Intel               | 2         | 2      | 2.6%    |
| Hitachi             | 2         | 2      | 2.6%    |
| Gigabyte Technology | 2         | 3      | 2.6%    |
| Apple               | 2         | 3      | 2.6%    |
| Star Drive          | 1         | 1      | 1.3%    |
| SK hynix            | 1         | 1      | 1.3%    |
| Phison              | 1         | 1      | 1.3%    |
| OCZ                 | 1         | 1      | 1.3%    |
| Micron Technology   | 1         | 1      | 1.3%    |
| LITEON              | 1         | 1      | 1.3%    |
| Leven               | 1         | 1      | 1.3%    |
| HPE                 | 1         | 1      | 1.3%    |
| Hoodisk             | 1         | 2      | 1.3%    |
| HGST                | 1         | 1      | 1.3%    |
| China               | 1         | 1      | 1.3%    |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart_bsd/drive_model.svg)


| Model                            | Notebooks | Percent |
|----------------------------------|-----------|---------|
| WDC WD5000LPVX-22V0TT0 500GB     | 2         | 2.56%   |
| Transcend TS256GMTE652T2 256GB   | 2         | 2.56%   |
| Toshiba MQ04ABF100 1TB           | 2         | 2.56%   |
| Seagate ST500LM000-SSHD-8GB      | 2         | 2.56%   |
| Seagate ST1000LM049-2GH172 1TB   | 2         | 2.56%   |
| Samsung SSD 840 EVO 250GB        | 2         | 2.56%   |
| WDC WDS500G2B0C-00PXH0 500GB     | 1         | 1.28%   |
| WDC WDS500G2B0A 500GB            | 1         | 1.28%   |
| WDC WDS100T2B0B-00YS70 1TB       | 1         | 1.28%   |
| WDC WD15EARS-00Z5B1 1.5TB        | 1         | 1.28%   |
| WDC WD10SPZX-24Z10 1TB           | 1         | 1.28%   |
| WDC WD10SPZX-00Z10T0 1TB         | 1         | 1.28%   |
| Transcend TS512GMTS430S 512GB    | 1         | 1.28%   |
| Transcend TS256GMTS952T2 256GB   | 1         | 1.28%   |
| Transcend TS128GMTE110S 128GB    | 1         | 1.28%   |
| Toshiba THNSN5512GPUK NVMe 512GB | 1         | 1.28%   |
| Toshiba THNSFJ256GCSU 256GB      | 1         | 1.28%   |
| Star Drive PCIe SSD 960GB        | 1         | 1.28%   |
| SK hynix SC311 SATA 256GB        | 1         | 1.28%   |
| Seagate ST9250410AS 250GB        | 1         | 1.28%   |
| Seagate ST9160412ASG 160GB       | 1         | 1.28%   |
| Seagate ST500VT000-1DK142 500GB  | 1         | 1.28%   |
| SanDisk SD8SN8U-128G-1006 128GB  | 1         | 1.28%   |
| SanDisk SD8SBAT256G1002 256GB    | 1         | 1.28%   |
| SanDisk SD7UB3Q256G1001 256GB    | 1         | 1.28%   |
| SanDisk SD6SB1M064G 64GB         | 1         | 1.28%   |
| Samsung SSD PM851 mSATA 512GB    | 1         | 1.28%   |
| Samsung SSD PM841 mSATA 256GB    | 1         | 1.28%   |
| Samsung SSD 980 PRO 1TB          | 1         | 1.28%   |
| Samsung SSD 970 PRO 512GB        | 1         | 1.28%   |
| Samsung SSD 970 EVO 500GB        | 1         | 1.28%   |
| Samsung SSD 870 QVO 1TB          | 1         | 1.28%   |
| Samsung SSD 860 EVO 1TB          | 1         | 1.28%   |
| Samsung SSD 850 EVO 500GB        | 1         | 1.28%   |
| Samsung SSD 850 EVO 250GB        | 1         | 1.28%   |
| Samsung SSD 840 PRO Series 256GB | 1         | 1.28%   |
| Samsung SSD 840 EVO 120GB        | 1         | 1.28%   |
| Samsung SSD 830 Series 64GB      | 1         | 1.28%   |
| Samsung MZVLB256HAHQ-000H1 256GB | 1         | 1.28%   |
| Samsung MZVLB1T0HBLR-000L7 1TB   | 1         | 1.28%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart_bsd/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 7         | 8      | 38.89%  |
| WDC                 | 5         | 5      | 27.78%  |
| Toshiba             | 2         | 2      | 11.11%  |
| Hitachi             | 2         | 2      | 11.11%  |
| Samsung Electronics | 1         | 1      | 5.56%   |
| HGST                | 1         | 1      | 5.56%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart_bsd/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 13        | 20     | 31.71%  |
| Crucial             | 5         | 6      | 12.2%   |
| SanDisk             | 4         | 4      | 9.76%   |
| NVMe                | 3         | 4      | 7.32%   |
| WDC                 | 2         | 2      | 4.88%   |
| Transcend           | 2         | 7      | 4.88%   |
| Apple               | 2         | 3      | 4.88%   |
| Toshiba             | 1         | 1      | 2.44%   |
| SK hynix            | 1         | 1      | 2.44%   |
| OCZ                 | 1         | 1      | 2.44%   |
| LITEON              | 1         | 1      | 2.44%   |
| Leven               | 1         | 1      | 2.44%   |
| Intel               | 1         | 1      | 2.44%   |
| HPE                 | 1         | 1      | 2.44%   |
| Hoodisk             | 1         | 2      | 2.44%   |
| Gigabyte Technology | 1         | 1      | 2.44%   |
| China               | 1         | 1      | 2.44%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart_bsd/drive_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SSD  | 37        | 57     | 52.11%  |
| HDD  | 18        | 19     | 25.35%  |
| NVMe | 16        | 22     | 22.54%  |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart_bsd/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 52        | 76     | 76.47%  |
| NVMe | 16        | 22     | 23.53%  |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart_bsd/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 40        | 57     | 71.43%  |
| 0.51-1.0   | 15        | 18     | 26.79%  |
| 1.01-2.0   | 1         | 1      | 1.79%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart_bsd/drive_space_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 101-250    | 20        | 28.57%  |
| 1-20       | 17        | 24.29%  |
| 251-500    | 15        | 21.43%  |
| 501-1000   | 7         | 10%     |
| 51-100     | 6         | 8.57%   |
| 21-50      | 2         | 2.86%   |
| 1001-2000  | 2         | 2.86%   |
| Unknown    | 1         | 1.43%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart_bsd/drive_space_used.svg)


| Used GB  | Notebooks | Percent |
|----------|-----------|---------|
| 1-20     | 58        | 85.29%  |
| 251-500  | 2         | 2.94%   |
| 21-50    | 2         | 2.94%   |
| 101-250  | 2         | 2.94%   |
| 51-100   | 2         | 2.94%   |
| 501-1000 | 1         | 1.47%   |
| Unknown  | 1         | 1.47%   |

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
| Works    | 56        | 86     | 84.85%  |
| Malfunc  | 5         | 5      | 7.58%   |
| Detected | 4         | 6      | 6.06%   |
| Failed   | 1         | 1      | 1.52%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart_bsd/storage_vendor.svg)


| Vendor                      | Notebooks | Percent |
|-----------------------------|-----------|---------|
| Intel                       | 45        | 58.44%  |
| AMD                         | 12        | 15.58%  |
| Samsung Electronics         | 8         | 10.39%  |
| Transcend                   | 3         | 3.9%    |
| Phison Electronics          | 3         | 3.9%    |
| Kingston Technology Company | 2         | 2.6%    |
| Toshiba                     | 1         | 1.3%    |
| SanDisk                     | 1         | 1.3%    |
| Micron/Crucial Technology   | 1         | 1.3%    |
| Micron Technology           | 1         | 1.3%    |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart_bsd/storage_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                          | 10        | 11.9%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                               | 8         | 9.52%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                | 5         | 5.95%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                           | 5         | 5.95%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                 | 5         | 5.95%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]             | 5         | 5.95%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                           | 4         | 4.76%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller | 4         | 4.76%   |
| Transcend NVMe PCIe SSD 110S/112S/120S/MTE300S/MTE400S/MTE652T2 (DRAM-less)  | 3         | 3.57%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]        | 3         | 3.57%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                               | 2         | 2.38%   |
| Intel Volume Management Device NVMe RAID Controller                          | 2         | 2.38%   |
| Intel SSD DC P4101/Pro 7600p/760p/E 6100p Series                             | 2         | 2.38%   |
| Intel Comet Lake SATA AHCI Controller                                        | 2         | 2.38%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                | 2         | 2.38%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                             | 2         | 2.38%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                            | 2         | 2.38%   |
| Toshiba XG4 NVMe SSD Controller                                              | 1         | 1.19%   |
| SanDisk Ultra 3D / WD Blue SN550 NVMe SSD                                    | 1         | 1.19%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                  | 1         | 1.19%   |
| Phison PS5013-E13 PCIe3 NVMe Controller (DRAM-less)                          | 1         | 1.19%   |
| Phison E18 PCIe4 NVMe Controller                                             | 1         | 1.19%   |
| Phison E12 NVMe Controller                                                   | 1         | 1.19%   |
| Micron/Crucial P2 [Nick P2] / P3 / P3 Plus NVMe PCIe SSD (DRAM-less)         | 1         | 1.19%   |
| Micron 2210 NVMe SSD [Cobain]                                                | 1         | 1.19%   |
| Kingston Company NV2 NVMe SSD SM2267XT                                       | 1         | 1.19%   |
| Kingston Company A2000 NVMe SSD SM2263EN                                     | 1         | 1.19%   |
| Intel Tiger Lake-LP SATA Controller                                          | 1         | 1.19%   |
| Intel SSD 660P Series                                                        | 1         | 1.19%   |
| Intel Mobile 4 Series Chipset PT IDER Controller                             | 1         | 1.19%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                        | 1         | 1.19%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                            | 1         | 1.19%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                       | 1         | 1.19%   |
| Intel 82801JI (ICH10 Family) SATA AHCI Controller                            | 1         | 1.19%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 2 port SATA Controller [IDE mode]         | 1         | 1.19%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart_bsd/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 47        | 57.32%  |
| NVMe | 21        | 25.61%  |
| RAID | 10        | 12.2%   |
| IDE  | 4         | 4.88%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart_bsd/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 51        | 76.12%  |
| AMD    | 16        | 23.88%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart_bsd/cpu_model.svg)


| Model                                   | Notebooks | Percent |
|-----------------------------------------|-----------|---------|
| AMD Ryzen Embedded V1500B               | 3         | 4.48%   |
| Intel Core i7-8750H CPU @ 2.20GHz       | 2         | 2.99%   |
| Intel Core i7-7600U CPU @ 2.80GHz       | 2         | 2.99%   |
| Intel Core i7-4600U CPU @ 2.10GHz       | 2         | 2.99%   |
| Intel Core i7-4500U CPU @ 1.80GHz       | 2         | 2.99%   |
| Intel Core i7-3520M CPU @ 2.90GHz       | 2         | 2.99%   |
| Intel Core i7-2630QM CPU @ 2.00GHz      | 2         | 2.99%   |
| Intel Core i5-6300U CPU @ 2.40GHz       | 2         | 2.99%   |
| Intel Core i5-5300U CPU @ 2.30GHz       | 2         | 2.99%   |
| Intel Core i5-3210M CPU @ 2.50GHz       | 2         | 2.99%   |
| Intel Core 2 Duo                        | 2         | 2.99%   |
| AMD Ryzen 7 5700U with Radeon Graphics  | 2         | 2.99%   |
| AMD E1-2500 APU with Radeon HD Graphics | 2         | 2.99%   |
| Intel Pentium CPU N3530 @ 2.16GHz       | 1         | 1.49%   |
| Intel Core m7-6Y75 CPU @ 1.20GHz        | 1         | 1.49%   |
| Intel Core m3-6Y30 CPU @ 0.90GHz        | 1         | 1.49%   |
| Intel Core i7-8665U CPU @ 1.90GHz       | 1         | 1.49%   |
| Intel Core i7-8565U CPU @ 1.80GHz       | 1         | 1.49%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz      | 1         | 1.49%   |
| Intel Core i7-6500U CPU @ 2.50GHz       | 1         | 1.49%   |
| Intel Core i7-5600U CPU @ 2.60GHz       | 1         | 1.49%   |
| Intel Core i7-5500U CPU @ 2.40GHz       | 1         | 1.49%   |
| Intel Core i7-3615QM CPU @ 2.30GHz      | 1         | 1.49%   |
| Intel Core i7-3612QM CPU @ 2.10GHz      | 1         | 1.49%   |
| Intel Core i7-10710U CPU @ 1.10GHz      | 1         | 1.49%   |
| Intel Core i5-8350U CPU @ 1.70GHz       | 1         | 1.49%   |
| Intel Core i5-6200U CPU @ 2.30GHz       | 1         | 1.49%   |
| Intel Core i5-4200U CPU @ 1.60GHz       | 1         | 1.49%   |
| Intel Core i5-3320M CPU @ 2.60GHz       | 1         | 1.49%   |
| Intel Core i5-2520M CPU @ 2.50GHz       | 1         | 1.49%   |
| Intel Core i5-2435M CPU @ 2.40GHz       | 1         | 1.49%   |
| Intel Core i5-10210U CPU @ 1.60GHz      | 1         | 1.49%   |
| Intel Core i3-7100U CPU @ 2.40GHz       | 1         | 1.49%   |
| Intel Core i3-5005U CPU @ 2.00GHz       | 1         | 1.49%   |
| Intel Core 2 Duo CPU P7500 @ 1.60GHz    | 1         | 1.49%   |
| Intel Core 2 Duo CPU L9400 @ 1.86GHz    | 1         | 1.49%   |
| Intel Core 2 Duo CPU L9300 @ 1.60GHz    | 1         | 1.49%   |
| Intel Core 2 Duo CPU L7500 @ 1.60GHz    | 1         | 1.49%   |
| Intel Celeron 2955U @ 1.40GHz           | 1         | 1.49%   |
| Intel Atom CPU D2550 @ 1.86GHz          | 1         | 1.49%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart_bsd/cpu_family.svg)


| Model              | Notebooks | Percent |
|--------------------|-----------|---------|
| Intel Core i7      | 21        | 31.34%  |
| Intel Core i5      | 13        | 19.4%   |
| Intel Core 2 Duo   | 6         | 8.96%   |
| Other              | 4         | 5.97%   |
| AMD Ryzen 7        | 4         | 5.97%   |
| AMD Ryzen Embedded | 3         | 4.48%   |
| Intel Core i3      | 2         | 2.99%   |
| AMD E1             | 2         | 2.99%   |
| Intel Pentium      | 1         | 1.49%   |
| Intel Core m7      | 1         | 1.49%   |
| Intel Core m3      | 1         | 1.49%   |
| Intel Celeron      | 1         | 1.49%   |
| Intel Atom         | 1         | 1.49%   |
| AMD Ryzen 5 PRO    | 1         | 1.49%   |
| AMD G              | 1         | 1.49%   |
| AMD EPYC           | 1         | 1.49%   |
| AMD E2             | 1         | 1.49%   |
| AMD Athlon II      | 1         | 1.49%   |
| AMD A8             | 1         | 1.49%   |
| AMD A6             | 1         | 1.49%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart_bsd/cpu_cores.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 35        | 52.24%  |
| 4       | 14        | 20.9%   |
| 8       | 7         | 10.45%  |
| Unknown | 4         | 5.97%   |
| 16      | 3         | 4.48%   |
| 6       | 3         | 4.48%   |
| 20      | 1         | 1.49%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart_bsd/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 66        | 98.51%  |
| 2      | 1         | 1.49%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart_bsd/cpu_threads.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 42        | 62.69%  |
| 1       | 21        | 31.34%  |
| Unknown | 4         | 5.97%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart_bsd/cpu_microarch.svg)


| Name        | Notebooks | Percent |
|-------------|-----------|---------|
| KabyLake    | 10        | 14.93%  |
| IvyBridge   | 7         | 10.45%  |
| Skylake     | 6         | 8.96%   |
| Haswell     | 6         | 8.96%   |
| Zen         | 5         | 7.46%   |
| Broadwell   | 5         | 7.46%   |
| SandyBridge | 4         | 5.97%   |
| Penryn      | 4         | 5.97%   |
| Unknown     | 4         | 5.97%   |
| Zen 2       | 2         | 2.99%   |
| TigerLake   | 2         | 2.99%   |
| Jaguar      | 2         | 2.99%   |
| Core        | 2         | 2.99%   |
| Silvermont  | 1         | 1.49%   |
| Piledriver  | 1         | 1.49%   |
| K10 Llano   | 1         | 1.49%   |
| K10         | 1         | 1.49%   |
| Excavator   | 1         | 1.49%   |
| CometLake   | 1         | 1.49%   |
| Bonnell     | 1         | 1.49%   |
| Bobcat      | 1         | 1.49%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart_bsd/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 50        | 69.44%  |
| AMD    | 13        | 18.06%  |
| Nvidia | 9         | 12.5%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart_bsd/gpu_model.svg)


| Model                                                                     | Notebooks | Percent |
|---------------------------------------------------------------------------|-----------|---------|
| Intel 3rd Gen Core processor Graphics Controller                          | 7         | 9.09%   |
| Intel Haswell-ULT Integrated Graphics Controller                          | 6         | 7.79%   |
| Intel HD Graphics 5500                                                    | 5         | 6.49%   |
| Intel Skylake GT2 [HD Graphics 520]                                       | 4         | 5.19%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller              | 4         | 5.19%   |
| Intel HD Graphics 620                                                     | 3         | 3.9%    |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller | 3         | 3.9%    |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                   | 2         | 2.6%    |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                | 2         | 2.6%    |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                 | 2         | 2.6%    |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)       | 2         | 2.6%    |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)         | 2         | 2.6%    |
| Intel HD Graphics 515                                                     | 2         | 2.6%    |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                 | 2         | 2.6%    |
| Intel Alder Lake-P GT2 [Iris Xe Graphics]                                 | 2         | 2.6%    |
| AMD Renoir [Radeon RX Vega 6 (Ryzen 4000/5000 Mobile Series)]             | 2         | 2.6%    |
| AMD Lucienne                                                              | 2         | 2.6%    |
| AMD Kabini [Radeon HD 8240 / R3 Series]                                   | 2         | 2.6%    |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                           | 1         | 1.3%    |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                | 1         | 1.3%    |
| Nvidia GM108M [GeForce 940M]                                              | 1         | 1.3%    |
| Nvidia GK107M [GeForce GT 650M Mac Edition]                               | 1         | 1.3%    |
| Nvidia GF108M [NVS 5400M]                                                 | 1         | 1.3%    |
| Nvidia GF108M [GeForce GT 540M]                                           | 1         | 1.3%    |
| Nvidia GF108GLM [Quadro 1000M]                                            | 1         | 1.3%    |
| Intel UHD Graphics 620                                                    | 1         | 1.3%    |
| Intel HD Graphics 630                                                     | 1         | 1.3%    |
| Intel DG2 [Arc A730M]                                                     | 1         | 1.3%    |
| Intel CometLake-U GT2 [UHD Graphics]                                      | 1         | 1.3%    |
| Intel Comet Lake UHD Graphics                                             | 1         | 1.3%    |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display              | 1         | 1.3%    |
| Intel Atom Processor D2xxx/N2xxx Integrated Graphics Controller           | 1         | 1.3%    |
| AMD Wrestler [Radeon HD 6310]                                             | 1         | 1.3%    |
| AMD Whistler [Radeon HD 6630M/6650M/6750M/7670M/7690M]                    | 1         | 1.3%    |
| AMD Trinity [Radeon HD 7640G]                                             | 1         | 1.3%    |
| AMD Sun PRO [Radeon HD 8570A/8570M]                                       | 1         | 1.3%    |
| AMD Sumo [Radeon HD 6520G]                                                | 1         | 1.3%    |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                  | 1         | 1.3%    |
| AMD Seymour [Radeon HD 6400M/7400M Series]                                | 1         | 1.3%    |
| AMD RS880M [Mobility Radeon HD 4225/4250]                                 | 1         | 1.3%    |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart_bsd/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 36        | 52.17%  |
| 1 x AMD        | 11        | 15.94%  |
| Intel + Nvidia | 8         | 11.59%  |
| 2 x Intel      | 7         | 10.14%  |
| Other          | 4         | 5.8%    |
| 2 x AMD        | 2         | 2.9%    |
| 1 x Nvidia     | 1         | 1.45%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart_bsd/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 61        | 88.41%  |
| Unknown     | 5         | 7.25%   |
| Proprietary | 3         | 4.35%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart_bsd/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 58        | 85.29%  |
| 0.01-0.5   | 6         | 8.82%   |
| 1.01-2.0   | 2         | 2.94%   |
| 0.51-1.0   | 2         | 2.94%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart_bsd/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| LG Display              | 11        | 20.75%  |
| Chimei Innolux          | 9         | 16.98%  |
| AU Optronics            | 8         | 15.09%  |
| BOE                     | 7         | 13.21%  |
| Samsung Electronics     | 4         | 7.55%   |
| Apple                   | 4         | 7.55%   |
| Lenovo                  | 3         | 5.66%   |
| Sharp                   | 2         | 3.77%   |
| Sony                    | 1         | 1.89%   |
| Philips                 | 1         | 1.89%   |
| PANDA                   | 1         | 1.89%   |
| Chi Mei Optoelectronics | 1         | 1.89%   |
| AOC                     | 1         | 1.89%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart_bsd/mon_model.svg)


| Model                                                                    | Notebooks | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| LG Display LCD Monitor LGD11F9 1280x800 290x180mm 13.4-inch              | 2         | 3.77%   |
| Sony LCD SNY06FA 1600x900 290x160mm 13.0-inch                            | 1         | 1.89%   |
| Sharp LCD Monitor SHP1461 3200x1800 290x170mm 13.2-inch                  | 1         | 1.89%   |
| Sharp LCD Monitor SHP1453 1920x1080 350x190mm 15.7-inch                  | 1         | 1.89%   |
| Samsung Electronics LCD Monitor SEC4541 1280x800 260x160mm 12.0-inch     | 1         | 1.89%   |
| Samsung Electronics LCD Monitor SEC324C 1600x900 310x170mm 13.9-inch     | 1         | 1.89%   |
| Samsung Electronics LCD Monitor SEC3047 1366x768 280x160mm 12.7-inch     | 1         | 1.89%   |
| Samsung Electronics LCD Monitor SDC4347 1366x768 340x190mm 15.3-inch     | 1         | 1.89%   |
| Philips PHL 328E1 PHLC204 3840x2160 700x390mm 31.5-inch                  | 1         | 1.89%   |
| PANDA LC133LF1L02 NCP0019 1920x1080 290x170mm 13.2-inch                  | 1         | 1.89%   |
| LG Display LCD Monitor LGD05C0 1920x1080 344x194mm 15.5-inch             | 1         | 1.89%   |
| LG Display LCD Monitor LGD058B 2560x1440 310x170mm 13.9-inch             | 1         | 1.89%   |
| LG Display LCD Monitor LGD0450 1366x768 280x160mm 12.7-inch              | 1         | 1.89%   |
| LG Display LCD Monitor LGD0437 1920x1080 280x160mm 12.7-inch             | 1         | 1.89%   |
| LG Display LCD Monitor LGD0414 1920x1080 280x160mm 12.7-inch             | 1         | 1.89%   |
| LG Display LCD Monitor LGD0408 1920x1080 280x160mm 12.7-inch             | 1         | 1.89%   |
| LG Display LCD Monitor LGD03ED 1366x768 280x160mm 12.7-inch              | 1         | 1.89%   |
| LG Display LCD Monitor LGD02D8 1366x768 280x160mm 12.7-inch              | 1         | 1.89%   |
| LG Display LCD Monitor LGD02AD 1366x768 340x190mm 15.3-inch              | 1         | 1.89%   |
| Lenovo LCD Monitor LEN40B1 1600x900 340x190mm 15.3-inch                  | 1         | 1.89%   |
| Lenovo LCD Monitor LEN4010 1280x800 260x160mm 12.0-inch                  | 1         | 1.89%   |
| Lenovo LCD Monitor LEN4000 1024x768 250x180mm 12.1-inch                  | 1         | 1.89%   |
| Chimei Innolux LCD Monitor CMN175A 1920x1080 380x210mm 17.1-inch         | 1         | 1.89%   |
| Chimei Innolux LCD Monitor CMN1734 1600x900 380x210mm 17.1-inch          | 1         | 1.89%   |
| Chimei Innolux LCD Monitor CMN15C9 1366x768 340x190mm 15.3-inch          | 1         | 1.89%   |
| Chimei Innolux LCD Monitor CMN15BF 1366x768 340x190mm 15.3-inch          | 1         | 1.89%   |
| Chimei Innolux LCD Monitor CMN15B5 1366x768 340x190mm 15.3-inch          | 1         | 1.89%   |
| Chimei Innolux LCD Monitor CMN152D 1920x1080 340x190mm 15.3-inch         | 1         | 1.89%   |
| Chimei Innolux LCD Monitor CMN1490 1366x768 310x170mm 13.9-inch          | 1         | 1.89%   |
| Chimei Innolux LCD Monitor CMN1404 1920x1080 310x170mm 13.9-inch         | 1         | 1.89%   |
| Chimei Innolux LCD Monitor CMN1239 1920x1080 280x160mm 12.7-inch         | 1         | 1.89%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A7 1366x768 350x190mm 15.7-inch | 1         | 1.89%   |
| BOE LCD Monitor BOE0A81 1920x1080 340x190mm 15.3-inch                    | 1         | 1.89%   |
| BOE LCD Monitor BOE0921 1920x515 310x80mm 12.6-inch                      | 1         | 1.89%   |
| BOE LCD Monitor BOE07F7 1920x1080 310x170mm 13.9-inch                    | 1         | 1.89%   |
| BOE LCD Monitor BOE07D8 1920x1080 340x190mm 15.3-inch                    | 1         | 1.89%   |
| BOE LCD Monitor BOE07C8 3840x2160 310x170mm 13.9-inch                    | 1         | 1.89%   |
| BOE LCD Monitor BOE06BF 1920x1080 280x160mm 12.7-inch                    | 1         | 1.89%   |
| BOE LCD Monitor BOE0675 1366x768 340x190mm 15.3-inch                     | 1         | 1.89%   |
| AU Optronics LCD Monitor AUOE48D 1920x1080 340x190mm 15.3-inch           | 1         | 1.89%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart_bsd/mon_resolution.svg)


| Resolution       | Notebooks | Percent |
|------------------|-----------|---------|
| 1920x1080 (FHD)  | 20        | 37.74%  |
| 1366x768 (WXGA)  | 13        | 24.53%  |
| 1280x800 (WXGA)  | 7         | 13.21%  |
| 1600x900 (HD+)   | 5         | 9.43%   |
| 3840x2160 (4K)   | 3         | 5.66%   |
| 2560x1440 (QHD)  | 2         | 3.77%   |
| 3200x1800 (QHD+) | 1         | 1.89%   |
| 2880x1800        | 1         | 1.89%   |
| 1920x515         | 1         | 1.89%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart_bsd/mon_diagonal.svg)


| Inches | Notebooks | Percent |
|--------|-----------|---------|
| 13     | 18        | 33.96%  |
| 15     | 16        | 30.19%  |
| 12     | 14        | 26.42%  |
| 17     | 2         | 3.77%   |
| 31     | 1         | 1.89%   |
| 27     | 1         | 1.89%   |
| 23     | 1         | 1.89%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart_bsd/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 26        | 50%     |
| 201-300     | 21        | 40.38%  |
| 601-700     | 2         | 3.85%   |
| 351-400     | 2         | 3.85%   |
| 501-600     | 1         | 1.92%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart_bsd/mon_ratio.svg)


| Ratio | Notebooks | Percent |
|-------|-----------|---------|
| 16/9  | 43        | 82.69%  |
| 16/10 | 7         | 13.46%  |
| 3/2   | 1         | 1.92%   |
| 3.88  | 1         | 1.92%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart_bsd/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 81-90          | 15        | 28.3%   |
| 61-70          | 13        | 24.53%  |
| 91-100         | 11        | 20.75%  |
| 101-110        | 5         | 9.43%   |
| 71-80          | 3         | 5.66%   |
| 121-130        | 2         | 3.77%   |
| 351-500        | 1         | 1.89%   |
| 1-40           | 1         | 1.89%   |
| 301-350        | 1         | 1.89%   |
| 201-250        | 1         | 1.89%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart_bsd/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 23        | 45.1%   |
| 101-120       | 14        | 27.45%  |
| 161-240       | 10        | 19.61%  |
| More than 240 | 2         | 3.92%   |
| 51-100        | 2         | 3.92%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart_bsd/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 51        | 73.91%  |
| 0     | 14        | 20.29%  |
| 2     | 4         | 5.8%    |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart_bsd/net_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 51        | 49.04%  |
| Realtek Semiconductor             | 24        | 23.08%  |
| Qualcomm Atheros                  | 7         | 6.73%   |
| Broadcom                          | 7         | 6.73%   |
| AMD                               | 4         | 3.85%   |
| TP-Link                           | 3         | 2.88%   |
| Sierra Wireless                   | 1         | 0.96%   |
| Ralink Technology                 | 1         | 0.96%   |
| Ralink                            | 1         | 0.96%   |
| MediaTek                          | 1         | 0.96%   |
| HMD Global                        | 1         | 0.96%   |
| Hewlett-Packard                   | 1         | 0.96%   |
| Fibocom                           | 1         | 0.96%   |
| Ericsson Business Mobile Networks | 1         | 0.96%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart_bsd/net_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 17        | 12.88%  |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 5         | 3.79%   |
| Intel Wireless 7260                                               | 5         | 3.79%   |
| Intel Wi-Fi 6 AX200                                               | 5         | 3.79%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 5         | 3.79%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter               | 4         | 3.03%   |
| Intel Wireless 8265 / 8275                                        | 4         | 3.03%   |
| Intel Wireless 7265                                               | 4         | 3.03%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 4         | 3.03%   |
| Intel 82567LM Gigabit Network Connection                          | 4         | 3.03%   |
| AMD XGMAC 10GbE Controller                                        | 4         | 3.03%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 3         | 2.27%   |
| Intel Wireless 8260                                               | 3         | 2.27%   |
| Intel I211 Gigabit Network Connection                             | 3         | 2.27%   |
| Intel Ethernet Connection (3) I218-LM                             | 3         | 2.27%   |
| Broadcom BCM4331 802.11a/b/g/n                                    | 3         | 2.27%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]        | 2         | 1.52%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 2         | 1.52%   |
| Intel Wireless-AC 9260                                            | 2         | 1.52%   |
| Intel WiFi Link 5100                                              | 2         | 1.52%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection           | 2         | 1.52%   |
| Intel I210 Gigabit Network Connection                             | 2         | 1.52%   |
| Intel Ethernet Connection I219-LM                                 | 2         | 1.52%   |
| Intel Ethernet Connection I218-LM                                 | 2         | 1.52%   |
| Intel Ethernet Connection (4) I219-LM                             | 2         | 1.52%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 2         | 1.52%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 2         | 1.52%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 2         | 1.52%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 2         | 1.52%   |
| TP-Link Wireless USB Adapter                                      | 1         | 0.76%   |
| Sierra Wireless EM7455                                            | 1         | 0.76%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 1         | 0.76%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                           | 1         | 0.76%   |
| Ralink RT5370 Wireless Adapter                                    | 1         | 0.76%   |
| Ralink RT3592 Wireless 802.11abgn 2T/2R PCIe                      | 1         | 0.76%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                            | 1         | 0.76%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 1         | 0.76%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter     | 1         | 0.76%   |
| Intel Wireless 3160                                               | 1         | 0.76%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 1         | 0.76%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart_bsd/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 42        | 61.76%  |
| Qualcomm Atheros      | 7         | 10.29%  |
| Realtek Semiconductor | 6         | 8.82%   |
| Broadcom              | 6         | 8.82%   |
| TP-Link               | 3         | 4.41%   |
| Sierra Wireless       | 1         | 1.47%   |
| Ralink Technology     | 1         | 1.47%   |
| Ralink                | 1         | 1.47%   |
| MediaTek              | 1         | 1.47%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart_bsd/net_wireless_model.svg)


| Model                                                          | Notebooks | Percent |
|----------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 5         | 7.35%   |
| Intel Wireless 7260                                            | 5         | 7.35%   |
| Intel Wi-Fi 6 AX200                                            | 5         | 7.35%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter            | 4         | 5.88%   |
| Intel Wireless 8265 / 8275                                     | 4         | 5.88%   |
| Intel Wireless 7265                                            | 4         | 5.88%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 4         | 5.88%   |
| Intel Wireless 8260                                            | 3         | 4.41%   |
| Broadcom BCM4331 802.11a/b/g/n                                 | 3         | 4.41%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]     | 2         | 2.94%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 2         | 2.94%   |
| Intel Wireless-AC 9260                                         | 2         | 2.94%   |
| Intel WiFi Link 5100                                           | 2         | 2.94%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection        | 2         | 2.94%   |
| Intel Comet Lake PCH-LP CNVi WiFi                              | 2         | 2.94%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                       | 2         | 2.94%   |
| Intel Cannon Lake PCH CNVi WiFi                                | 2         | 2.94%   |
| TP-Link Wireless USB Adapter                                   | 1         | 1.47%   |
| Sierra Wireless EM7455                                         | 1         | 1.47%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 1         | 1.47%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                        | 1         | 1.47%   |
| Ralink RT5370 Wireless Adapter                                 | 1         | 1.47%   |
| Ralink RT3592 Wireless 802.11abgn 2T/2R PCIe                   | 1         | 1.47%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter  | 1         | 1.47%   |
| Intel Wireless 3160                                            | 1         | 1.47%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                         | 1         | 1.47%   |
| Intel Wi-Fi 6 AX201                                            | 1         | 1.47%   |
| Intel Centrino Ultimate-N 6300                                 | 1         | 1.47%   |
| Intel Centrino Advanced-N 6235                                 | 1         | 1.47%   |
| Broadcom BCM4321 802.11a/b/g/n                                 | 1         | 1.47%   |
| Broadcom BCM43142 802.11b/g/n                                  | 1         | 1.47%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter            | 1         | 1.47%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart_bsd/net_ethernet_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 30        | 49.18%  |
| Realtek Semiconductor | 20        | 32.79%  |
| Broadcom              | 4         | 6.56%   |
| AMD                   | 4         | 6.56%   |
| Qualcomm Atheros      | 2         | 3.28%   |
| HMD Global            | 1         | 1.64%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart_bsd/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 17        | 27.87%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 5         | 8.2%    |
| Intel 82567LM Gigabit Network Connection                          | 4         | 6.56%   |
| AMD XGMAC 10GbE Controller                                        | 4         | 6.56%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 3         | 4.92%   |
| Intel I211 Gigabit Network Connection                             | 3         | 4.92%   |
| Intel Ethernet Connection (3) I218-LM                             | 3         | 4.92%   |
| Intel I210 Gigabit Network Connection                             | 2         | 3.28%   |
| Intel Ethernet Connection I219-LM                                 | 2         | 3.28%   |
| Intel Ethernet Connection I218-LM                                 | 2         | 3.28%   |
| Intel Ethernet Connection (4) I219-LM                             | 2         | 3.28%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 2         | 3.28%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                            | 1         | 1.64%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 1         | 1.64%   |
| Intel Ethernet Connection I219-V                                  | 1         | 1.64%   |
| Intel Ethernet Connection I218-V                                  | 1         | 1.64%   |
| Intel Ethernet Connection (6) I219-V                              | 1         | 1.64%   |
| Intel Ethernet Connection (6) I219-LM                             | 1         | 1.64%   |
| Intel Ethernet Connection (16) I219-V                             | 1         | 1.64%   |
| Intel 82574L Gigabit Network Connection                           | 1         | 1.64%   |
| Intel 82566MM Gigabit Network Connection                          | 1         | 1.64%   |
| HMD Global Nokia 5.3 RNDIS Control RNDIS Ethernet Data            | 1         | 1.64%   |
| Broadcom NetXtreme BCM57786 Gigabit Ethernet PCIe                 | 1         | 1.64%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                  | 1         | 1.64%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart_bsd/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 58        | 49.57%  |
| Ethernet | 56        | 47.86%  |
| Modem    | 2         | 1.71%   |
| Unknown  | 1         | 0.85%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart_bsd/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| Ethernet | 43        | 50.59%  |
| WiFi     | 42        | 49.41%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart_bsd/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 48        | 71.64%  |
| 1     | 14        | 20.9%   |
| 5     | 3         | 4.48%   |
| 6     | 2         | 2.99%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart_bsd/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 57        | 81.43%  |
| Yes  | 13        | 18.57%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart_bsd/bt_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 28        | 62.22%  |
| Broadcom              | 4         | 8.89%   |
| Apple                 | 4         | 8.89%   |
| IMC Networks          | 3         | 6.67%   |
| Foxconn / Hon Hai     | 2         | 4.44%   |
| Realtek Semiconductor | 1         | 2.22%   |
| Lite-On Technology    | 1         | 2.22%   |
| Hewlett-Packard       | 1         | 2.22%   |
| Dell                  | 1         | 2.22%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart_bsd/bt_model.svg)


| Model                                                  | Notebooks | Percent |
|--------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                     | 12        | 26.67%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)         | 5         | 11.11%  |
| Intel AX200 Bluetooth                                  | 5         | 11.11%  |
| Intel Wireless-AC 9260 Bluetooth Adapter               | 2         | 4.44%   |
| Intel AX201 Bluetooth                                  | 2         | 4.44%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]             | 2         | 4.44%   |
| Apple Bluetooth Host Controller                        | 2         | 4.44%   |
| Realtek Bluetooth Adapter                              | 1         | 2.22%   |
| Lite-On Atheros AR3012 Bluetooth                       | 1         | 2.22%   |
| Intel Centrino Bluetooth Wireless Transceiver          | 1         | 2.22%   |
| Intel AX210 Bluetooth                                  | 1         | 2.22%   |
| IMC Networks Qualcomm Atheros Bluetooth 4.0 + HS       | 1         | 2.22%   |
| IMC Networks Qualcomm Atheros Bluetooth 4.0            | 1         | 2.22%   |
| IMC Networks Asus Integrated Bluetooth module [AR3011] | 1         | 2.22%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]          | 1         | 2.22%   |
| Foxconn / Hon Hai MediaTek Bluetooth Adapter           | 1         | 2.22%   |
| Foxconn / Hon Hai BCM43142A0 broadcom bluetooth        | 1         | 2.22%   |
| Dell Dell Wireless 380 Bluetooth 4.0 Module            | 1         | 2.22%   |
| Broadcom BCM2070 Bluetooth 2.1 + EDR                   | 1         | 2.22%   |
| Broadcom BCM2045B (BDC-2.1)                            | 1         | 2.22%   |
| Apple Broadcom Built-in Bluetooth                      | 1         | 2.22%   |
| Apple Broadcom Bluetooth 2.1 module                    | 1         | 2.22%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart_bsd/snd_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 50        | 72.46%  |
| AMD    | 17        | 24.64%  |
| Nvidia | 2         | 2.9%    |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart_bsd/snd_model.svg)


| Model                                                                             | Notebooks | Percent |
|-----------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                                   | 9         | 9.68%   |
| AMD Family 17h/19h HD Audio Controller                                            | 8         | 8.6%    |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller               | 7         | 7.53%   |
| Intel Haswell-ULT HD Audio Controller                                             | 6         | 6.45%   |
| Intel 8 Series HD Audio Controller                                                | 6         | 6.45%   |
| Intel Wildcat Point-LP High Definition Audio Controller                           | 5         | 5.38%   |
| Intel Broadwell-U Audio Controller                                                | 5         | 5.38%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                    | 4         | 4.3%    |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller        | 4         | 4.3%    |
| AMD Renoir Radeon High Definition Audio Controller                                | 4         | 4.3%    |
| AMD FCH Azalia Controller                                                         | 4         | 4.3%    |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                       | 2         | 2.15%   |
| Intel Comet Lake PCH-LP cAVS                                                      | 2         | 2.15%   |
| Intel Cannon Point-LP High Definition Audio Controller                            | 2         | 2.15%   |
| Intel Cannon Lake PCH cAVS                                                        | 2         | 2.15%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                           | 2         | 2.15%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                    | 2         | 2.15%   |
| AMD SBx00 Azalia (Intel HDA)                                                      | 2         | 2.15%   |
| AMD Kabini HDMI/DP Audio                                                          | 2         | 2.15%   |
| Nvidia GK107 HDMI Audio Controller                                                | 1         | 1.08%   |
| Nvidia GF108 High Definition Audio Controller                                     | 1         | 1.08%   |
| Intel DG2 Audio Controller                                                        | 1         | 1.08%   |
| Intel CM238 HD Audio Controller                                                   | 1         | 1.08%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller        | 1         | 1.08%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                  | 1         | 1.08%   |
| AMD Wrestler HDMI Audio                                                           | 1         | 1.08%   |
| AMD Trinity HDMI Audio Controller                                                 | 1         | 1.08%   |
| AMD RS880 HDMI Audio [Radeon HD 4200 Series]                                      | 1         | 1.08%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                               | 1         | 1.08%   |
| AMD High Definition Audio Controller                                              | 1         | 1.08%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                               | 1         | 1.08%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                  | 1         | 1.08%   |
| AMD Caicos HDMI Audio [Radeon HD 6450 / 7450/8450/8490 OEM / R5 230/235/235X OEM] | 1         | 1.08%   |
| AMD BeaverCreek HDMI Audio [Radeon HD 6500D and 6400G-6600G series]               | 1         | 1.08%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart_bsd/memory_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Samsung Electronics   | 16        | 24.24%  |
| Micron Technology     | 12        | 18.18%  |
| SK hynix              | 10        | 15.15%  |
| Unknown               | 4         | 6.06%   |
| Transcend             | 4         | 6.06%   |
| Crucial               | 4         | 6.06%   |
| Kingston              | 3         | 4.55%   |
| Elpida                | 3         | 4.55%   |
| Ramaxel Technology    | 2         | 3.03%   |
| Apacer                | 2         | 3.03%   |
| Team                  | 1         | 1.52%   |
| Nanya Technology      | 1         | 1.52%   |
| Kingmax Semiconductor | 1         | 1.52%   |
| G.Skill               | 1         | 1.52%   |
| Corsair               | 1         | 1.52%   |
| A-DATA Technology     | 1         | 1.52%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart_bsd/memory_model.svg)


| Model                                                        | Notebooks | Percent |
|--------------------------------------------------------------|-----------|---------|
| Transcend RAM TS1GLH64V6BL 8GB SODIMM DDR4 2667MT/s          | 3         | 4.55%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s        | 2         | 3.03%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s        | 2         | 3.03%   |
| Elpida RAM EBJ41UF8BCS0-DJ-F 4GB SODIMM DDR3 1334MT/s        | 2         | 3.03%   |
| Unknown RAM Module 8GB SODIMM LPDDR3 1867MT/s                | 1         | 1.52%   |
| Unknown RAM Module 4GB SODIMM DDR3                           | 1         | 1.52%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                   | 1         | 1.52%   |
| Unknown RAM Module 1GB SODIMM DDR2 667MT/s                   | 1         | 1.52%   |
| Transcend RAM TS512MLH64V6HL 4GB SODIMM DDR4 2667MT/s        | 1         | 1.52%   |
| Team RAM TEAMGROUP-SD4-2400 8GB SODIMM DDR4 2400MT/s         | 1         | 1.52%   |
| SK hynix RAM Module 8GB SODIMM DDR4 2133MT/s                 | 1         | 1.52%   |
| SK hynix RAM Module 4GB SODIMM DDR3 1600MT/s                 | 1         | 1.52%   |
| SK hynix RAM Module 4096MB SODIMM DDR3 1333MT/s              | 1         | 1.52%   |
| SK hynix RAM HMT451S6MFR8A-PB 4GB SODIMM DDR3 800MT/s        | 1         | 1.52%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s       | 1         | 1.52%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s       | 1         | 1.52%   |
| SK hynix RAM HMT41GS6AFR8A-PB 8GB SODIMM DDR3 1600MT/s       | 1         | 1.52%   |
| SK hynix RAM HMT351S6EFR8C-PB 4GB SODIMM DDR3 1600MT/s       | 1         | 1.52%   |
| SK hynix RAM HMT351S6CFR8A-PB 4GB SODIMM DDR3 1333MT/s       | 1         | 1.52%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB Row Of Chips DDR4 3200MT/s | 1         | 1.52%   |
| Samsung RAM Module 8GB SODIMM DDR4 2133MT/s                  | 1         | 1.52%   |
| Samsung RAM Module 8GB Row Of Chips LPDDR3 2133MT/s          | 1         | 1.52%   |
| Samsung RAM M471B5673FH0-CH9 2GB SODIMM DDR3 1334MT/s        | 1         | 1.52%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s        | 1         | 1.52%   |
| Samsung RAM M471B5174BM0-YK0 4GB SODIMM DDR3 1600MT/s        | 1         | 1.52%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1867MT/s        | 1         | 1.52%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s        | 1         | 1.52%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 2667MT/s        | 1         | 1.52%   |
| Samsung RAM M471A4G43AB1-CWE 32GB SODIMM DDR4 3200MT/s       | 1         | 1.52%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s        | 1         | 1.52%   |
| Samsung RAM M425R1GB4BB0-CQKOL 8GB SODIMM DDR5 4800MT/s      | 1         | 1.52%   |
| Samsung RAM K4E6E304EB-EGCF 4GB 1867MT/s                     | 1         | 1.52%   |
| Ramaxel RAM RMT3170MN68F9F1600 4GB SODIMM DDR3 1600MT/s      | 1         | 1.52%   |
| Ramaxel RAM RMT3020EF48E8W1333 2GB SODIMM DDR3 1334MT/s      | 1         | 1.52%   |
| Nanya RAM NT2GC64B8HA1NS-BE 2GB SODIMM DDR3 1067MT/s         | 1         | 1.52%   |
| Micron RAM MT41K512M16TNA-125 4GB Chip DDR3 1600MT/s         | 1         | 1.52%   |
| Micron RAM 8KTS51264HDZ-1G6E1 4GB Chip DDR3 1600MT/s         | 1         | 1.52%   |
| Micron RAM 8KTF51264HZ-1G6N1 4GB SODIMM DDR3 1600MT/s        | 1         | 1.52%   |
| Micron RAM 8KTF51264HDZ-1G6E1 4GB SODIMM DDR3 1600MT/s       | 1         | 1.52%   |
| Micron RAM 53E2G32D4NQ-046 4GB Row Of Chips LPDDR4 4267MT/s  | 1         | 1.52%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart_bsd/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR3    | 29        | 50%     |
| DDR4    | 21        | 36.21%  |
| DDR2    | 3         | 5.17%   |
| LPDDR3  | 2         | 3.45%   |
| LPDDR4  | 1         | 1.72%   |
| DDR5    | 1         | 1.72%   |
| Unknown | 1         | 1.72%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart_bsd/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 52        | 88.14%  |
| Row Of Chips | 3         | 5.08%   |
| Chip         | 3         | 5.08%   |
| Unknown      | 1         | 1.69%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart_bsd/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 4096  | 25        | 39.68%  |
| 8192  | 23        | 36.51%  |
| 2048  | 7         | 11.11%  |
| 16384 | 6         | 9.52%   |
| 32768 | 1         | 1.59%   |
| 1024  | 1         | 1.59%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart_bsd/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 1600    | 16        | 26.67%  |
| 2667    | 10        | 16.67%  |
| 3200    | 4         | 6.67%   |
| 2400    | 4         | 6.67%   |
| 1867    | 4         | 6.67%   |
| 1334    | 4         | 6.67%   |
| 1333    | 4         | 6.67%   |
| 2133    | 3         | 5%      |
| 1866    | 2         | 3.33%   |
| 800     | 2         | 3.33%   |
| 667     | 2         | 3.33%   |
| 4800    | 1         | 1.67%   |
| 4267    | 1         | 1.67%   |
| 1067    | 1         | 1.67%   |
| 1066    | 1         | 1.67%   |
| Unknown | 1         | 1.67%   |

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
| Chicony Electronics                    | 17        | 36.17%  |
| Realtek Semiconductor                  | 6         | 12.77%  |
| IMC Networks                           | 6         | 12.77%  |
| Lite-On Technology                     | 4         | 8.51%   |
| Microdia                               | 3         | 6.38%   |
| Bison Electronics                      | 3         | 6.38%   |
| Apple                                  | 3         | 6.38%   |
| Alcor Micro                            | 2         | 4.26%   |
| Sunplus Innovation Technology          | 1         | 2.13%   |
| Ricoh                                  | 1         | 2.13%   |
| Cheng Uei Precision Industry (Foxlink) | 1         | 2.13%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart_bsd/camera_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Chicony Integrated Camera                     | 4         | 8.51%   |
| IMC Networks Integrated Camera                | 3         | 6.38%   |
| Realtek USB Camera                            | 2         | 4.26%   |
| Realtek Integrated_Webcam_HD                  | 2         | 4.26%   |
| Microdia Integrated_Webcam_HD                 | 2         | 4.26%   |
| Lite-On Integrated Camera                     | 2         | 4.26%   |
| Chicony Realtek DMFT RGB                      | 2         | 4.26%   |
| Chicony Chicony USB2.0 Camera                 | 2         | 4.26%   |
| Bison Integrated Camera                       | 2         | 4.26%   |
| Apple FaceTime HD Camera                      | 2         | 4.26%   |
| Sunplus Laptop Integrated Webcam HD           | 1         | 2.13%   |
| Ricoh USB2.0 Camera                           | 1         | 2.13%   |
| Realtek Lenovo EasyCamera                     | 1         | 2.13%   |
| Realtek Integrated Webcam HD                  | 1         | 2.13%   |
| Microdia Dell Integrated HD Webcam            | 1         | 2.13%   |
| Lite-On TOSHIBA Web Camera - HD               | 1         | 2.13%   |
| Lite-On HP Universal Camera                   | 1         | 2.13%   |
| IMC Networks USB2.0 HD UVC WebCam             | 1         | 2.13%   |
| IMC Networks Realtek PC Camera                | 1         | 2.13%   |
| IMC Networks EasyCamera                       | 1         | 2.13%   |
| Chicony VGA Webcam                            | 1         | 2.13%   |
| Chicony thinkpad t430s camera                 | 1         | 2.13%   |
| Chicony Lenovo Integrated Camera (0.3MP)      | 1         | 2.13%   |
| Chicony Integrated IR Camera                  | 1         | 2.13%   |
| Chicony Integrated Camera (1280x720@30)       | 1         | 2.13%   |
| Chicony HP Wide Vision HD Camera              | 1         | 2.13%   |
| Chicony HP Webcam [2 MP]                      | 1         | 2.13%   |
| Chicony HD WebCam (Acer)                      | 1         | 2.13%   |
| Chicony HD Webcam                             | 1         | 2.13%   |
| Cheng Uei Precision Industry (Foxlink) Webcam | 1         | 2.13%   |
| Bison Lenovo EasyCamera                       | 1         | 2.13%   |
| Apple FaceTime HD Camera (Built-in)           | 1         | 2.13%   |
| Alcor Micro ASUS USB2.0 WebCam                | 1         | 2.13%   |
| Alcor Micro Asus Integrated Webcam            | 1         | 2.13%   |

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
| 1     | 31        | 45.59%  |
| 0     | 13        | 19.12%  |
| 2     | 12        | 17.65%  |
| 3     | 8         | 11.76%  |
| 4     | 4         | 5.88%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart_bsd/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Communication controller | 44        | 51.16%  |
| Card reader              | 12        | 13.95%  |
| Net/wireless             | 10        | 11.63%  |
| Bluetooth                | 8         | 9.3%    |
| Fingerprint reader       | 6         | 6.98%   |
| Firewire controller      | 3         | 3.49%   |
| Sound                    | 1         | 1.16%   |
| Net/ethernet             | 1         | 1.16%   |
| Graphics card            | 1         | 1.16%   |

