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

Total: 114

| Vendor        | Model                       | Probe                                                     | Date         |
|---------------|-----------------------------|-----------------------------------------------------------|--------------|
| Lenovo        | ThinkPad W520 4284GZ1       | [0990e7253e](https://bsd-hardware.info/?probe=0990e7253e) | May 07, 2024 |
| Micro Comp... | Venus series                | [11184b32bb](https://bsd-hardware.info/?probe=11184b32bb) | May 05, 2024 |
| HP            | OMEN by Laptop              | [e2bce481c8](https://bsd-hardware.info/?probe=e2bce481c8) | Apr 21, 2024 |
| Deciso        | NetBoard-A10                | [659c975065](https://bsd-hardware.info/?probe=659c975065) | Apr 02, 2024 |
| Deciso        | NetBoard-A20                | [f5341b37b3](https://bsd-hardware.info/?probe=f5341b37b3) | Mar 21, 2024 |
| Deciso        | OPNsense Appliance          | [8283ee7c1b](https://bsd-hardware.info/?probe=8283ee7c1b) | Mar 21, 2024 |
| Deciso        | NetBoard-A10                | [0b83b42575](https://bsd-hardware.info/?probe=0b83b42575) | Feb 22, 2024 |
| Micro Comp... | Venus series                | [20e602834b](https://bsd-hardware.info/?probe=20e602834b) | Feb 08, 2024 |
| Micro Comp... | Venus series                | [3a2455558f](https://bsd-hardware.info/?probe=3a2455558f) | Feb 08, 2024 |
| Deciso        | NetBoard-A10                | [6cfe3230e8](https://bsd-hardware.info/?probe=6cfe3230e8) | Feb 07, 2024 |
| Panasonic     | CF-52PGNBX2M                | [401aeae642](https://bsd-hardware.info/?probe=401aeae642) | Feb 03, 2024 |
| Micro Comp... | Venus series                | [2fbda08743](https://bsd-hardware.info/?probe=2fbda08743) | Feb 03, 2024 |
| Micro Comp... | Venus series                | [e7693b7781](https://bsd-hardware.info/?probe=e7693b7781) | Feb 03, 2024 |
| HP            | ProBook 650 G1              | [50888a6e05](https://bsd-hardware.info/?probe=50888a6e05) | Jan 22, 2024 |
| Lenovo        | ThinkPad W520 4284GZ1       | [32bc5e823d](https://bsd-hardware.info/?probe=32bc5e823d) | Jan 17, 2024 |
| Micro Comp... | Venus series                | [fc242d0e50](https://bsd-hardware.info/?probe=fc242d0e50) | Jan 13, 2024 |
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


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| helloSystem 0.7.0   | 8         | 8.89%   |
| helloSystem 0.5.0   | 6         | 6.67%   |
| helloSystem 0.8.1   | 5         | 5.56%   |
| FreeBSD 13.0-STABLE | 5         | 5.56%   |
| helloSystem 0.8.0   | 4         | 4.44%   |
| helloSystem 0.6.0   | 3         | 3.33%   |
| helloSystem 0.3.0   | 3         | 3.33%   |
| OPNsense 23.10.2    | 2         | 2.22%   |
| OPNsense 22.10      | 2         | 2.22%   |
| OpenBSD 7.1         | 2         | 2.22%   |
| OpenBSD 6.9         | 2         | 2.22%   |
| OpenBSD 6.8         | 2         | 2.22%   |
| helloSystem 0.8.2   | 2         | 2.22%   |
| helloSystem 0.4.0   | 2         | 2.22%   |
| GhostBSD 22.06.18   | 2         | 2.22%   |
| FreeBSD 14.0-p4     | 2         | 2.22%   |
| FreeBSD 14.0        | 2         | 2.22%   |
| FreeBSD 13.1-p4     | 2         | 2.22%   |
| FreeBSD 13.1        | 2         | 2.22%   |
| FreeBSD 13.0-p5     | 2         | 2.22%   |
| OPNsense 24.1.6     | 1         | 1.11%   |
| OPNsense 24.1.4     | 1         | 1.11%   |
| OPNsense 24.1.2     | 1         | 1.11%   |
| OPNsense 24.1.1     | 1         | 1.11%   |
| OPNsense 24.1       | 1         | 1.11%   |
| OPNsense 23.7.10    | 1         | 1.11%   |
| OPNsense 23.4.1     | 1         | 1.11%   |
| OPNsense 23.4       | 1         | 1.11%   |
| OPNsense 23.10      | 1         | 1.11%   |
| OPNsense 22.7.4     | 1         | 1.11%   |
| OPNsense 22.7.2     | 1         | 1.11%   |
| OPNsense 22.7.10    | 1         | 1.11%   |
| OPNsense 22.10.1    | 1         | 1.11%   |
| OPNsense 22.1.7     | 1         | 1.11%   |
| OPNsense 22.1.6     | 1         | 1.11%   |
| OPNsense 22.1       | 1         | 1.11%   |
| OPNsense 21.7.7     | 1         | 1.11%   |
| OPNsense 21.1.9     | 1         | 1.11%   |
| OpenBSD 7.2         | 1         | 1.11%   |
| OpenBSD 7.0         | 1         | 1.11%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart_bsd/os_family.svg)


| Name        | Notebooks | Percent |
|-------------|-----------|---------|
| helloSystem | 32        | 43.84%  |
| FreeBSD     | 20        | 27.4%   |
| OPNsense    | 11        | 15.07%  |
| OpenBSD     | 8         | 10.96%  |
| GhostBSD    | 2         | 2.74%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart_bsd/os_arch.svg)


| Name  | Notebooks | Percent |
|-------|-----------|---------|
| amd64 | 72        | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart_bsd/os_de.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| helloDesktop | 34        | 44.74%  |
| Console      | 14        | 18.42%  |
| MATE         | 5         | 6.58%   |
| fvwm         | 5         | 6.58%   |
| XFCE         | 3         | 3.95%   |
| TWM          | 3         | 3.95%   |
| KDE5         | 3         | 3.95%   |
| GNOME        | 3         | 3.95%   |
| LXQt         | 2         | 2.63%   |
| i3           | 2         | 2.63%   |
| GNUstep      | 1         | 1.32%   |
| AwesomeWM    | 1         | 1.32%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart_bsd/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 58        | 80.56%  |
| Console | 13        | 18.06%  |
| Wayland | 1         | 1.39%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart_bsd/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| SLiM    | 35        | 47.3%   |
| Console | 26        | 35.14%  |
| XDM     | 4         | 5.41%   |
| LightDM | 4         | 5.41%   |
| SDDM    | 3         | 4.05%   |
| GDM     | 2         | 2.7%    |

OS Lang
-------

Language

![OS Lang](./images/pie_chart_bsd/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| en_US   | 29        | 38.67%  |
| C       | 18        | 24%     |
| Unknown | 17        | 22.67%  |
| nl_NL   | 6         | 8%      |
| en      | 3         | 4%      |
| nl      | 1         | 1.33%   |
| fr_FR   | 1         | 1.33%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart_bsd/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 61        | 82.43%  |
| BIOS | 13        | 17.57%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart_bsd/os_filesystem.svg)


| Type   | Notebooks | Percent |
|--------|-----------|---------|
| Zfs    | 45        | 61.64%  |
| Ufs    | 10        | 13.7%   |
| Cd9660 | 10        | 13.7%   |
| Ffs    | 8         | 10.96%  |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart_bsd/os_part_scheme.svg)


| Type | Notebooks | Percent |
|------|-----------|---------|
| GPT  | 67        | 93.06%  |
| MBR  | 5         | 6.94%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart_bsd/node_vendor.svg)


| Name                             | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Lenovo                           | 22        | 30.56%  |
| Dell                             | 9         | 12.5%   |
| Hewlett-Packard                  | 7         | 9.72%   |
| Deciso                           | 5         | 6.94%   |
| ASUSTek Computer                 | 4         | 5.56%   |
| Apple                            | 4         | 5.56%   |
| Notebook                         | 3         | 4.17%   |
| SLIMBOOK                         | 2         | 2.78%   |
| Micro Computer (HK) Tech Limited | 2         | 2.78%   |
| Acer                             | 2         | 2.78%   |
| Unknown                          | 2         | 2.78%   |
| WYSE                             | 1         | 1.39%   |
| TUXEDO                           | 1         | 1.39%   |
| TOXIC by BTO                     | 1         | 1.39%   |
| Toshiba                          | 1         | 1.39%   |
| Star Labs                        | 1         | 1.39%   |
| Sony                             | 1         | 1.39%   |
| Panasonic                        | 1         | 1.39%   |
| Medion                           | 1         | 1.39%   |
| Intel                            | 1         | 1.39%   |
| Google                           | 1         | 1.39%   |

Model
-----

Motherboard model

![Model](./images/pie_chart_bsd/node_model.svg)


| Name                                     | Notebooks | Percent |
|------------------------------------------|-----------|---------|
| Unknown                                  | 3         | 4.17%   |
| Micro (HK) Tech Limited Venus series     | 2         | 2.78%   |
| HP EliteBook 840 G3                      | 2         | 2.78%   |
| Dell Latitude E4300                      | 2         | 2.78%   |
| Deciso OPNsense Appliance                | 2         | 2.78%   |
| Deciso NetBoard-A10                      | 2         | 2.78%   |
| WYSE Z CLASS                             | 1         | 1.39%   |
| TUXEDO Pulse 15 Gen1                     | 1         | 1.39%   |
| TOXIC by BTO 15CL872 1050TI              | 1         | 1.39%   |
| Toshiba Satellite C50-B                  | 1         | 1.39%   |
| Star Labs LabTop                         | 1         | 1.39%   |
| Sony SVZ1311C5E                          | 1         | 1.39%   |
| SLIMBOOK PROX-AMD5                       | 1         | 1.39%   |
| Panasonic CF-52PGNBX2M                   | 1         | 1.39%   |
| Notebook NS5x_NS7xPU                     | 1         | 1.39%   |
| Notebook NL5xRU                          | 1         | 1.39%   |
| Notebook N2x0WU                          | 1         | 1.39%   |
| Medion Major X10                         | 1         | 1.39%   |
| Lenovo Yoga 500-14IBD 80N4               | 1         | 1.39%   |
| Lenovo ThinkPad X61s 76693KG             | 1         | 1.39%   |
| Lenovo ThinkPad X280 20KESA000B          | 1         | 1.39%   |
| Lenovo ThinkPad X250 20CLS5BU00          | 1         | 1.39%   |
| Lenovo ThinkPad X250 20CLS59400          | 1         | 1.39%   |
| Lenovo ThinkPad X250 20CLS4WV08          | 1         | 1.39%   |
| Lenovo ThinkPad X230 2325IG2             | 1         | 1.39%   |
| Lenovo ThinkPad X230 23255Y4             | 1         | 1.39%   |
| Lenovo ThinkPad X200s 7470W1V            | 1         | 1.39%   |
| Lenovo ThinkPad X1 Carbon 7th 20QDCTO1WW | 1         | 1.39%   |
| Lenovo ThinkPad X1 Carbon 5th 20HRCTO1WW | 1         | 1.39%   |
| Lenovo ThinkPad W520 4284GZ1             | 1         | 1.39%   |
| Lenovo ThinkPad T490 20N2CTO1WW          | 1         | 1.39%   |
| Lenovo ThinkPad T440s 20ARS1B704         | 1         | 1.39%   |
| Lenovo ThinkPad T440 20B7S2LT00          | 1         | 1.39%   |
| Lenovo ThinkPad T430 2347G7G             | 1         | 1.39%   |
| Lenovo ThinkPad S1 Yoga 20CD0038MB       | 1         | 1.39%   |
| Lenovo ThinkPad A285 20MW000JMH          | 1         | 1.39%   |
| Lenovo IdeaPad Gaming 3 15IHU6 82K1      | 1         | 1.39%   |
| Lenovo IdeaPad 5 15ALC05 82LN            | 1         | 1.39%   |
| Lenovo IdeaPad 130-15AST 81H5            | 1         | 1.39%   |
| Lenovo G505s 20255                       | 1         | 1.39%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart_bsd/node_model_family.svg)


| Name                          | Notebooks | Percent |
|-------------------------------|-----------|---------|
| Lenovo ThinkPad               | 17        | 23.61%  |
| Dell Latitude                 | 7         | 9.72%   |
| HP EliteBook                  | 4         | 5.56%   |
| Lenovo IdeaPad                | 3         | 4.17%   |
| Unknown                       | 3         | 4.17%   |
| Micro (HK) Tech Limited Venus | 2         | 2.78%   |
| Deciso OPNsense               | 2         | 2.78%   |
| Deciso NetBoard-A10           | 2         | 2.78%   |
| Acer Aspire                   | 2         | 2.78%   |
| WYSE Z                        | 1         | 1.39%   |
| TUXEDO Pulse                  | 1         | 1.39%   |
| TOXIC by BTO 15CL872          | 1         | 1.39%   |
| Toshiba Satellite             | 1         | 1.39%   |
| Star Labs LabTop              | 1         | 1.39%   |
| Sony SVZ1311C5E               | 1         | 1.39%   |
| SLIMBOOK PROX-AMD5            | 1         | 1.39%   |
| Panasonic CF-52PGNBX2M        | 1         | 1.39%   |
| Notebook NS5x                 | 1         | 1.39%   |
| Notebook NL5xRU               | 1         | 1.39%   |
| Notebook N2x0WU               | 1         | 1.39%   |
| Medion Major                  | 1         | 1.39%   |
| Lenovo Yoga                   | 1         | 1.39%   |
| Lenovo G505s                  | 1         | 1.39%   |
| Intel Milstead                | 1         | 1.39%   |
| HP ProBook                    | 1         | 1.39%   |
| HP OMEN                       | 1         | 1.39%   |
| HP 625                        | 1         | 1.39%   |
| Google Cave                   | 1         | 1.39%   |
| Dell XPS                      | 1         | 1.39%   |
| Dell Inspiron                 | 1         | 1.39%   |
| Deciso NetBoard-A20           | 1         | 1.39%   |
| ASUS ZenBook                  | 1         | 1.39%   |
| ASUS X751LB                   | 1         | 1.39%   |
| ASUS X556UA                   | 1         | 1.39%   |
| ASUS K53TA                    | 1         | 1.39%   |
| Apple MacBookPro9             | 1         | 1.39%   |
| Apple MacBookPro8             | 1         | 1.39%   |
| Apple MacBookPro10            | 1         | 1.39%   |
| Apple MacBookAir1             | 1         | 1.39%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart_bsd/node_year.svg)


| Year    | Notebooks | Percent |
|---------|-----------|---------|
| 2022    | 9         | 12.5%   |
| 2018    | 7         | 9.72%   |
| 2021    | 6         | 8.33%   |
| 2019    | 6         | 8.33%   |
| 2015    | 6         | 8.33%   |
| 2012    | 6         | 8.33%   |
| 2020    | 5         | 6.94%   |
| 2014    | 5         | 6.94%   |
| 2016    | 4         | 5.56%   |
| 2013    | 3         | 4.17%   |
| 2011    | 3         | 4.17%   |
| 2023    | 2         | 2.78%   |
| 2017    | 2         | 2.78%   |
| 2010    | 2         | 2.78%   |
| 2009    | 2         | 2.78%   |
| 2008    | 2         | 2.78%   |
| Unknown | 2         | 2.78%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart_bsd/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 72        | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart_bsd/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 71        | 98.61%  |
| Yes  | 1         | 1.39%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart_bsd/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 8.01-16.0   | 32        | 44.44%  |
| 16.01-24.0  | 19        | 26.39%  |
| 4.01-8.0    | 14        | 19.44%  |
| 32.01-64.0  | 4         | 5.56%   |
| 64.01-256.0 | 2         | 2.78%   |
| 2.01-3.0    | 1         | 1.39%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart_bsd/node_ram_used.svg)


| Used GB  | Notebooks | Percent |
|----------|-----------|---------|
| 0.01-0.5 | 39        | 52.7%   |
| 0.51-1.0 | 22        | 29.73%  |
| 1.01-2.0 | 9         | 12.16%  |
| 3.01-4.0 | 2         | 2.7%    |
| 2.01-3.0 | 2         | 2.7%    |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart_bsd/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 48        | 64.86%  |
| 2      | 18        | 24.32%  |
| 3      | 4         | 5.41%   |
| 0      | 4         | 5.41%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart_bsd/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 58        | 80.56%  |
| Yes       | 14        | 19.44%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart_bsd/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 61        | 84.72%  |
| No        | 11        | 15.28%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart_bsd/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 62        | 86.11%  |
| No        | 10        | 13.89%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart_bsd/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 46        | 63.89%  |
| No        | 26        | 36.11%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart_bsd/node_location.svg)


| Country     | Notebooks | Percent |
|-------------|-----------|---------|
| Netherlands | 72        | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart_bsd/node_city.svg)


| City                    | Notebooks | Percent |
|-------------------------|-----------|---------|
| Amsterdam               | 16        | 20.51%  |
| Utrecht                 | 5         | 6.41%   |
| The Hague               | 5         | 6.41%   |
| Zwolle                  | 3         | 3.85%   |
| Eindhoven               | 3         | 3.85%   |
| Papendrecht             | 2         | 2.56%   |
| Oosterhout              | 2         | 2.56%   |
| Oegstgeest              | 2         | 2.56%   |
| Hoogeveen               | 2         | 2.56%   |
| Groningen               | 2         | 2.56%   |
| 's-Hertogenbosch        | 2         | 2.56%   |
| Woerdense Verlaat       | 1         | 1.28%   |
| Westervoort             | 1         | 1.28%   |
| Warmond                 | 1         | 1.28%   |
| Veendam                 | 1         | 1.28%   |
| Tilburg                 | 1         | 1.28%   |
| Rozenburg               | 1         | 1.28%   |
| Roosendaal              | 1         | 1.28%   |
| Rhoon                   | 1         | 1.28%   |
| Ouderkerk aan de Amstel | 1         | 1.28%   |
| Norg                    | 1         | 1.28%   |
| Munnikens-Vinkel        | 1         | 1.28%   |
| Lent                    | 1         | 1.28%   |
| Leiden                  | 1         | 1.28%   |
| Leeuwarden              | 1         | 1.28%   |
| Hoek van Holland        | 1         | 1.28%   |
| Hilversum               | 1         | 1.28%   |
| Haarlem                 | 1         | 1.28%   |
| Gouda                   | 1         | 1.28%   |
| Elim                    | 1         | 1.28%   |
| Ede                     | 1         | 1.28%   |
| Dronten                 | 1         | 1.28%   |
| Dordrecht               | 1         | 1.28%   |
| Diemen                  | 1         | 1.28%   |
| Deventer                | 1         | 1.28%   |
| Den Dolder              | 1         | 1.28%   |
| De Lutte                | 1         | 1.28%   |
| Cuijk                   | 1         | 1.28%   |
| Capelle aan den IJssel  | 1         | 1.28%   |
| Berghem                 | 1         | 1.28%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart_bsd/drive_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 19        | 30     | 23.17%  |
| WDC                 | 8         | 8      | 9.76%   |
| Seagate             | 7         | 9      | 8.54%   |
| Transcend           | 6         | 15     | 7.32%   |
| Crucial             | 6         | 8      | 7.32%   |
| SanDisk             | 5         | 5      | 6.1%    |
| Toshiba             | 4         | 4      | 4.88%   |
| NVMe                | 3         | 4      | 3.66%   |
| VICKTER             | 2         | 4      | 2.44%   |
| Kingston            | 2         | 2      | 2.44%   |
| Intel               | 2         | 2      | 2.44%   |
| Hitachi             | 2         | 2      | 2.44%   |
| Gigabyte Technology | 2         | 3      | 2.44%   |
| Apple               | 2         | 3      | 2.44%   |
| Vaseky              | 1         | 1      | 1.22%   |
| Star Drive          | 1         | 1      | 1.22%   |
| SK hynix            | 1         | 1      | 1.22%   |
| Phison              | 1         | 1      | 1.22%   |
| OCZ                 | 1         | 1      | 1.22%   |
| Micron Technology   | 1         | 1      | 1.22%   |
| LITEON              | 1         | 1      | 1.22%   |
| Leven               | 1         | 1      | 1.22%   |
| HPE                 | 1         | 1      | 1.22%   |
| Hoodisk             | 1         | 2      | 1.22%   |
| HGST                | 1         | 1      | 1.22%   |
| China               | 1         | 1      | 1.22%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart_bsd/drive_model.svg)


| Model                            | Notebooks | Percent |
|----------------------------------|-----------|---------|
| WDC WD5000LPVX-22V0TT0 500GB     | 2         | 2.41%   |
| VICKTER SSD 512GB                | 2         | 2.41%   |
| Transcend TS256GMTE652T2 256GB   | 2         | 2.41%   |
| Toshiba MQ04ABF100 1TB           | 2         | 2.41%   |
| Seagate ST500LM000-SSHD-8GB      | 2         | 2.41%   |
| Seagate ST1000LM049-2GH172 1TB   | 2         | 2.41%   |
| Samsung SSD 840 EVO 250GB        | 2         | 2.41%   |
| WDC WDS500G2B0C-00PXH0 500GB     | 1         | 1.2%    |
| WDC WDS500G2B0A 500GB            | 1         | 1.2%    |
| WDC WDS100T2B0B-00YS70 1TB       | 1         | 1.2%    |
| WDC WD15EARS-00Z5B1 1.5TB        | 1         | 1.2%    |
| WDC WD10SPZX-24Z10 1TB           | 1         | 1.2%    |
| WDC WD10SPZX-00Z10T0 1TB         | 1         | 1.2%    |
| Vaseky V850-128G                 | 1         | 1.2%    |
| Transcend TS512GMTS430S 512GB    | 1         | 1.2%    |
| Transcend TS256GMTS952T2 256GB   | 1         | 1.2%    |
| Transcend TS256GMTE710T 256GB    | 1         | 1.2%    |
| Transcend TS128GMTE110S 128GB    | 1         | 1.2%    |
| Toshiba THNSN5512GPUK NVMe 512GB | 1         | 1.2%    |
| Toshiba THNSFJ256GCSU 256GB      | 1         | 1.2%    |
| Star Drive PCIe SSD 960GB        | 1         | 1.2%    |
| SK hynix SC311 SATA 256GB        | 1         | 1.2%    |
| Seagate ST9250410AS 250GB        | 1         | 1.2%    |
| Seagate ST9160412ASG 160GB       | 1         | 1.2%    |
| Seagate ST500VT000-1DK142 500GB  | 1         | 1.2%    |
| SanDisk SD8SN8U-128G-1006 128GB  | 1         | 1.2%    |
| SanDisk SD8SBAT256G1002 256GB    | 1         | 1.2%    |
| SanDisk SD7UB3Q256G1001 256GB    | 1         | 1.2%    |
| SanDisk SD7TB3Q-256G-1006 256GB  | 1         | 1.2%    |
| SanDisk SD6SB1M064G 64GB         | 1         | 1.2%    |
| Samsung SSD PM851 mSATA 512GB    | 1         | 1.2%    |
| Samsung SSD PM841 mSATA 256GB    | 1         | 1.2%    |
| Samsung SSD 980 PRO 1TB          | 1         | 1.2%    |
| Samsung SSD 970 PRO 512GB        | 1         | 1.2%    |
| Samsung SSD 970 EVO 500GB        | 1         | 1.2%    |
| Samsung SSD 870 QVO 1TB          | 1         | 1.2%    |
| Samsung SSD 860 EVO 1TB          | 1         | 1.2%    |
| Samsung SSD 850 EVO 500GB        | 1         | 1.2%    |
| Samsung SSD 850 EVO 250GB        | 1         | 1.2%    |
| Samsung SSD 840 PRO Series 256GB | 1         | 1.2%    |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart_bsd/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 7         | 9      | 38.89%  |
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
| Samsung Electronics | 13        | 22     | 28.89%  |
| SanDisk             | 5         | 5      | 11.11%  |
| Crucial             | 5         | 6      | 11.11%  |
| NVMe                | 3         | 4      | 6.67%   |
| WDC                 | 2         | 2      | 4.44%   |
| VICKTER             | 2         | 4      | 4.44%   |
| Transcend           | 2         | 8      | 4.44%   |
| Apple               | 2         | 3      | 4.44%   |
| Vaseky              | 1         | 1      | 2.22%   |
| Toshiba             | 1         | 1      | 2.22%   |
| SK hynix            | 1         | 1      | 2.22%   |
| OCZ                 | 1         | 1      | 2.22%   |
| LITEON              | 1         | 1      | 2.22%   |
| Leven               | 1         | 1      | 2.22%   |
| Intel               | 1         | 1      | 2.22%   |
| HPE                 | 1         | 1      | 2.22%   |
| Hoodisk             | 1         | 2      | 2.22%   |
| Gigabyte Technology | 1         | 1      | 2.22%   |
| China               | 1         | 1      | 2.22%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart_bsd/drive_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SSD  | 41        | 66     | 53.95%  |
| HDD  | 18        | 20     | 23.68%  |
| NVMe | 17        | 26     | 22.37%  |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart_bsd/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 56        | 86     | 76.71%  |
| NVMe | 17        | 26     | 23.29%  |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart_bsd/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 42        | 62     | 70%     |
| 0.51-1.0   | 17        | 23     | 28.33%  |
| 1.01-2.0   | 1         | 1      | 1.67%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart_bsd/drive_space_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 101-250    | 22        | 29.33%  |
| 251-500    | 17        | 22.67%  |
| 1-20       | 17        | 22.67%  |
| 501-1000   | 7         | 9.33%   |
| 51-100     | 7         | 9.33%   |
| 21-50      | 2         | 2.67%   |
| 1001-2000  | 2         | 2.67%   |
| Unknown    | 1         | 1.33%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart_bsd/drive_space_used.svg)


| Used GB  | Notebooks | Percent |
|----------|-----------|---------|
| 1-20     | 62        | 84.93%  |
| 21-50    | 3         | 4.11%   |
| 251-500  | 2         | 2.74%   |
| 101-250  | 2         | 2.74%   |
| 51-100   | 2         | 2.74%   |
| 501-1000 | 1         | 1.37%   |
| Unknown  | 1         | 1.37%   |

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
| Works    | 61        | 100    | 85.92%  |
| Malfunc  | 5         | 5      | 7.04%   |
| Detected | 4         | 6      | 5.63%   |
| Failed   | 1         | 1      | 1.41%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart_bsd/storage_vendor.svg)


| Vendor                      | Notebooks | Percent |
|-----------------------------|-----------|---------|
| Intel                       | 49        | 59.76%  |
| AMD                         | 12        | 14.63%  |
| Samsung Electronics         | 8         | 9.76%   |
| Transcend                   | 4         | 4.88%   |
| Phison Electronics          | 3         | 3.66%   |
| Kingston Technology Company | 2         | 2.44%   |
| Toshiba                     | 1         | 1.22%   |
| SanDisk                     | 1         | 1.22%   |
| Micron/Crucial Technology   | 1         | 1.22%   |
| Micron Technology           | 1         | 1.22%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart_bsd/storage_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 10        | 11.24%  |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 8         | 8.99%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 5         | 5.62%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 5         | 5.62%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 5         | 5.62%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 5         | 5.62%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 4         | 4.49%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 4         | 4.49%   |
| Transcend NVMe PCIe SSD 110S/112S/120S/MTE300S/MTE400S/MTE652T2 (DRAM-less)    | 3         | 3.37%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 3         | 3.37%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 2         | 2.25%   |
| Intel Volume Management Device NVMe RAID Controller                            | 2         | 2.25%   |
| Intel SSD DC P4101/Pro 7600p/760p/E 6100p Series                               | 2         | 2.25%   |
| Intel product 54d3                                                             | 2         | 2.25%   |
| Intel Comet Lake SATA AHCI Controller                                          | 2         | 2.25%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                  | 2         | 2.25%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                               | 2         | 2.25%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 2         | 2.25%   |
| Transcend NVMe PCIe SSD 240S/MTE710T                                           | 1         | 1.12%   |
| Toshiba XG4 NVMe SSD Controller                                                | 1         | 1.12%   |
| SanDisk Ultra 3D / WD Blue SN550 NVMe SSD                                      | 1         | 1.12%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                    | 1         | 1.12%   |
| Phison PS5013-E13 PCIe3 NVMe Controller (DRAM-less)                            | 1         | 1.12%   |
| Phison E18 PCIe4 NVMe Controller                                               | 1         | 1.12%   |
| Phison E12 NVMe Controller                                                     | 1         | 1.12%   |
| Micron/Crucial P2 [Nick P2] / P3 / P3 Plus NVMe PCIe SSD (DRAM-less)           | 1         | 1.12%   |
| Micron 2210 NVMe SSD [Cobain]                                                  | 1         | 1.12%   |
| Kingston Company NV2 NVMe SSD SM2267XT (DRAM-less)                             | 1         | 1.12%   |
| Kingston Company A2000 NVMe SSD SM2263EN                                       | 1         | 1.12%   |
| Intel Tiger Lake-LP SATA Controller                                            | 1         | 1.12%   |
| Intel SSD 660P Series                                                          | 1         | 1.12%   |
| Intel Mobile 4 Series Chipset PT IDER Controller                               | 1         | 1.12%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 1         | 1.12%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 1         | 1.12%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                         | 1         | 1.12%   |
| Intel 82801JI (ICH10 Family) SATA AHCI Controller                              | 1         | 1.12%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 2 port SATA Controller [IDE mode]           | 1         | 1.12%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 1         | 1.12%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                 | 1         | 1.12%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart_bsd/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 51        | 58.62%  |
| NVMe | 22        | 25.29%  |
| RAID | 10        | 11.49%  |
| IDE  | 4         | 4.6%    |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart_bsd/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 55        | 76.39%  |
| AMD    | 17        | 23.61%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart_bsd/cpu_model.svg)


| Model                                   | Notebooks | Percent |
|-----------------------------------------|-----------|---------|
| AMD Ryzen Embedded V1500B               | 3         | 4.17%   |
| Intel N100                              | 2         | 2.78%   |
| Intel Core i7-8750H CPU @ 2.20GHz       | 2         | 2.78%   |
| Intel Core i7-7600U CPU @ 2.80GHz       | 2         | 2.78%   |
| Intel Core i7-4600U CPU @ 2.10GHz       | 2         | 2.78%   |
| Intel Core i7-4500U CPU @ 1.80GHz       | 2         | 2.78%   |
| Intel Core i7-3520M CPU @ 2.90GHz       | 2         | 2.78%   |
| Intel Core i7-2630QM CPU @ 2.00GHz      | 2         | 2.78%   |
| Intel Core i5-6300U CPU @ 2.40GHz       | 2         | 2.78%   |
| Intel Core i5-5300U CPU @ 2.30GHz       | 2         | 2.78%   |
| Intel Core i5-3210M CPU @ 2.50GHz       | 2         | 2.78%   |
| Intel Core 2 Duo                        | 2         | 2.78%   |
| AMD Ryzen 7 5700U with Radeon Graphics  | 2         | 2.78%   |
| AMD EPYC 3201 8-Core Processor          | 2         | 2.78%   |
| AMD E1-2500 APU with Radeon HD Graphics | 2         | 2.78%   |
| Intel Pentium CPU N3530 @ 2.16GHz       | 1         | 1.39%   |
| Intel Core m7-6Y75 CPU @ 1.20GHz        | 1         | 1.39%   |
| Intel Core m3-6Y30 CPU @ 0.90GHz        | 1         | 1.39%   |
| Intel Core i7-8665U CPU @ 1.90GHz       | 1         | 1.39%   |
| Intel Core i7-8565U CPU @ 1.80GHz       | 1         | 1.39%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz      | 1         | 1.39%   |
| Intel Core i7-6500U CPU @ 2.50GHz       | 1         | 1.39%   |
| Intel Core i7-5600U CPU @ 2.60GHz       | 1         | 1.39%   |
| Intel Core i7-5500U CPU @ 2.40GHz       | 1         | 1.39%   |
| Intel Core i7-3615QM CPU @ 2.30GHz      | 1         | 1.39%   |
| Intel Core i7-3612QM CPU @ 2.10GHz      | 1         | 1.39%   |
| Intel Core i7-10710U CPU @ 1.10GHz      | 1         | 1.39%   |
| Intel Core i5-8350U CPU @ 1.70GHz       | 1         | 1.39%   |
| Intel Core i5-6200U CPU @ 2.30GHz       | 1         | 1.39%   |
| Intel Core i5-4310M CPU @ 2.70GHz       | 1         | 1.39%   |
| Intel Core i5-4200U CPU @ 1.60GHz       | 1         | 1.39%   |
| Intel Core i5-3320M CPU @ 2.60GHz       | 1         | 1.39%   |
| Intel Core i5-2520M CPU @ 2.50GHz       | 1         | 1.39%   |
| Intel Core i5-2435M CPU @ 2.40GHz       | 1         | 1.39%   |
| Intel Core i5-10210U CPU @ 1.60GHz      | 1         | 1.39%   |
| Intel Core i3-7100U CPU @ 2.40GHz       | 1         | 1.39%   |
| Intel Core i3-5005U CPU @ 2.00GHz       | 1         | 1.39%   |
| Intel Core i3 CPU M 330 @ 2.13GHz       | 1         | 1.39%   |
| Intel Core 2 Duo CPU P7500 @ 1.60GHz    | 1         | 1.39%   |
| Intel Core 2 Duo CPU L9400 @ 1.86GHz    | 1         | 1.39%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart_bsd/cpu_family.svg)


| Model              | Notebooks | Percent |
|--------------------|-----------|---------|
| Intel Core i7      | 21        | 29.17%  |
| Intel Core i5      | 14        | 19.44%  |
| Other              | 6         | 8.33%   |
| Intel Core 2 Duo   | 6         | 8.33%   |
| AMD Ryzen 7        | 4         | 5.56%   |
| Intel Core i3      | 3         | 4.17%   |
| AMD Ryzen Embedded | 3         | 4.17%   |
| AMD EPYC           | 2         | 2.78%   |
| AMD E1             | 2         | 2.78%   |
| Intel Pentium      | 1         | 1.39%   |
| Intel Core m7      | 1         | 1.39%   |
| Intel Core m3      | 1         | 1.39%   |
| Intel Celeron      | 1         | 1.39%   |
| Intel Atom         | 1         | 1.39%   |
| AMD Ryzen 5 PRO    | 1         | 1.39%   |
| AMD G              | 1         | 1.39%   |
| AMD E2             | 1         | 1.39%   |
| AMD Athlon II      | 1         | 1.39%   |
| AMD A8             | 1         | 1.39%   |
| AMD A6             | 1         | 1.39%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart_bsd/cpu_cores.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 37        | 51.39%  |
| 4       | 16        | 22.22%  |
| 8       | 8         | 11.11%  |
| Unknown | 4         | 5.56%   |
| 16      | 3         | 4.17%   |
| 6       | 3         | 4.17%   |
| 20      | 1         | 1.39%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart_bsd/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 71        | 98.61%  |
| 2      | 1         | 1.39%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart_bsd/cpu_threads.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 44        | 61.11%  |
| 1       | 24        | 33.33%  |
| Unknown | 4         | 5.56%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart_bsd/cpu_microarch.svg)


| Name        | Notebooks | Percent |
|-------------|-----------|---------|
| KabyLake    | 10        | 13.89%  |
| IvyBridge   | 7         | 9.72%   |
| Haswell     | 7         | 9.72%   |
| Zen         | 6         | 8.33%   |
| Skylake     | 6         | 8.33%   |
| Unknown     | 6         | 8.33%   |
| Broadwell   | 5         | 6.94%   |
| SandyBridge | 4         | 5.56%   |
| Penryn      | 4         | 5.56%   |
| Zen 2       | 2         | 2.78%   |
| TigerLake   | 2         | 2.78%   |
| Jaguar      | 2         | 2.78%   |
| Core        | 2         | 2.78%   |
| Westmere    | 1         | 1.39%   |
| Silvermont  | 1         | 1.39%   |
| Piledriver  | 1         | 1.39%   |
| K10 Llano   | 1         | 1.39%   |
| K10         | 1         | 1.39%   |
| Excavator   | 1         | 1.39%   |
| CometLake   | 1         | 1.39%   |
| Bonnell     | 1         | 1.39%   |
| Bobcat      | 1         | 1.39%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart_bsd/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 54        | 71.05%  |
| AMD    | 13        | 17.11%  |
| Nvidia | 9         | 11.84%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart_bsd/gpu_model.svg)


| Model                                                                     | Notebooks | Percent |
|---------------------------------------------------------------------------|-----------|---------|
| Intel 3rd Gen Core processor Graphics Controller                          | 7         | 8.64%   |
| Intel Haswell-ULT Integrated Graphics Controller                          | 6         | 7.41%   |
| Intel HD Graphics 5500                                                    | 5         | 6.17%   |
| Intel Skylake GT2 [HD Graphics 520]                                       | 4         | 4.94%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller              | 4         | 4.94%   |
| Intel HD Graphics 620                                                     | 3         | 3.7%    |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller | 3         | 3.7%    |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                   | 2         | 2.47%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                | 2         | 2.47%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                 | 2         | 2.47%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)       | 2         | 2.47%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)         | 2         | 2.47%   |
| Intel HD Graphics 515                                                     | 2         | 2.47%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                 | 2         | 2.47%   |
| Intel Alder Lake-P GT2 [Iris Xe Graphics]                                 | 2         | 2.47%   |
| Intel Alder Lake-N [UHD Graphics]                                         | 2         | 2.47%   |
| AMD Renoir [Radeon RX Vega 6 (Ryzen 4000/5000 Mobile Series)]             | 2         | 2.47%   |
| AMD Lucienne                                                              | 2         | 2.47%   |
| AMD Kabini [Radeon HD 8240 / R3 Series]                                   | 2         | 2.47%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                           | 1         | 1.23%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                | 1         | 1.23%   |
| Nvidia GM108M [GeForce 940M]                                              | 1         | 1.23%   |
| Nvidia GK107M [GeForce GT 650M Mac Edition]                               | 1         | 1.23%   |
| Nvidia GF108M [NVS 5400M]                                                 | 1         | 1.23%   |
| Nvidia GF108M [GeForce GT 540M]                                           | 1         | 1.23%   |
| Nvidia GF108GLM [Quadro 1000M]                                            | 1         | 1.23%   |
| Intel UHD Graphics 620                                                    | 1         | 1.23%   |
| Intel HD Graphics 630                                                     | 1         | 1.23%   |
| Intel DG2 [Arc A730M]                                                     | 1         | 1.23%   |
| Intel Core Processor Integrated Graphics Controller                       | 1         | 1.23%   |
| Intel CometLake-U GT2 [UHD Graphics]                                      | 1         | 1.23%   |
| Intel Comet Lake UHD Graphics                                             | 1         | 1.23%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display              | 1         | 1.23%   |
| Intel Atom Processor D2xxx/N2xxx Integrated Graphics Controller           | 1         | 1.23%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller               | 1         | 1.23%   |
| AMD Wrestler [Radeon HD 6310]                                             | 1         | 1.23%   |
| AMD Whistler [Radeon HD 6630M/6650M/6750M/7670M/7690M]                    | 1         | 1.23%   |
| AMD Trinity [Radeon HD 7640G]                                             | 1         | 1.23%   |
| AMD Sun PRO [Radeon HD 8570A/8570M]                                       | 1         | 1.23%   |
| AMD Sumo [Radeon HD 6520G]                                                | 1         | 1.23%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart_bsd/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 40        | 53.33%  |
| 1 x AMD        | 11        | 14.67%  |
| Intel + Nvidia | 8         | 10.67%  |
| 2 x Intel      | 7         | 9.33%   |
| Other          | 5         | 6.67%   |
| 2 x AMD        | 2         | 2.67%   |
| 1 x Nvidia     | 2         | 2.67%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart_bsd/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 65        | 87.84%  |
| Unknown     | 6         | 8.11%   |
| Proprietary | 3         | 4.05%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart_bsd/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 63        | 86.3%   |
| 0.01-0.5   | 6         | 8.22%   |
| 1.01-2.0   | 2         | 2.74%   |
| 0.51-1.0   | 2         | 2.74%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart_bsd/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| LG Display              | 11        | 20%     |
| Chimei Innolux          | 10        | 18.18%  |
| AU Optronics            | 8         | 14.55%  |
| BOE                     | 7         | 12.73%  |
| Samsung Electronics     | 4         | 7.27%   |
| Apple                   | 4         | 7.27%   |
| Lenovo                  | 3         | 5.45%   |
| Sharp                   | 2         | 3.64%   |
| Sony                    | 1         | 1.82%   |
| Philips                 | 1         | 1.82%   |
| PANDA                   | 1         | 1.82%   |
| Hewlett-Packard         | 1         | 1.82%   |
| Chi Mei Optoelectronics | 1         | 1.82%   |
| AOC                     | 1         | 1.82%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart_bsd/mon_model.svg)


| Model                                                                    | Notebooks | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| LG Display LCD Monitor LGD11F9 1280x800 290x180mm 13.4-inch              | 2         | 3.64%   |
| Sony LCD SNY06FA 1600x900 290x160mm 13.0-inch                            | 1         | 1.82%   |
| Sharp LCD Monitor SHP1461 3200x1800 290x170mm 13.2-inch                  | 1         | 1.82%   |
| Sharp LCD Monitor SHP1453 1920x1080 350x190mm 15.7-inch                  | 1         | 1.82%   |
| Samsung Electronics LCD Monitor SEC4541 1280x800 260x160mm 12.0-inch     | 1         | 1.82%   |
| Samsung Electronics LCD Monitor SEC324C 1600x900 310x170mm 13.9-inch     | 1         | 1.82%   |
| Samsung Electronics LCD Monitor SEC3047 1366x768 280x160mm 12.7-inch     | 1         | 1.82%   |
| Samsung Electronics LCD Monitor SDC4347 1366x768 340x190mm 15.3-inch     | 1         | 1.82%   |
| Philips PHL 328E1 PHLC204 3840x2160 700x390mm 31.5-inch                  | 1         | 1.82%   |
| PANDA LC133LF1L02 NCP0019 1920x1080 290x170mm 13.2-inch                  | 1         | 1.82%   |
| LG Display LCD Monitor LGD05C0 1920x1080 344x194mm 15.5-inch             | 1         | 1.82%   |
| LG Display LCD Monitor LGD058B 2560x1440 310x170mm 13.9-inch             | 1         | 1.82%   |
| LG Display LCD Monitor LGD0450 1366x768 280x160mm 12.7-inch              | 1         | 1.82%   |
| LG Display LCD Monitor LGD0437 1920x1080 280x160mm 12.7-inch             | 1         | 1.82%   |
| LG Display LCD Monitor LGD0414 1920x1080 280x160mm 12.7-inch             | 1         | 1.82%   |
| LG Display LCD Monitor LGD0408 1920x1080 280x160mm 12.7-inch             | 1         | 1.82%   |
| LG Display LCD Monitor LGD03ED 1366x768 280x160mm 12.7-inch              | 1         | 1.82%   |
| LG Display LCD Monitor LGD02D8 1366x768 280x160mm 12.7-inch              | 1         | 1.82%   |
| LG Display LCD Monitor LGD02AD 1366x768 340x190mm 15.3-inch              | 1         | 1.82%   |
| Lenovo LCD Monitor LEN40B1 1600x900 350x190mm 15.7-inch                  | 1         | 1.82%   |
| Lenovo LCD Monitor LEN4010 1280x800 260x160mm 12.0-inch                  | 1         | 1.82%   |
| Lenovo LCD Monitor LEN4000 1024x768 250x180mm 12.1-inch                  | 1         | 1.82%   |
| Hewlett-Packard LA1951 HWP285A 1280x1024 380x300mm 19.1-inch             | 1         | 1.82%   |
| Chimei Innolux LCD Monitor CMN175A 1920x1080 380x210mm 17.1-inch         | 1         | 1.82%   |
| Chimei Innolux LCD Monitor CMN1734 1600x900 380x210mm 17.1-inch          | 1         | 1.82%   |
| Chimei Innolux LCD Monitor CMN15C9 1366x768 340x190mm 15.3-inch          | 1         | 1.82%   |
| Chimei Innolux LCD Monitor CMN15C3 1920x1080 340x190mm 15.3-inch         | 1         | 1.82%   |
| Chimei Innolux LCD Monitor CMN15BF 1366x768 340x190mm 15.3-inch          | 1         | 1.82%   |
| Chimei Innolux LCD Monitor CMN15B5 1366x768 340x190mm 15.3-inch          | 1         | 1.82%   |
| Chimei Innolux LCD Monitor CMN152D 1920x1080 340x190mm 15.3-inch         | 1         | 1.82%   |
| Chimei Innolux LCD Monitor CMN1490 1366x768 310x170mm 13.9-inch          | 1         | 1.82%   |
| Chimei Innolux LCD Monitor CMN1404 1920x1080 310x170mm 13.9-inch         | 1         | 1.82%   |
| Chimei Innolux LCD Monitor CMN1239 1920x1080 280x160mm 12.7-inch         | 1         | 1.82%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A7 1366x768 350x190mm 15.7-inch | 1         | 1.82%   |
| BOE LCD Monitor BOE0A81 1920x1080 340x190mm 15.3-inch                    | 1         | 1.82%   |
| BOE LCD Monitor BOE0921 1920x515 310x80mm 12.6-inch                      | 1         | 1.82%   |
| BOE LCD Monitor BOE07F7 1920x1080 310x170mm 13.9-inch                    | 1         | 1.82%   |
| BOE LCD Monitor BOE07D8 1920x1080 340x190mm 15.3-inch                    | 1         | 1.82%   |
| BOE LCD Monitor BOE07C8 3840x2160 310x170mm 13.9-inch                    | 1         | 1.82%   |
| BOE LCD Monitor BOE06BF 1920x1080 280x160mm 12.7-inch                    | 1         | 1.82%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart_bsd/mon_resolution.svg)


| Resolution       | Notebooks | Percent |
|------------------|-----------|---------|
| 1920x1080 (FHD)  | 21        | 38.18%  |
| 1366x768 (WXGA)  | 13        | 23.64%  |
| 1280x800 (WXGA)  | 7         | 12.73%  |
| 1600x900 (HD+)   | 5         | 9.09%   |
| 3840x2160 (4K)   | 3         | 5.45%   |
| 2560x1440 (QHD)  | 2         | 3.64%   |
| 3200x1800 (QHD+) | 1         | 1.82%   |
| 2880x1800        | 1         | 1.82%   |
| 1920x515         | 1         | 1.82%   |
| 1280x1024 (SXGA) | 1         | 1.82%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart_bsd/mon_diagonal.svg)


| Inches | Notebooks | Percent |
|--------|-----------|---------|
| 13     | 18        | 32.73%  |
| 15     | 17        | 30.91%  |
| 12     | 14        | 25.45%  |
| 17     | 2         | 3.64%   |
| 31     | 1         | 1.82%   |
| 27     | 1         | 1.82%   |
| 23     | 1         | 1.82%   |
| 19     | 1         | 1.82%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart_bsd/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 27        | 50%     |
| 201-300     | 21        | 38.89%  |
| 351-400     | 3         | 5.56%   |
| 601-700     | 2         | 3.7%    |
| 501-600     | 1         | 1.85%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart_bsd/mon_ratio.svg)


| Ratio | Notebooks | Percent |
|-------|-----------|---------|
| 16/9  | 44        | 81.48%  |
| 16/10 | 7         | 12.96%  |
| 5/4   | 1         | 1.85%   |
| 3/2   | 1         | 1.85%   |
| 3.88  | 1         | 1.85%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart_bsd/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 81-90          | 15        | 27.27%  |
| 61-70          | 13        | 23.64%  |
| 91-100         | 12        | 21.82%  |
| 101-110        | 5         | 9.09%   |
| 71-80          | 3         | 5.45%   |
| 121-130        | 2         | 3.64%   |
| 351-500        | 1         | 1.82%   |
| 1-40           | 1         | 1.82%   |
| 301-350        | 1         | 1.82%   |
| 201-250        | 1         | 1.82%   |
| 151-200        | 1         | 1.82%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart_bsd/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 24        | 45.28%  |
| 101-120       | 14        | 26.42%  |
| 161-240       | 10        | 18.87%  |
| 51-100        | 3         | 5.66%   |
| More than 240 | 2         | 3.77%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart_bsd/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 53        | 71.62%  |
| 0     | 17        | 22.97%  |
| 2     | 4         | 5.41%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart_bsd/net_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 56        | 49.56%  |
| Realtek Semiconductor             | 26        | 23.01%  |
| Qualcomm Atheros                  | 8         | 7.08%   |
| Broadcom                          | 7         | 6.19%   |
| AMD                               | 5         | 4.42%   |
| TP-Link                           | 3         | 2.65%   |
| Sierra Wireless                   | 1         | 0.88%   |
| Ralink Technology                 | 1         | 0.88%   |
| Ralink                            | 1         | 0.88%   |
| MediaTek                          | 1         | 0.88%   |
| HMD Global                        | 1         | 0.88%   |
| Hewlett-Packard                   | 1         | 0.88%   |
| Fibocom                           | 1         | 0.88%   |
| Ericsson Business Mobile Networks | 1         | 0.88%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart_bsd/net_model.svg)


| Model                                                                  | Notebooks | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 19        | 13.38%  |
| Intel Wireless 7265                                                    | 6         | 4.23%   |
| Intel Wireless 7260                                                    | 6         | 4.23%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter             | 5         | 3.52%   |
| Intel Wi-Fi 6 AX200                                                    | 5         | 3.52%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 5         | 3.52%   |
| AMD XGMAC 10GbE Controller                                             | 5         | 3.52%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                    | 4         | 2.82%   |
| Intel Wireless 8265 / 8275                                             | 4         | 2.82%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                           | 4         | 2.82%   |
| Intel 82567LM Gigabit Network Connection                               | 4         | 2.82%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 3         | 2.11%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)         | 3         | 2.11%   |
| Intel Wireless 8260                                                    | 3         | 2.11%   |
| Intel I211 Gigabit Network Connection                                  | 3         | 2.11%   |
| Intel Ethernet Connection (3) I218-LM                                  | 3         | 2.11%   |
| Broadcom BCM4331 802.11a/b/g/n                                         | 3         | 2.11%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]             | 2         | 1.41%   |
| Intel WiFi Link 5100                                                   | 2         | 1.41%   |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]                | 2         | 1.41%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection                | 2         | 1.41%   |
| Intel I210 Gigabit Network Connection                                  | 2         | 1.41%   |
| Intel Ethernet Connection I219-LM                                      | 2         | 1.41%   |
| Intel Ethernet Connection I218-LM                                      | 2         | 1.41%   |
| Intel Ethernet Connection (4) I219-LM                                  | 2         | 1.41%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                      | 2         | 1.41%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                               | 2         | 1.41%   |
| Intel Cannon Lake PCH CNVi WiFi                                        | 2         | 1.41%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                      | 2         | 1.41%   |
| TP-Link Wireless USB Adapter                                           | 1         | 0.7%    |
| Sierra Wireless EM7455                                                 | 1         | 0.7%    |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter               | 1         | 0.7%    |
| Realtek RTL8188CUS 802.11n WLAN Adapter                                | 1         | 0.7%    |
| Ralink RT5370 Wireless Adapter                                         | 1         | 0.7%    |
| Ralink RT3592 Wireless 802.11abgn 2T/2R PCIe                           | 1         | 0.7%    |
| Qualcomm Atheros QCA8172 Fast Ethernet                                 | 1         | 0.7%    |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                              | 1         | 0.7%    |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter          | 1         | 0.7%    |
| Intel Wireless 3160                                                    | 1         | 0.7%    |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]              | 1         | 0.7%    |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart_bsd/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 45        | 62.5%   |
| Qualcomm Atheros      | 8         | 11.11%  |
| Realtek Semiconductor | 6         | 8.33%   |
| Broadcom              | 6         | 8.33%   |
| TP-Link               | 3         | 4.17%   |
| Sierra Wireless       | 1         | 1.39%   |
| Ralink Technology     | 1         | 1.39%   |
| Ralink                | 1         | 1.39%   |
| MediaTek              | 1         | 1.39%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart_bsd/net_wireless_model.svg)


| Model                                                          | Notebooks | Percent |
|----------------------------------------------------------------|-----------|---------|
| Intel Wireless 7265                                            | 6         | 8.33%   |
| Intel Wireless 7260                                            | 6         | 8.33%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 5         | 6.94%   |
| Intel Wi-Fi 6 AX200                                            | 5         | 6.94%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter            | 4         | 5.56%   |
| Intel Wireless 8265 / 8275                                     | 4         | 5.56%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 4         | 5.56%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 3         | 4.17%   |
| Intel Wireless 8260                                            | 3         | 4.17%   |
| Broadcom BCM4331 802.11a/b/g/n                                 | 3         | 4.17%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]     | 2         | 2.78%   |
| Intel WiFi Link 5100                                           | 2         | 2.78%   |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]        | 2         | 2.78%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection        | 2         | 2.78%   |
| Intel Comet Lake PCH-LP CNVi WiFi                              | 2         | 2.78%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                       | 2         | 2.78%   |
| Intel Cannon Lake PCH CNVi WiFi                                | 2         | 2.78%   |
| TP-Link Wireless USB Adapter                                   | 1         | 1.39%   |
| Sierra Wireless EM7455                                         | 1         | 1.39%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 1         | 1.39%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                        | 1         | 1.39%   |
| Ralink RT5370 Wireless Adapter                                 | 1         | 1.39%   |
| Ralink RT3592 Wireless 802.11abgn 2T/2R PCIe                   | 1         | 1.39%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter  | 1         | 1.39%   |
| Intel Wireless 3160                                            | 1         | 1.39%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]      | 1         | 1.39%   |
| Intel Wi-Fi 6 AX201                                            | 1         | 1.39%   |
| Intel Centrino Ultimate-N 6300                                 | 1         | 1.39%   |
| Intel Centrino Advanced-N 6235                                 | 1         | 1.39%   |
| Broadcom BCM4321 802.11a/b/g/n                                 | 1         | 1.39%   |
| Broadcom BCM43142 802.11b/g/n                                  | 1         | 1.39%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter            | 1         | 1.39%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart_bsd/net_ethernet_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 33        | 49.25%  |
| Realtek Semiconductor | 22        | 32.84%  |
| AMD                   | 5         | 7.46%   |
| Broadcom              | 4         | 5.97%   |
| Qualcomm Atheros      | 2         | 2.99%   |
| HMD Global            | 1         | 1.49%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart_bsd/net_ethernet_model.svg)


| Model                                                                  | Notebooks | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 19        | 28.36%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 5         | 7.46%   |
| AMD XGMAC 10GbE Controller                                             | 5         | 7.46%   |
| Intel 82567LM Gigabit Network Connection                               | 4         | 5.97%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 3         | 4.48%   |
| Intel I211 Gigabit Network Connection                                  | 3         | 4.48%   |
| Intel Ethernet Connection (3) I218-LM                                  | 3         | 4.48%   |
| Intel I210 Gigabit Network Connection                                  | 2         | 2.99%   |
| Intel Ethernet Connection I219-LM                                      | 2         | 2.99%   |
| Intel Ethernet Connection I218-LM                                      | 2         | 2.99%   |
| Intel Ethernet Connection (4) I219-LM                                  | 2         | 2.99%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                      | 2         | 2.99%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                                 | 1         | 1.49%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                              | 1         | 1.49%   |
| Intel Ethernet Controller I225-V                                       | 1         | 1.49%   |
| Intel Ethernet Connection I219-V                                       | 1         | 1.49%   |
| Intel Ethernet Connection I218-V                                       | 1         | 1.49%   |
| Intel Ethernet Connection I217-V                                       | 1         | 1.49%   |
| Intel Ethernet Connection (6) I219-V                                   | 1         | 1.49%   |
| Intel Ethernet Connection (6) I219-LM                                  | 1         | 1.49%   |
| Intel Ethernet Connection (16) I219-V                                  | 1         | 1.49%   |
| Intel 82577LM Gigabit Network Connection                               | 1         | 1.49%   |
| Intel 82574L Gigabit Network Connection                                | 1         | 1.49%   |
| Intel 82566MM Gigabit Network Connection                               | 1         | 1.49%   |
| HMD Global Nokia 5.3 RNDIS Control RNDIS Ethernet Data                 | 1         | 1.49%   |
| Broadcom NetXtreme BCM57786 Gigabit Ethernet PCIe                      | 1         | 1.49%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                       | 1         | 1.49%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart_bsd/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 62        | 49.21%  |
| Ethernet | 61        | 48.41%  |
| Modem    | 2         | 1.59%   |
| Unknown  | 1         | 0.79%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart_bsd/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| Ethernet | 47        | 52.22%  |
| WiFi     | 43        | 47.78%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart_bsd/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 50        | 69.44%  |
| 1     | 14        | 19.44%  |
| 6     | 3         | 4.17%   |
| 5     | 3         | 4.17%   |
| 3     | 2         | 2.78%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart_bsd/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 61        | 80.26%  |
| Yes  | 15        | 19.74%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart_bsd/bt_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 29        | 63.04%  |
| Broadcom              | 4         | 8.7%    |
| Apple                 | 4         | 8.7%    |
| IMC Networks          | 3         | 6.52%   |
| Foxconn / Hon Hai     | 2         | 4.35%   |
| Realtek Semiconductor | 1         | 2.17%   |
| Lite-On Technology    | 1         | 2.17%   |
| Hewlett-Packard       | 1         | 2.17%   |
| Dell                  | 1         | 2.17%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart_bsd/bt_model.svg)


| Model                                                  | Notebooks | Percent |
|--------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                     | 13        | 28.26%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)         | 5         | 10.87%  |
| Intel AX200 Bluetooth                                  | 5         | 10.87%  |
| Intel Wireless-AC 9260 Bluetooth Adapter               | 2         | 4.35%   |
| Intel AX201 Bluetooth                                  | 2         | 4.35%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]             | 2         | 4.35%   |
| Apple Bluetooth Host Controller                        | 2         | 4.35%   |
| Realtek Bluetooth Adapter                              | 1         | 2.17%   |
| Lite-On Atheros AR3012 Bluetooth                       | 1         | 2.17%   |
| Intel Centrino Bluetooth Wireless Transceiver          | 1         | 2.17%   |
| Intel AX210 Bluetooth                                  | 1         | 2.17%   |
| IMC Networks Qualcomm Atheros Bluetooth 4.0 + HS       | 1         | 2.17%   |
| IMC Networks Qualcomm Atheros Bluetooth 4.0            | 1         | 2.17%   |
| IMC Networks Asus Integrated Bluetooth module [AR3011] | 1         | 2.17%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]          | 1         | 2.17%   |
| Foxconn / Hon Hai MediaTek Bluetooth Adapter           | 1         | 2.17%   |
| Foxconn / Hon Hai BCM43142A0 broadcom bluetooth        | 1         | 2.17%   |
| Dell Dell Wireless 380 Bluetooth 4.0 Module            | 1         | 2.17%   |
| Broadcom BCM2070 Bluetooth 2.1 + EDR                   | 1         | 2.17%   |
| Broadcom BCM2045B (BDC-2.1)                            | 1         | 2.17%   |
| Apple Broadcom Built-in Bluetooth                      | 1         | 2.17%   |
| Apple Broadcom Bluetooth 2.1 module                    | 1         | 2.17%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart_bsd/snd_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 54        | 72.97%  |
| AMD    | 17        | 22.97%  |
| Nvidia | 3         | 4.05%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart_bsd/snd_model.svg)


| Model                                                                             | Notebooks | Percent |
|-----------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                                   | 9         | 9.09%   |
| AMD Family 17h/19h HD Audio Controller                                            | 8         | 8.08%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller               | 7         | 7.07%   |
| Intel Haswell-ULT HD Audio Controller                                             | 6         | 6.06%   |
| Intel 8 Series HD Audio Controller                                                | 6         | 6.06%   |
| Intel Wildcat Point-LP High Definition Audio Controller                           | 5         | 5.05%   |
| Intel Broadwell-U Audio Controller                                                | 5         | 5.05%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                    | 4         | 4.04%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller        | 4         | 4.04%   |
| AMD Renoir Radeon High Definition Audio Controller                                | 4         | 4.04%   |
| AMD FCH Azalia Controller                                                         | 4         | 4.04%   |
| Nvidia GF108 High Definition Audio Controller                                     | 2         | 2.02%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                       | 2         | 2.02%   |
| Intel Comet Lake PCH-LP cAVS                                                      | 2         | 2.02%   |
| Intel Cannon Point-LP High Definition Audio Controller                            | 2         | 2.02%   |
| Intel Cannon Lake PCH cAVS                                                        | 2         | 2.02%   |
| Intel Alder Lake-N PCH High Definition Audio Controller                           | 2         | 2.02%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                           | 2         | 2.02%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                    | 2         | 2.02%   |
| AMD SBx00 Azalia (Intel HDA)                                                      | 2         | 2.02%   |
| AMD Kabini HDMI/DP Audio                                                          | 2         | 2.02%   |
| Nvidia GK107 HDMI Audio Controller                                                | 1         | 1.01%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                  | 1         | 1.01%   |
| Intel DG2 Audio Controller                                                        | 1         | 1.01%   |
| Intel CM238 HD Audio Controller                                                   | 1         | 1.01%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller        | 1         | 1.01%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                  | 1         | 1.01%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller               | 1         | 1.01%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                          | 1         | 1.01%   |
| AMD Wrestler HDMI Audio                                                           | 1         | 1.01%   |
| AMD Trinity HDMI Audio Controller                                                 | 1         | 1.01%   |
| AMD RS880 HDMI Audio [Radeon HD 4200 Series]                                      | 1         | 1.01%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                               | 1         | 1.01%   |
| AMD High Definition Audio Controller                                              | 1         | 1.01%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                               | 1         | 1.01%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                  | 1         | 1.01%   |
| AMD Caicos HDMI Audio [Radeon HD 6450 / 7450/8450/8490 OEM / R5 230/235/235X OEM] | 1         | 1.01%   |
| AMD BeaverCreek HDMI Audio [Radeon HD 6500D and 6400G-6600G series]               | 1         | 1.01%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart_bsd/memory_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Samsung Electronics   | 19        | 26.76%  |
| Micron Technology     | 12        | 16.9%   |
| SK hynix              | 10        | 14.08%  |
| Unknown               | 5         | 7.04%   |
| Transcend             | 5         | 7.04%   |
| Crucial               | 4         | 5.63%   |
| Kingston              | 3         | 4.23%   |
| Elpida                | 3         | 4.23%   |
| Ramaxel Technology    | 2         | 2.82%   |
| Apacer                | 2         | 2.82%   |
| Team                  | 1         | 1.41%   |
| Nanya Technology      | 1         | 1.41%   |
| Kingmax Semiconductor | 1         | 1.41%   |
| G.Skill               | 1         | 1.41%   |
| Corsair               | 1         | 1.41%   |
| A-DATA Technology     | 1         | 1.41%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart_bsd/memory_model.svg)


| Model                                                        | Notebooks | Percent |
|--------------------------------------------------------------|-----------|---------|
| Transcend RAM TS1GLH64V6BL 8GB SODIMM DDR4 2667MT/s          | 4         | 5.56%   |
| Samsung RAM Module 4GB Row Of Chips LPDDR5 4000MT/s          | 2         | 2.78%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s        | 2         | 2.78%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s        | 2         | 2.78%   |
| Elpida RAM EBJ41UF8BCS0-DJ-F 4GB SODIMM DDR3 1334MT/s        | 2         | 2.78%   |
| Unknown RAM Module 8GB SODIMM LPDDR3 1867MT/s                | 1         | 1.39%   |
| Unknown RAM Module 4GB SODIMM DDR3 1067MT/s                  | 1         | 1.39%   |
| Unknown RAM Module 4GB SODIMM DDR3                           | 1         | 1.39%   |
| Unknown RAM Module 2GB SODIMM DDR3 1067MT/s                  | 1         | 1.39%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                   | 1         | 1.39%   |
| Unknown RAM Module 1GB SODIMM DDR2 667MT/s                   | 1         | 1.39%   |
| Transcend RAM TS512MLH64V6HL 4GB SODIMM DDR4 2667MT/s        | 1         | 1.39%   |
| Team RAM TEAMGROUP-SD4-2400 8GB SODIMM DDR4 2400MT/s         | 1         | 1.39%   |
| SK hynix RAM Module 8GB SODIMM DDR4 2133MT/s                 | 1         | 1.39%   |
| SK hynix RAM Module 4GB SODIMM DDR3 1600MT/s                 | 1         | 1.39%   |
| SK hynix RAM Module 4096MB SODIMM DDR3 1333MT/s              | 1         | 1.39%   |
| SK hynix RAM HMT451S6MFR8A-PB 4GB SODIMM DDR3 800MT/s        | 1         | 1.39%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s       | 1         | 1.39%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s       | 1         | 1.39%   |
| SK hynix RAM HMT41GS6AFR8A-PB 8GB SODIMM DDR3 1600MT/s       | 1         | 1.39%   |
| SK hynix RAM HMT351S6EFR8C-PB 4GB SODIMM DDR3 1600MT/s       | 1         | 1.39%   |
| SK hynix RAM HMT351S6CFR8A-PB 4GB SODIMM DDR3 1333MT/s       | 1         | 1.39%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB Row Of Chips DDR4 3200MT/s | 1         | 1.39%   |
| Samsung RAM Module 8GB SODIMM DDR4 2133MT/s                  | 1         | 1.39%   |
| Samsung RAM Module 8GB Row Of Chips LPDDR3 2133MT/s          | 1         | 1.39%   |
| Samsung RAM M471B5673FH0-CH9 2GB SODIMM DDR3 1334MT/s        | 1         | 1.39%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s        | 1         | 1.39%   |
| Samsung RAM M471B5174BM0-YK0 4GB SODIMM DDR3 1600MT/s        | 1         | 1.39%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s        | 1         | 1.39%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1867MT/s        | 1         | 1.39%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s        | 1         | 1.39%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 2667MT/s        | 1         | 1.39%   |
| Samsung RAM M471A4G43AB1-CWE 32GB SODIMM DDR4 3200MT/s       | 1         | 1.39%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s        | 1         | 1.39%   |
| Samsung RAM M425R1GB4BB0-CQKOL 8GB SODIMM DDR5 4800MT/s      | 1         | 1.39%   |
| Samsung RAM K4E6E304EB-EGCF 4GB 1867MT/s                     | 1         | 1.39%   |
| Ramaxel RAM RMT3170MN68F9F1600 4GB SODIMM DDR3 1600MT/s      | 1         | 1.39%   |
| Ramaxel RAM RMT3020EF48E8W1333 2GB SODIMM DDR3 1334MT/s      | 1         | 1.39%   |
| Nanya RAM NT2GC64B8HA1NS-BE 2GB SODIMM DDR3 1067MT/s         | 1         | 1.39%   |
| Micron RAM MT41K512M16TNA-125 4GB Chip DDR3 1600MT/s         | 1         | 1.39%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart_bsd/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR3    | 31        | 49.21%  |
| DDR4    | 22        | 34.92%  |
| DDR2    | 3         | 4.76%   |
| LPDDR5  | 2         | 3.17%   |
| LPDDR3  | 2         | 3.17%   |
| LPDDR4  | 1         | 1.59%   |
| DDR5    | 1         | 1.59%   |
| Unknown | 1         | 1.59%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart_bsd/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 55        | 85.94%  |
| Row Of Chips | 5         | 7.81%   |
| Chip         | 3         | 4.69%   |
| Unknown      | 1         | 1.56%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart_bsd/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 4096  | 29        | 42.03%  |
| 8192  | 24        | 34.78%  |
| 2048  | 8         | 11.59%  |
| 16384 | 6         | 8.7%    |
| 32768 | 1         | 1.45%   |
| 1024  | 1         | 1.45%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart_bsd/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 1600    | 18        | 27.69%  |
| 2667    | 11        | 16.92%  |
| 3200    | 5         | 7.69%   |
| 1867    | 4         | 6.15%   |
| 1334    | 4         | 6.15%   |
| 2400    | 3         | 4.62%   |
| 2133    | 3         | 4.62%   |
| 1333    | 3         | 4.62%   |
| 4000    | 2         | 3.08%   |
| 1866    | 2         | 3.08%   |
| 1067    | 2         | 3.08%   |
| 800     | 2         | 3.08%   |
| 667     | 2         | 3.08%   |
| 4800    | 1         | 1.54%   |
| 4267    | 1         | 1.54%   |
| 1066    | 1         | 1.54%   |
| Unknown | 1         | 1.54%   |

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
| Chicony Electronics                    | 17        | 34.69%  |
| IMC Networks                           | 7         | 14.29%  |
| Realtek Semiconductor                  | 6         | 12.24%  |
| Lite-On Technology                     | 4         | 8.16%   |
| Microdia                               | 3         | 6.12%   |
| Bison Electronics                      | 3         | 6.12%   |
| Apple                                  | 3         | 6.12%   |
| Cheng Uei Precision Industry (Foxlink) | 2         | 4.08%   |
| Alcor Micro                            | 2         | 4.08%   |
| Sunplus Innovation Technology          | 1         | 2.04%   |
| Ricoh                                  | 1         | 2.04%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart_bsd/camera_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                           | 4         | 8.16%   |
| IMC Networks Integrated Camera                      | 3         | 6.12%   |
| Realtek USB Camera                                  | 2         | 4.08%   |
| Realtek Integrated_Webcam_HD                        | 2         | 4.08%   |
| Microdia Integrated_Webcam_HD                       | 2         | 4.08%   |
| Lite-On Integrated Camera                           | 2         | 4.08%   |
| IMC Networks Realtek PC Camera                      | 2         | 4.08%   |
| Chicony Realtek DMFT RGB                            | 2         | 4.08%   |
| Chicony Chicony USB2.0 Camera                       | 2         | 4.08%   |
| Bison Integrated Camera                             | 2         | 4.08%   |
| Apple FaceTime HD Camera                            | 2         | 4.08%   |
| Sunplus Laptop Integrated Webcam HD                 | 1         | 2.04%   |
| Ricoh USB2.0 Camera                                 | 1         | 2.04%   |
| Realtek Lenovo EasyCamera                           | 1         | 2.04%   |
| Realtek Integrated Webcam HD                        | 1         | 2.04%   |
| Microdia Dell Integrated HD Webcam                  | 1         | 2.04%   |
| Lite-On TOSHIBA Web Camera - HD                     | 1         | 2.04%   |
| Lite-On HP Universal Camera                         | 1         | 2.04%   |
| IMC Networks USB2.0 HD UVC WebCam                   | 1         | 2.04%   |
| IMC Networks EasyCamera                             | 1         | 2.04%   |
| Chicony VGA Webcam                                  | 1         | 2.04%   |
| Chicony thinkpad t430s camera                       | 1         | 2.04%   |
| Chicony Lenovo Integrated Camera (0.3MP)            | 1         | 2.04%   |
| Chicony Integrated IR Camera                        | 1         | 2.04%   |
| Chicony Integrated Camera (1280x720@30)             | 1         | 2.04%   |
| Chicony HP Wide Vision HD Camera                    | 1         | 2.04%   |
| Chicony HP Webcam [2 MP]                            | 1         | 2.04%   |
| Chicony HD WebCam (Acer)                            | 1         | 2.04%   |
| Chicony HD Webcam                                   | 1         | 2.04%   |
| Cheng Uei Precision Industry (Foxlink) Webcam       | 1         | 2.04%   |
| Cheng Uei Precision Industry (Foxlink) HP HD Webcam | 1         | 2.04%   |
| Bison Lenovo EasyCamera                             | 1         | 2.04%   |
| Apple FaceTime HD Camera (Built-in)                 | 1         | 2.04%   |
| Alcor Micro ASUS USB2.0 WebCam                      | 1         | 2.04%   |
| Alcor Micro Asus Integrated Webcam                  | 1         | 2.04%   |

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
| 1     | 34        | 46.58%  |
| 0     | 14        | 19.18%  |
| 2     | 13        | 17.81%  |
| 3     | 8         | 10.96%  |
| 4     | 4         | 5.48%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart_bsd/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Communication controller | 48        | 52.75%  |
| Card reader              | 12        | 13.19%  |
| Net/wireless             | 10        | 10.99%  |
| Bluetooth                | 9         | 9.89%   |
| Fingerprint reader       | 6         | 6.59%   |
| Firewire controller      | 3         | 3.3%    |
| Sound                    | 1         | 1.1%    |
| Net/ethernet             | 1         | 1.1%    |
| Graphics card            | 1         | 1.1%    |

