helloSystem 0.6.0 - Tested Hardware & Statistics (Notebooks)
------------------------------------------------------------

A project to collect tested hardware configurations for helloSystem 0.6.0.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe/blob/master/INSTALL.BSD.md) tool:

    hw-probe -all -upload

Please submit a probe of your configuration if it's not presented on the page or is rare.

Full-feature report is available here: https://bsd-hardware.info/?view=trends

Contents
--------

* [ Test Cases ](#test-cases)

* [ System ](#system)
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

| Vendor    | Model                       | Probe                                                     | Date         |
|-----------|-----------------------------|-----------------------------------------------------------|--------------|
| HP        | Pavilion dv6                | [dee0853f4b](https://bsd-hardware.info/?probe=dee0853f4b) | Mar 17, 2022 |
| Lenovo    | G580 20150                  | [478714c7c9](https://bsd-hardware.info/?probe=478714c7c9) | Feb 07, 2022 |
| Sony      | VPCEB1J1E                   | [04c5ee02da](https://bsd-hardware.info/?probe=04c5ee02da) | Feb 05, 2022 |
| Lenovo    | IdeaPad L340-15IWL 81LG     | [bb6cc55d53](https://bsd-hardware.info/?probe=bb6cc55d53) | Jan 23, 2022 |
| Toshiba   | Satellite L50-A             | [94b87158aa](https://bsd-hardware.info/?probe=94b87158aa) | Jan 21, 2022 |
| Apple     | MacBookPro5,5               | [53b106bbb6](https://bsd-hardware.info/?probe=53b106bbb6) | Jan 16, 2022 |
| Sony      | VPCYB45JB                   | [cd18905620](https://bsd-hardware.info/?probe=cd18905620) | Jan 09, 2022 |
| Lenovo    | G550 2958                   | [21407195e3](https://bsd-hardware.info/?probe=21407195e3) | Jan 07, 2022 |
| Acer      | Aspire E1-421               | [b2aea3de1b](https://bsd-hardware.info/?probe=b2aea3de1b) | Dec 21, 2021 |
| Lenovo    | G500 20236                  | [350def9eca](https://bsd-hardware.info/?probe=350def9eca) | Dec 19, 2021 |
| Lenovo    | ThinkPad T440p 20AW007QM... | [9efeb9ee24](https://bsd-hardware.info/?probe=9efeb9ee24) | Dec 16, 2021 |
| Dell      | Inspiron 3521               | [d8bcea438a](https://bsd-hardware.info/?probe=d8bcea438a) | Dec 15, 2021 |
| ASUSTek   | X502CA                      | [45f61ab19e](https://bsd-hardware.info/?probe=45f61ab19e) | Dec 14, 2021 |
| HP        | EliteBook 2560p             | [a064edad4b](https://bsd-hardware.info/?probe=a064edad4b) | Dec 10, 2021 |
| Acer      | Aspire 5749Z                | [60a25af38c](https://bsd-hardware.info/?probe=60a25af38c) | Dec 09, 2021 |
| Philco    | 10B                         | [a27148f35d](https://bsd-hardware.info/?probe=a27148f35d) | Dec 06, 2021 |
| Positivo  | C14CR01                     | [a33c158f9f](https://bsd-hardware.info/?probe=a33c158f9f) | Dec 05, 2021 |
| ASUSTek   | UX31A                       | [9febab6c01](https://bsd-hardware.info/?probe=9febab6c01) | Dec 05, 2021 |
| Lenovo    | ThinkPad 13 20GJCTO1WW      | [e4b923d500](https://bsd-hardware.info/?probe=e4b923d500) | Dec 02, 2021 |
| ASUSTek   | X540LA                      | [0680188ca4](https://bsd-hardware.info/?probe=0680188ca4) | Dec 01, 2021 |
| HP        | Laptop 15-db0xxx            | [812c7f3e36](https://bsd-hardware.info/?probe=812c7f3e36) | Nov 29, 2021 |
| HP        | EliteBook 2560p             | [41c04c8449](https://bsd-hardware.info/?probe=41c04c8449) | Nov 26, 2021 |
| HP        | EliteBook 2560p             | [8fe8caf37d](https://bsd-hardware.info/?probe=8fe8caf37d) | Nov 21, 2021 |
| Dell      | Inspiron 5566               | [7c6b2f2013](https://bsd-hardware.info/?probe=7c6b2f2013) | Nov 14, 2021 |
| Toshiba   | STI NA 1401                 | [bbbf661ee8](https://bsd-hardware.info/?probe=bbbf661ee8) | Nov 14, 2021 |
| Toshiba   | PORTEGE M780                | [2ac9bea1e6](https://bsd-hardware.info/?probe=2ac9bea1e6) | Nov 13, 2021 |
| Apple     | MacBookPro9,2               | [04cc56305c](https://bsd-hardware.info/?probe=04cc56305c) | Nov 11, 2021 |
| HP        | EliteBook 840 G5            | [a1ece36be8](https://bsd-hardware.info/?probe=a1ece36be8) | Nov 11, 2021 |
| Dell      | Studio 1747                 | [b0a51ac0af](https://bsd-hardware.info/?probe=b0a51ac0af) | Nov 11, 2021 |
| Dell      | Studio 1747                 | [7ab6b58d69](https://bsd-hardware.info/?probe=7ab6b58d69) | Nov 11, 2021 |
| Acer      | Aspire 5742G                | [0513869be8](https://bsd-hardware.info/?probe=0513869be8) | Nov 09, 2021 |
| Lenovo    | ThinkPad T450s 20BX001PU... | [748312bfbf](https://bsd-hardware.info/?probe=748312bfbf) | Nov 07, 2021 |
| ASUSTek   | K52Jc                       | [fc919c73e3](https://bsd-hardware.info/?probe=fc919c73e3) | Nov 07, 2021 |
| HP        | 14                          | [e0c8e95e52](https://bsd-hardware.info/?probe=e0c8e95e52) | Nov 07, 2021 |
| Lenovo    | ThinkPad W520 4276CTO       | [9082353a69](https://bsd-hardware.info/?probe=9082353a69) | Nov 06, 2021 |
| Lenovo    | ThinkPad T420 4180EE8       | [5303c12fe5](https://bsd-hardware.info/?probe=5303c12fe5) | Nov 05, 2021 |
| Lenovo    | IdeaPad Z360                | [796bd6482f](https://bsd-hardware.info/?probe=796bd6482f) | Nov 02, 2021 |
| Lenovo    | ThinkPad T430u 3352AA5      | [8619bcca35](https://bsd-hardware.info/?probe=8619bcca35) | Nov 01, 2021 |
| Apple     | MacBookAir5,1               | [b354b2bd4e](https://bsd-hardware.info/?probe=b354b2bd4e) | Oct 31, 2021 |
| HP        | Presario CQ43               | [b97d9ff563](https://bsd-hardware.info/?probe=b97d9ff563) | Oct 30, 2021 |
| Chuwi     | MiniBook                    | [4ce05f93a8](https://bsd-hardware.info/?probe=4ce05f93a8) | Oct 28, 2021 |
| Dell      | Precision M4600             | [2f848fd2c0](https://bsd-hardware.info/?probe=2f848fd2c0) | Oct 27, 2021 |
| Sony      | SVS1511AJB                  | [a366b5fab3](https://bsd-hardware.info/?probe=a366b5fab3) | Oct 24, 2021 |
| Sony      | SVS1511AJB                  | [2333f62192](https://bsd-hardware.info/?probe=2333f62192) | Oct 24, 2021 |
| Lenovo    | ThinkPad X1 Carbon 2nd 2... | [9996e06a3d](https://bsd-hardware.info/?probe=9996e06a3d) | Oct 22, 2021 |
| Dell      | Studio 1747                 | [ed704cde92](https://bsd-hardware.info/?probe=ed704cde92) | Oct 20, 2021 |
| Apple     | MacBookPro4,1               | [10861818b2](https://bsd-hardware.info/?probe=10861818b2) | Oct 20, 2021 |
| HP        | Unknown                     | [ad95186d17](https://bsd-hardware.info/?probe=ad95186d17) | Oct 19, 2021 |
| Dell      | Studio 1747                 | [ca939fbe2f](https://bsd-hardware.info/?probe=ca939fbe2f) | Oct 19, 2021 |
| HP        | 15                          | [e3f26d7245](https://bsd-hardware.info/?probe=e3f26d7245) | Oct 18, 2021 |
| Lenovo    | Yoga 3 Pro-1370 80HE        | [48169f1d3c](https://bsd-hardware.info/?probe=48169f1d3c) | Oct 16, 2021 |
| Lenovo    | ThinkPad L440 20ASS0FP00    | [d92e6e3c21](https://bsd-hardware.info/?probe=d92e6e3c21) | Oct 11, 2021 |
| Lenovo    | ThinkPad X1 Carbon Gen 9... | [abf8bb08a6](https://bsd-hardware.info/?probe=abf8bb08a6) | Oct 11, 2021 |
| ASUSTek   | U33Jc                       | [07f11b6604](https://bsd-hardware.info/?probe=07f11b6604) | Oct 10, 2021 |
| MSI       | MS-16F1                     | [72b9db306a](https://bsd-hardware.info/?probe=72b9db306a) | Oct 09, 2021 |
| Lenovo    | S20-30 Touch 20434          | [141a393d54](https://bsd-hardware.info/?probe=141a393d54) | Oct 08, 2021 |
| Lenovo    | ThinkPad X250 20CLS2A11K    | [e47f4113bf](https://bsd-hardware.info/?probe=e47f4113bf) | Oct 08, 2021 |
| Acer      | Aspire 5741                 | [fd4e40a8d9](https://bsd-hardware.info/?probe=fd4e40a8d9) | Oct 07, 2021 |
| Lenovo    | ThinkPad R500 2718W92       | [384f10861a](https://bsd-hardware.info/?probe=384f10861a) | Oct 05, 2021 |
| ASUSTek   | UX21A                       | [fe08d28d4c](https://bsd-hardware.info/?probe=fe08d28d4c) | Oct 05, 2021 |
| Itautec   | Infoway w7530               | [a376201681](https://bsd-hardware.info/?probe=a376201681) | Oct 05, 2021 |
| HP        | Pavilion Gaming Laptop 1... | [f02ef8c047](https://bsd-hardware.info/?probe=f02ef8c047) | Oct 04, 2021 |
| Dell      | Latitude E4300              | [fdb3de3036](https://bsd-hardware.info/?probe=fdb3de3036) | Oct 03, 2021 |
| Dell      | Inspiron 3521               | [748b6d14f4](https://bsd-hardware.info/?probe=748b6d14f4) | Oct 02, 2021 |
| Toshiba   | dynabook RX3 SM240E/3HD     | [2fe863dff4](https://bsd-hardware.info/?probe=2fe863dff4) | Oct 01, 2021 |
| Toshiba   | Satellite S55t-B            | [445fe665b8](https://bsd-hardware.info/?probe=445fe665b8) | Oct 01, 2021 |
| HP        | Pavilion dm4                | [bb5a564a50](https://bsd-hardware.info/?probe=bb5a564a50) | Sep 30, 2021 |
| Lenovo    | G500s 20245                 | [88cd1ca7bd](https://bsd-hardware.info/?probe=88cd1ca7bd) | Sep 18, 2021 |
| Kraftway  | KW10T                       | [4810842d82](https://bsd-hardware.info/?probe=4810842d82) | Sep 06, 2021 |
| Dell      | Latitude 3540               | [2583b22e8d](https://bsd-hardware.info/?probe=2583b22e8d) | Aug 29, 2021 |
| Dell      | Latitude 3540               | [de97e0b2fc](https://bsd-hardware.info/?probe=de97e0b2fc) | Aug 29, 2021 |
| Itautec   | Infoway w7530               | [d91ec24ce0](https://bsd-hardware.info/?probe=d91ec24ce0) | Aug 29, 2021 |
| Toshiba   | Satellite S55t-B            | [5aaacec4ad](https://bsd-hardware.info/?probe=5aaacec4ad) | Aug 23, 2021 |
| Toshiba   | Satellite S55t-B            | [d74035a8e7](https://bsd-hardware.info/?probe=d74035a8e7) | Aug 23, 2021 |
| Lenovo    | ThinkPad X230 23062S2       | [bceadf5c66](https://bsd-hardware.info/?probe=bceadf5c66) | Aug 05, 2021 |
| Lenovo    | ThinkPad SL 2746M3C         | [aa10433581](https://bsd-hardware.info/?probe=aa10433581) | Jul 28, 2021 |
| Lenovo    | ThinkPad X230 2325IG2       | [158ecc5e0b](https://bsd-hardware.info/?probe=158ecc5e0b) | Jul 14, 2021 |
| eMachines | eM350                       | [94579b896e](https://bsd-hardware.info/?probe=94579b896e) | Jul 04, 2021 |
| eMachines | eM350                       | [c268dd82de](https://bsd-hardware.info/?probe=c268dd82de) | Jul 04, 2021 |
| Lenovo    | B590 62743PG                | [2400297995](https://bsd-hardware.info/?probe=2400297995) | Jul 03, 2021 |
| Lenovo    | IdeaPad S145-15IWL 81MV     | [ceb18e38a3](https://bsd-hardware.info/?probe=ceb18e38a3) | Jun 28, 2021 |
| eMachines | eM350                       | [52198cfd80](https://bsd-hardware.info/?probe=52198cfd80) | Jun 22, 2021 |
| eMachines | eM350                       | [60b4338ace](https://bsd-hardware.info/?probe=60b4338ace) | Jun 22, 2021 |
| Dell      | Inspiron 3542               | [bb13e61de1](https://bsd-hardware.info/?probe=bb13e61de1) | Jun 21, 2021 |
| Lenovo    | ThinkPad Yoga 11e 20DAS0... | [0e448af5f5](https://bsd-hardware.info/?probe=0e448af5f5) | Jun 18, 2021 |
| Dell      | Latitude 7280               | [8fd335f46f](https://bsd-hardware.info/?probe=8fd335f46f) | Jun 18, 2021 |

System
------

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart_bsd/os_arch.svg)


| Name  | Notebooks | Percent |
|-------|-----------|---------|
| amd64 | 69        | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart_bsd/os_de.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| helloDesktop | 67        | 97.1%   |
| XFCE         | 1         | 1.45%   |
| KDE5         | 1         | 1.45%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart_bsd/os_display_server.svg)


| Name | Notebooks | Percent |
|------|-----------|---------|
| X11  | 69        | 100%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart_bsd/os_display_manager.svg)


| Name | Notebooks | Percent |
|------|-----------|---------|
| SLiM | 69        | 100%    |

OS Lang
-------

Language

![OS Lang](./images/pie_chart_bsd/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| en_US   | 66        | 95.65%  |
| ru_RU   | 1         | 1.45%   |
| de_DE   | 1         | 1.45%   |
| Unknown | 1         | 1.45%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart_bsd/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 52        | 74.29%  |
| BIOS | 18        | 25.71%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart_bsd/os_filesystem.svg)


| Type | Notebooks | Percent |
|------|-----------|---------|
| Zfs  | 69        | 100%    |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart_bsd/os_part_scheme.svg)


| Type | Notebooks | Percent |
|------|-----------|---------|
| GPT  | 69        | 100%    |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart_bsd/node_vendor.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| Lenovo           | 25        | 36.23%  |
| Hewlett-Packard  | 9         | 13.04%  |
| Dell             | 8         | 11.59%  |
| Toshiba          | 4         | 5.8%    |
| ASUSTek Computer | 4         | 5.8%    |
| Apple            | 4         | 5.8%    |
| Acer             | 4         | 5.8%    |
| Sony             | 3         | 4.35%   |
| Semp Toshiba     | 1         | 1.45%   |
| Positivo         | 1         | 1.45%   |
| Philco           | 1         | 1.45%   |
| MSI              | 1         | 1.45%   |
| Kraftway         | 1         | 1.45%   |
| Itautec          | 1         | 1.45%   |
| eMachines        | 1         | 1.45%   |
| Chuwi            | 1         | 1.45%   |

Model
-----

Motherboard model

![Model](./images/pie_chart_bsd/node_model.svg)


| Name                                       | Notebooks | Percent |
|--------------------------------------------|-----------|---------|
| Toshiba Satellite S55t-B                   | 1         | 1.45%   |
| Toshiba Satellite L50-A                    | 1         | 1.45%   |
| Toshiba PORTEGE M780                       | 1         | 1.45%   |
| Toshiba dynabook RX3 SM240E/3HD            | 1         | 1.45%   |
| Sony VPCYB45JB                             | 1         | 1.45%   |
| Sony VPCEB1J1E                             | 1         | 1.45%   |
| Sony SVS1511AJB                            | 1         | 1.45%   |
| Semp Toshiba STI NA 1401                   | 1         | 1.45%   |
| Positivo C14CR01                           | 1         | 1.45%   |
| Philco 10B                                 | 1         | 1.45%   |
| MSI MS-16F1                                | 1         | 1.45%   |
| Lenovo Yoga 3 Pro-1370 80HE                | 1         | 1.45%   |
| Lenovo ThinkPad Yoga 11e 20DAS0AE00        | 1         | 1.45%   |
| Lenovo ThinkPad X250 20CLS2A11K            | 1         | 1.45%   |
| Lenovo ThinkPad X230 2325IG2               | 1         | 1.45%   |
| Lenovo ThinkPad X230 23062S2               | 1         | 1.45%   |
| Lenovo ThinkPad X1 Carbon Gen 9 20XWA003CD | 1         | 1.45%   |
| Lenovo ThinkPad X1 Carbon 2nd 20A70066UK   | 1         | 1.45%   |
| Lenovo ThinkPad W520 4276CTO               | 1         | 1.45%   |
| Lenovo ThinkPad T450s 20BX001PUS           | 1         | 1.45%   |
| Lenovo ThinkPad T440p 20AW007QMS           | 1         | 1.45%   |
| Lenovo ThinkPad T430u 3352AA5              | 1         | 1.45%   |
| Lenovo ThinkPad T420 4180EE8               | 1         | 1.45%   |
| Lenovo ThinkPad SL 2746M3C                 | 1         | 1.45%   |
| Lenovo ThinkPad R500 2718W92               | 1         | 1.45%   |
| Lenovo ThinkPad L440 20ASS0FP00            | 1         | 1.45%   |
| Lenovo ThinkPad 13 20GJCTO1WW              | 1         | 1.45%   |
| Lenovo S20-30 Touch 20434                  | 1         | 1.45%   |
| Lenovo IdeaPad Z360                        | 1         | 1.45%   |
| Lenovo IdeaPad S145-15IWL 81MV             | 1         | 1.45%   |
| Lenovo IdeaPad L340-15IWL 81LG             | 1         | 1.45%   |
| Lenovo G580 20150                          | 1         | 1.45%   |
| Lenovo G550 2958                           | 1         | 1.45%   |
| Lenovo G500s 20245                         | 1         | 1.45%   |
| Lenovo G500 20236                          | 1         | 1.45%   |
| Lenovo B590 62743PG                        | 1         | 1.45%   |
| Kraftway KW10T                             | 1         | 1.45%   |
| Itautec Infoway w7530                      | 1         | 1.45%   |
| HP Presario CQ43                           | 1         | 1.45%   |
| HP Pavilion dv6                            | 1         | 1.45%   |
| HP Pavilion dm4                            | 1         | 1.45%   |
| HP Laptop 15-db0xxx                        | 1         | 1.45%   |
| HP EliteBook 840 G5                        | 1         | 1.45%   |
| HP EliteBook 2560p                         | 1         | 1.45%   |
| HP 15                                      | 1         | 1.45%   |
| HP 14                                      | 1         | 1.45%   |
| eMachines eM350                            | 1         | 1.45%   |
| Dell Studio 1747                           | 1         | 1.45%   |
| Dell Precision M4600                       | 1         | 1.45%   |
| Dell Latitude E4300                        | 1         | 1.45%   |
| Dell Latitude 7280                         | 1         | 1.45%   |
| Dell Latitude 3540                         | 1         | 1.45%   |
| Dell Inspiron 5566                         | 1         | 1.45%   |
| Dell Inspiron 3542                         | 1         | 1.45%   |
| Dell Inspiron 3521                         | 1         | 1.45%   |
| Chuwi MiniBook                             | 1         | 1.45%   |
| ASUS X502CA                                | 1         | 1.45%   |
| ASUS UX31A                                 | 1         | 1.45%   |
| ASUS UX21A                                 | 1         | 1.45%   |
| ASUS U33Jc                                 | 1         | 1.45%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart_bsd/node_model_family.svg)


| Name              | Notebooks | Percent |
|-------------------|-----------|---------|
| Lenovo ThinkPad   | 15        | 21.74%  |
| Acer Aspire       | 4         | 5.8%    |
| Lenovo IdeaPad    | 3         | 4.35%   |
| Dell Latitude     | 3         | 4.35%   |
| Dell Inspiron     | 3         | 4.35%   |
| Toshiba Satellite | 2         | 2.9%    |
| HP Pavilion       | 2         | 2.9%    |
| HP EliteBook      | 2         | 2.9%    |
| Toshiba PORTEGE   | 1         | 1.45%   |
| Toshiba dynabook  | 1         | 1.45%   |
| Sony VPCYB45JB    | 1         | 1.45%   |
| Sony VPCEB1J1E    | 1         | 1.45%   |
| Sony SVS1511AJB   | 1         | 1.45%   |
| Semp Toshiba STI  | 1         | 1.45%   |
| Positivo C14CR01  | 1         | 1.45%   |
| Philco 10B        | 1         | 1.45%   |
| MSI MS-16F1       | 1         | 1.45%   |
| Lenovo Yoga       | 1         | 1.45%   |
| Lenovo S20-30     | 1         | 1.45%   |
| Lenovo G580       | 1         | 1.45%   |
| Lenovo G550       | 1         | 1.45%   |
| Lenovo G500s      | 1         | 1.45%   |
| Lenovo G500       | 1         | 1.45%   |
| Lenovo B590       | 1         | 1.45%   |
| Kraftway KW10T    | 1         | 1.45%   |
| Itautec Infoway   | 1         | 1.45%   |
| HP Presario       | 1         | 1.45%   |
| HP Laptop         | 1         | 1.45%   |
| HP 15             | 1         | 1.45%   |
| HP 14             | 1         | 1.45%   |
| eMachines eM350   | 1         | 1.45%   |
| Dell Studio       | 1         | 1.45%   |
| Dell Precision    | 1         | 1.45%   |
| Chuwi MiniBook    | 1         | 1.45%   |
| ASUS X502CA       | 1         | 1.45%   |
| ASUS UX31A        | 1         | 1.45%   |
| ASUS UX21A        | 1         | 1.45%   |
| ASUS U33Jc        | 1         | 1.45%   |
| Apple MacBookPro9 | 1         | 1.45%   |
| Apple MacBookPro5 | 1         | 1.45%   |
| Apple MacBookPro4 | 1         | 1.45%   |
| Apple MacBookAir5 | 1         | 1.45%   |
| Unknown           | 1         | 1.45%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart_bsd/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2011 | 10        | 14.49%  |
| 2013 | 9         | 13.04%  |
| 2012 | 9         | 13.04%  |
| 2019 | 7         | 10.14%  |
| 2014 | 7         | 10.14%  |
| 2015 | 6         | 8.7%    |
| 2010 | 6         | 8.7%    |
| 2020 | 5         | 7.25%   |
| 2009 | 4         | 5.8%    |
| 2018 | 2         | 2.9%    |
| 2016 | 2         | 2.9%    |
| 2021 | 1         | 1.45%   |
| 2008 | 1         | 1.45%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart_bsd/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 69        | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart_bsd/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 69        | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart_bsd/node_ram_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 4.01-8.0   | 34        | 49.28%  |
| 8.01-16.0  | 27        | 39.13%  |
| 16.01-24.0 | 7         | 10.14%  |
| 2.01-3.0   | 1         | 1.45%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart_bsd/node_ram_used.svg)


| Used GB  | Notebooks | Percent |
|----------|-----------|---------|
| 0.01-0.5 | 52        | 75.36%  |
| 0.51-1.0 | 17        | 24.64%  |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart_bsd/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 58        | 84.06%  |
| 2      | 8         | 11.59%  |
| 0      | 2         | 2.9%    |
| 3      | 1         | 1.45%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart_bsd/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 36        | 52.17%  |
| Yes       | 33        | 47.83%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart_bsd/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 62        | 89.86%  |
| No        | 7         | 10.14%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart_bsd/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 66        | 95.65%  |
| No        | 3         | 4.35%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart_bsd/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 36        | 52.17%  |
| No        | 33        | 47.83%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart_bsd/node_location.svg)


| Country     | Notebooks | Percent |
|-------------|-----------|---------|
| Brazil      | 10        | 14.49%  |
| USA         | 6         | 8.7%    |
| Germany     | 5         | 7.25%   |
| Ukraine     | 4         | 5.8%    |
| Russia      | 4         | 5.8%    |
| UK          | 3         | 4.35%   |
| Spain       | 3         | 4.35%   |
| Mexico      | 3         | 4.35%   |
| Italy       | 3         | 4.35%   |
| China       | 3         | 4.35%   |
| South Korea | 2         | 2.9%    |
| Poland      | 2         | 2.9%    |
| New Zealand | 2         | 2.9%    |
| Netherlands | 2         | 2.9%    |
| Australia   | 2         | 2.9%    |
| Syria       | 1         | 1.45%   |
| Slovakia    | 1         | 1.45%   |
| Singapore   | 1         | 1.45%   |
| Peru        | 1         | 1.45%   |
| Lithuania   | 1         | 1.45%   |
| Libya       | 1         | 1.45%   |
| Japan       | 1         | 1.45%   |
| Greece      | 1         | 1.45%   |
| France      | 1         | 1.45%   |
| Czechia     | 1         | 1.45%   |
| Cuba        | 1         | 1.45%   |
| Colombia    | 1         | 1.45%   |
| Chile       | 1         | 1.45%   |
| Canada      | 1         | 1.45%   |
| Bulgaria    | 1         | 1.45%   |

City
----

Geographic location (city)

![City](./images/pie_chart_bsd/node_city.svg)


| City                       | Notebooks | Percent |
|----------------------------|-----------|---------|
| Maraba                     | 2         | 2.82%   |
| Harrisburg                 | 2         | 2.82%   |
| Guangzhou                  | 2         | 2.82%   |
| Barcelona                  | 2         | 2.82%   |
| Yeongdong-gun              | 1         | 1.41%   |
| Wroclaw                    | 1         | 1.41%   |
| Wellington                 | 1         | 1.41%   |
| Ufa                        | 1         | 1.41%   |
| Tyumen                     | 1         | 1.41%   |
| Tula de Allende            | 1         | 1.41%   |
| Tripoli                    | 1         | 1.41%   |
| The Hague                  | 1         | 1.41%   |
| Taito                      | 1         | 1.41%   |
| Stara Zagora               | 1         | 1.41%   |
| Stade                      | 1         | 1.41%   |
| St Petersburg              | 1         | 1.41%   |
| Singapore                  | 1         | 1.41%   |
| Seoul                      | 1         | 1.41%   |
| Seattle                    | 1         | 1.41%   |
| SÃ£o Paulo               | 1         | 1.41%   |
| Santiago                   | 1         | 1.41%   |
| Rome                       | 1         | 1.41%   |
| Rio de Janeiro             | 1         | 1.41%   |
| Redmond                    | 1         | 1.41%   |
| Pruszcz Gdanski            | 1         | 1.41%   |
| Pilsen                     | 1         | 1.41%   |
| Perth                      | 1         | 1.41%   |
| Oegstgeest                 | 1         | 1.41%   |
| Odessa                     | 1         | 1.41%   |
| Obninsk                    | 1         | 1.41%   |
| Nughedu San Nicolo         | 1         | 1.41%   |
| Nogent-sur-Marne           | 1         | 1.41%   |
| New Plymouth               | 1         | 1.41%   |
| Mykolayiv                  | 1         | 1.41%   |
| Monterrey                  | 1         | 1.41%   |
| Monte Belo                 | 1         | 1.41%   |
| Mission                    | 1         | 1.41%   |
| Memphis                    | 1         | 1.41%   |
| MedellÃ­n                | 1         | 1.41%   |
| LiptovskÃ½ MikulÃ¡Å¡ | 1         | 1.41%   |
| Lima                       | 1         | 1.41%   |
| Leatherhead                | 1         | 1.41%   |
| La Paz                     | 1         | 1.41%   |
| Kyiv                       | 1         | 1.41%   |
| Kaunas                     | 1         | 1.41%   |
| JagÃ¼ey Grande           | 1         | 1.41%   |
| Ipojuca                    | 1         | 1.41%   |
| Ibiuna                     | 1         | 1.41%   |
| Havana                     | 1         | 1.41%   |
| Frankfurt am Main          | 1         | 1.41%   |
| Finchley                   | 1         | 1.41%   |
| Farneto                    | 1         | 1.41%   |
| Elche                      | 1         | 1.41%   |
| Dulles                     | 1         | 1.41%   |
| Diadema                    | 1         | 1.41%   |
| Detmold                    | 1         | 1.41%   |
| Damascus                   | 1         | 1.41%   |
| Curitiba                   | 1         | 1.41%   |
| Chengdu                    | 1         | 1.41%   |
| ChapecÃ³                 | 1         | 1.41%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart_bsd/drive_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 15        | 16     | 19.48%  |
| Samsung Electronics | 11        | 12     | 14.29%  |
| Toshiba             | 9         | 11     | 11.69%  |
| WDC                 | 8         | 8      | 10.39%  |
| Kingston            | 5         | 6      | 6.49%   |
| SanDisk             | 3         | 3      | 3.9%    |
| Hitachi             | 3         | 3      | 3.9%    |
| Crucial             | 3         | 3      | 3.9%    |
| HGST                | 2         | 2      | 2.6%    |
| Corsair             | 2         | 2      | 2.6%    |
| Transcend           | 1         | 1      | 1.3%    |
| SPCC                | 1         | 1      | 1.3%    |
| PLEXTOR             | 1         | 1      | 1.3%    |
| Patriot             | 1         | 1      | 1.3%    |
| Micron Technology   | 1         | 1      | 1.3%    |
| LITEON              | 1         | 1      | 1.3%    |
| Lexar               | 1         | 1      | 1.3%    |
| Leven               | 1         | 1      | 1.3%    |
| KingSpec            | 1         | 1      | 1.3%    |
| Intel               | 1         | 1      | 1.3%    |
| Gigabyte Technology | 1         | 1      | 1.3%    |
| FORESEE             | 1         | 1      | 1.3%    |
| Apple               | 1         | 1      | 1.3%    |
| Apacer              | 1         | 1      | 1.3%    |
| AMD                 | 1         | 1      | 1.3%    |
| A-DATA Technology   | 1         | 1      | 1.3%    |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart_bsd/drive_model.svg)


| Model                                | Notebooks | Percent |
|--------------------------------------|-----------|---------|
| Toshiba MQ01ABD100 1TB               | 3         | 3.85%   |
| Seagate ST9500325AS 500GB            | 3         | 3.85%   |
| Toshiba MQ01ABF050 500GB             | 2         | 2.56%   |
| Seagate ST9500420AS 500GB            | 2         | 2.56%   |
| Seagate ST1000LM024 HN-M101MBB 1TB   | 2         | 2.56%   |
| SanDisk SD5SE2256G1002E 256GB        | 2         | 2.56%   |
| Samsung SSD 860 EVO 1TB              | 2         | 2.56%   |
| Samsung MZ7TE128HMGR-000L1 128GB     | 2         | 2.56%   |
| Kingston SA400S37960G 960GB          | 2         | 2.56%   |
| WDC WDS240G2G0A-00JH30 240GB         | 1         | 1.28%   |
| WDC WD5000BPKT-00PK4T0 500GB         | 1         | 1.28%   |
| WDC WD5000BEKT-60KA9T0 500GB         | 1         | 1.28%   |
| WDC WD3200BEVT-80A0RT0 320GB         | 1         | 1.28%   |
| WDC WD2500BEVS-08VAT2 250GB          | 1         | 1.28%   |
| WDC WD1600BPVT-11JJ5T0 160GB         | 1         | 1.28%   |
| WDC WD1200BEVS-07RST0 120GB          | 1         | 1.28%   |
| WDC WD10SPZX-24Z10 1TB               | 1         | 1.28%   |
| Transcend TS120GMTS420S 120GB        | 1         | 1.28%   |
| Toshiba MQ01ABD050 247GB             | 1         | 1.28%   |
| Toshiba MK5061GSYN 500GB             | 1         | 1.28%   |
| Toshiba MK3261GSYN 320GB             | 1         | 1.28%   |
| Toshiba MK1252GSX 120GB              | 1         | 1.28%   |
| SPCC Solid State Disk 1TB            | 1         | 1.28%   |
| Seagate ST9250315ASG 250GB           | 1         | 1.28%   |
| Seagate ST9160412ASG 160GB           | 1         | 1.28%   |
| Seagate ST500LT012-1DG142 500GB      | 1         | 1.28%   |
| Seagate ST500LM021-1KJ152 500GB      | 1         | 1.28%   |
| Seagate ST500LM012 HN-M500MBB 500GB  | 1         | 1.28%   |
| Seagate ST320LT012-9WS14C 320GB      | 1         | 1.28%   |
| Seagate ST2000LM007-1R8174 2TB       | 1         | 1.28%   |
| Seagate ST1000LM048-2E7172 1TB       | 1         | 1.28%   |
| SanDisk SSD U110 16GB                | 1         | 1.28%   |
| Samsung SSD 850 EVO 500GB            | 1         | 1.28%   |
| Samsung SSD 840 EVO 250GB            | 1         | 1.28%   |
| Samsung MZVL21T0HCLR-00BL7 1TB       | 1         | 1.28%   |
| Samsung MZNTE256HMHP-000L2 256GB     | 1         | 1.28%   |
| Samsung MZNLN512HMJP-000L7 512GB     | 1         | 1.28%   |
| Samsung MZNLN512HMJP-000H1 512GB     | 1         | 1.28%   |
| Samsung HM320II 320GB                | 1         | 1.28%   |
| PLEXTOR PX-128M5Pro 128GB            | 1         | 1.28%   |
| Patriot Burst 120GB                  | 1         | 1.28%   |
| Micron MTFDDAV256TBN-1AR15ABHA 256GB | 1         | 1.28%   |
| LITEON IT LCS-128L9S-HP 128GB        | 1         | 1.28%   |
| Lexar 256GB SSD                      | 1         | 1.28%   |
| Leven JAJS300M480C 480GB             | 1         | 1.28%   |
| Kingston SVP200S37A60G 64GB          | 1         | 1.28%   |
| Kingston SUV300S37A120G 120GB        | 1         | 1.28%   |
| Kingston SMS200S360G 64GB            | 1         | 1.28%   |
| Kingston SKC300S37A240G 240GB        | 1         | 1.28%   |
| KingSpec MT-256 256GB                | 1         | 1.28%   |
| Intel SSDSCKGF180A4L 180GB           | 1         | 1.28%   |
| Hitachi HTS545025B9A300 250GB        | 1         | 1.28%   |
| Hitachi HTS541616J9SA00 160GB        | 1         | 1.28%   |
| Hitachi HTS541080G9SA00 80GB         | 1         | 1.28%   |
| HGST HTS545032A7E680 320GB           | 1         | 1.28%   |
| HGST HTS541010A9E680 1TB             | 1         | 1.28%   |
| Gigabyte GP-GSTFS31256GTND 256GB     | 1         | 1.28%   |
| FORESEE 128GB SSD                    | 1         | 1.28%   |
| Crucial CT500MX500SSD1 500GB         | 1         | 1.28%   |
| Crucial CT480BX200SSD1 480GB         | 1         | 1.28%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart_bsd/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 15        | 16     | 40.54%  |
| Toshiba             | 9         | 11     | 24.32%  |
| WDC                 | 7         | 7      | 18.92%  |
| Hitachi             | 3         | 3      | 8.11%   |
| HGST                | 2         | 2      | 5.41%   |
| Samsung Electronics | 1         | 1      | 2.7%    |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart_bsd/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 9         | 10     | 23.68%  |
| Kingston            | 5         | 6      | 13.16%  |
| SanDisk             | 3         | 3      | 7.89%   |
| Crucial             | 3         | 3      | 7.89%   |
| Corsair             | 2         | 2      | 5.26%   |
| WDC                 | 1         | 1      | 2.63%   |
| Transcend           | 1         | 1      | 2.63%   |
| SPCC                | 1         | 1      | 2.63%   |
| PLEXTOR             | 1         | 1      | 2.63%   |
| Patriot             | 1         | 1      | 2.63%   |
| Micron Technology   | 1         | 1      | 2.63%   |
| LITEON              | 1         | 1      | 2.63%   |
| Lexar               | 1         | 1      | 2.63%   |
| Leven               | 1         | 1      | 2.63%   |
| KingSpec            | 1         | 1      | 2.63%   |
| Intel               | 1         | 1      | 2.63%   |
| Gigabyte Technology | 1         | 1      | 2.63%   |
| FORESEE             | 1         | 1      | 2.63%   |
| Apple               | 1         | 1      | 2.63%   |
| Apacer              | 1         | 1      | 2.63%   |
| AMD                 | 1         | 1      | 2.63%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart_bsd/drive_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SSD  | 35        | 40     | 48.61%  |
| HDD  | 35        | 40     | 48.61%  |
| NVMe | 2         | 2      | 2.78%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart_bsd/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 66        | 80     | 97.06%  |
| NVMe | 2         | 2      | 2.94%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart_bsd/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 53        | 64     | 76.81%  |
| 0.51-1.0   | 14        | 14     | 20.29%  |
| 1.01-2.0   | 2         | 2      | 2.9%    |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart_bsd/drive_space_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 1-20       | 37        | 50.68%  |
| 101-250    | 18        | 24.66%  |
| 251-500    | 11        | 15.07%  |
| 501-1000   | 6         | 8.22%   |
| 51-100     | 1         | 1.37%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart_bsd/drive_space_used.svg)


| Used GB | Notebooks | Percent |
|---------|-----------|---------|
| 1-20    | 69        | 100%    |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart_bsd/drive_malfunc.svg)


| Model                                           | Notebooks | Drives | Percent |
|-------------------------------------------------|-----------|--------|---------|
| Seagate ST9500420AS 500GB                       | 2         | 2      | 10.53%  |
| WDC WD3200BEVT-80A0RT0 320GB                    | 1         | 1      | 5.26%   |
| Toshiba MQ01ABF050 500GB                        | 1         | 2      | 5.26%   |
| Toshiba MQ01ABD050 247GB                        | 1         | 1      | 5.26%   |
| Toshiba MK5061GSYN 500GB                        | 1         | 1      | 5.26%   |
| Toshiba MK3261GSYN 320GB                        | 1         | 2      | 5.26%   |
| Toshiba MK1252GSX 120GB                         | 1         | 1      | 5.26%   |
| Seagate ST9500325AS 500GB                       | 1         | 1      | 5.26%   |
| Seagate ST500LM021-1KJ152 500GB                 | 1         | 1      | 5.26%   |
| Seagate ST320LT012-9WS14C 320GB                 | 1         | 1      | 5.26%   |
| Seagate ST1000LM048-2E7172 1TB                  | 1         | 1      | 5.26%   |
| Seagate ST1000LM024 HN-M101MBB 1TB              | 1         | 1      | 5.26%   |
| SanDisk SD5SE2256G1002E 256GB                   | 1         | 1      | 5.26%   |
| Micron Technology MTFDDAV256TBN-1AR15ABHA 256GB | 1         | 1      | 5.26%   |
| Hitachi HTS541616J9SA00 160GB                   | 1         | 1      | 5.26%   |
| Hitachi HTS541080G9SA00 80GB                    | 1         | 1      | 5.26%   |
| HGST HTS541010A9E680 1TB                        | 1         | 1      | 5.26%   |
| Corsair Force GT 120GB                          | 1         | 1      | 5.26%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart_bsd/drive_malfunc_vendor.svg)


| Vendor            | Notebooks | Drives | Percent |
|-------------------|-----------|--------|---------|
| Seagate           | 7         | 7      | 36.84%  |
| Toshiba           | 5         | 7      | 26.32%  |
| Hitachi           | 2         | 2      | 10.53%  |
| WDC               | 1         | 1      | 5.26%   |
| SanDisk           | 1         | 1      | 5.26%   |
| Micron Technology | 1         | 1      | 5.26%   |
| HGST              | 1         | 1      | 5.26%   |
| Corsair           | 1         | 1      | 5.26%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart_bsd/drive_malfunc_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 7         | 7      | 43.75%  |
| Toshiba | 5         | 7      | 31.25%  |
| Hitachi | 2         | 2      | 12.5%   |
| WDC     | 1         | 1      | 6.25%   |
| HGST    | 1         | 1      | 6.25%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart_bsd/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 16        | 18     | 84.21%  |
| SSD  | 3         | 3      | 15.79%  |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart_bsd/drive_failed.svg)


| Model                         | Notebooks | Drives | Percent |
|-------------------------------|-----------|--------|---------|
| Hitachi HTS545025B9A300 250GB | 1         | 1      | 100%    |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart_bsd/drive_failed_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Hitachi | 1         | 1      | 100%    |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart_bsd/drive_status.svg)


| Status  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Works   | 50        | 60     | 71.43%  |
| Malfunc | 19        | 21     | 27.14%  |
| Failed  | 1         | 1      | 1.43%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart_bsd/storage_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 63        | 90%     |
| AMD                   | 4         | 5.71%   |
| Samsung Electronics   | 1         | 1.43%   |
| Realtek Semiconductor | 1         | 1.43%   |
| Nvidia                | 1         | 1.43%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart_bsd/storage_model.svg)


| Model                                                                                  | Notebooks | Percent |
|----------------------------------------------------------------------------------------|-----------|---------|
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                       | 17        | 22.67%  |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                         | 7         | 9.33%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller           | 6         | 8%      |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                     | 5         | 6.67%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                                     | 4         | 5.33%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                           | 4         | 5.33%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                                 | 3         | 4%      |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]                  | 3         | 4%      |
| Intel 82801 Mobile SATA Controller [RAID mode]                                         | 3         | 4%      |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                                     | 2         | 2.67%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                      | 2         | 2.67%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]         | 2         | 2.67%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                         | 2         | 2.67%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                      | 2         | 2.67%   |
| AMD FCH SATA Controller [AHCI mode]                                                    | 2         | 2.67%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                         | 1         | 1.33%   |
| Nvidia MCP79 AHCI Controller                                                           | 1         | 1.33%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                          | 1         | 1.33%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                       | 1         | 1.33%   |
| Intel 8 Series/C220 Series Chipset Family 2-port SATA Controller 2 [IDE mode]          | 1         | 1.33%   |
| Intel 8 Series Chipset Family 4-port SATA Controller 1 [IDE mode] - Mobile             | 1         | 1.33%   |
| Intel 6 Series/C200 Series Chipset Family Mobile SATA Controller (IDE mode, ports 4-5) | 1         | 1.33%   |
| Intel 6 Series/C200 Series Chipset Family Mobile SATA Controller (IDE mode, ports 0-3) | 1         | 1.33%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA IDE Controller                          | 1         | 1.33%   |
| Intel 5 Series/3400 Series Chipset 2 port SATA IDE Controller                          | 1         | 1.33%   |
| Unknown                                                                                | 1         | 1.33%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart_bsd/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 63        | 87.5%   |
| IDE  | 4         | 5.56%   |
| RAID | 3         | 4.17%   |
| NVMe | 2         | 2.78%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart_bsd/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 65        | 94.2%   |
| AMD    | 4         | 5.8%    |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart_bsd/cpu_model.svg)


| Model                                        | Notebooks | Percent |
|----------------------------------------------|-----------|---------|
| Intel Core i5-3317U CPU @ 1.70GHz            | 3         | 4.35%   |
| Intel CPU Version                            | 2         | 2.9%    |
| Intel Core i7-3520M CPU @ 2.90GHz            | 2         | 2.9%    |
| Intel Core i5-5200U CPU @ 2.20GHz            | 2         | 2.9%    |
| Intel Core i5-4210U CPU @ 1.70GHz            | 2         | 2.9%    |
| Intel Core i5-3230M CPU @ 2.60GHz            | 2         | 2.9%    |
| Intel Core i5-2520M CPU @ 2.50GHz            | 2         | 2.9%    |
| Intel Core i3-3110M CPU @ 2.40GHz            | 2         | 2.9%    |
| Intel Core i3 CPU M 370 @ 2.40GHz            | 2         | 2.9%    |
| Intel Core i3 CPU M 330 @ 2.13GHz            | 2         | 2.9%    |
| Intel Processor 5Y70 CPU @ 1.10GHz           | 1         | 1.45%   |
| Intel Pentium CPU N3530 @ 2.16GHz            | 1         | 1.45%   |
| Intel Pentium CPU B960 @ 2.20GHz             | 1         | 1.45%   |
| Intel Pentium CPU 5405U @ 2.30GHz            | 1         | 1.45%   |
| Intel Genuine CPU                            | 1         | 1.45%   |
| Intel Core m3-8100Y CPU @ 1.10GHz            | 1         | 1.45%   |
| Intel Core i7-7500U CPU @ 2.70GHz            | 1         | 1.45%   |
| Intel Core i7-4712MQ CPU @ 2.30GHz           | 1         | 1.45%   |
| Intel Core i7-4700MQ CPU @ 2.40GHz           | 1         | 1.45%   |
| Intel Core i7-3632QM CPU @ 2.20GHz           | 1         | 1.45%   |
| Intel Core i7-3517U CPU @ 1.90GHz            | 1         | 1.45%   |
| Intel Core i7-2860QM CPU @ 2.50GHz           | 1         | 1.45%   |
| Intel Core i7-2640M CPU @ 2.80GH             | 1         | 1.45%   |
| Intel Core i5-8350U CPU @ 1.70GHz            | 1         | 1.45%   |
| Intel Core i5-7300U CPU @ 2.60GHz            | 1         | 1.45%   |
| Intel Core i5-5300U CPU @ 2.30GHz            | 1         | 1.45%   |
| Intel Core i5-4300U CPU @ 1.90GHz            | 1         | 1.45%   |
| Intel Core i5-4300M CPU @ 2.60GHz            | 1         | 1.45%   |
| Intel Core i5-3320M CPU @ 2.60GHz            | 1         | 1.45%   |
| Intel Core i5-3210M CPU @ 2.50GHz            | 1         | 1.45%   |
| Intel Core i5-2450M CPU @ 2.50GHz            | 1         | 1.45%   |
| Intel Core i5-2410M CPU @ 2.30GHz            | 1         | 1.45%   |
| Intel Core i5 CPU M 520 @ 2.40GHz            | 1         | 1.45%   |
| Intel Core i5 CPU M 460 @ 2.53GHz            | 1         | 1.45%   |
| Intel Core i5 CPU M 450 @ 2.40GHz            | 1         | 1.45%   |
| Intel Core i3-8145U CPU @ 2.10GHz            | 1         | 1.45%   |
| Intel Core i3-6100U CPU @ 2.30GHz            | 1         | 1.45%   |
| Intel Core i3-4005U CPU @ 1.70GHz            | 1         | 1.45%   |
| Intel Core i3-3227U CPU @ 1.90GHz            | 1         | 1.45%   |
| Intel Core i3 CPU M 370 @ 2.40GH             | 1         | 1.45%   |
| Intel Core 2 Duo CPU T8300 @ 2.40GHz         | 1         | 1.45%   |
| Intel Core 2 Duo CPU T5870 @ 2.00GHz         | 1         | 1.45%   |
| Intel Core 2 Duo CPU P8700 @ 2.53GHz         | 1         | 1.45%   |
| Intel Core 2 Duo CPU P8600 @ 2.40GHz         | 1         | 1.45%   |
| Intel Core 2 Duo                             | 1         | 1.45%   |
| Intel Celeron CPU N2930 @ 1.83GHz            | 1         | 1.45%   |
| Intel Celeron CPU B815 @ 1.60GHz             | 1         | 1.45%   |
| Intel Celeron CPU 847 @ 1.10GHz              | 1         | 1.45%   |
| Intel Celeron CPU 1007U @ 1.50GHz            | 1         | 1.45%   |
| Intel Celeron CPU 1005M @ 1.90GHz            | 1         | 1.45%   |
| Intel Atom CPU N450 @ 1.66GHz                | 1         | 1.45%   |
| Intel Atom CPU E3825 @ 1.33GHz               | 1         | 1.45%   |
| Intel Atom CPU D425 @ 1.80GHz                | 1         | 1.45%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz      | 1         | 1.45%   |
| AMD E-450 APU with Radeon HD Graphics        | 1         | 1.45%   |
| AMD E-300 APU with Radeon HD Graphics        | 1         | 1.45%   |
| AMD C-60 APU with Radeon HD Graphics         | 1         | 1.45%   |
| AMD A6-9225 RADEON R4, 5 COMPUTE CORES 2C+3G | 1         | 1.45%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart_bsd/cpu_family.svg)


| Model            | Notebooks | Percent |
|------------------|-----------|---------|
| Intel Core i5    | 23        | 33.33%  |
| Intel Core i3    | 11        | 15.94%  |
| Intel Core i7    | 9         | 13.04%  |
| Intel Core 2 Duo | 5         | 7.25%   |
| Intel Celeron    | 5         | 7.25%   |
| Other            | 4         | 5.8%    |
| Intel Pentium    | 3         | 4.35%   |
| Intel Atom       | 3         | 4.35%   |
| AMD E            | 2         | 2.9%    |
| Intel Genuine    | 1         | 1.45%   |
| Intel Core m3    | 1         | 1.45%   |
| AMD C-60         | 1         | 1.45%   |
| AMD A6           | 1         | 1.45%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart_bsd/cpu_cores.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 54        | 78.26%  |
| 4       | 9         | 13.04%  |
| Unknown | 4         | 5.8%    |
| 1       | 2         | 2.9%    |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart_bsd/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 67        | 97.1%   |
| 2      | 2         | 2.9%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart_bsd/cpu_threads.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 51        | 73.91%  |
| 1       | 14        | 20.29%  |
| Unknown | 4         | 5.8%    |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart_bsd/cpu_microarch.svg)


| Name        | Notebooks | Percent |
|-------------|-----------|---------|
| IvyBridge   | 16        | 23.19%  |
| Westmere    | 9         | 13.04%  |
| SandyBridge | 9         | 13.04%  |
| Haswell     | 7         | 10.14%  |
| KabyLake    | 6         | 8.7%    |
| Penryn      | 5         | 7.25%   |
| Broadwell   | 4         | 5.8%    |
| Silvermont  | 3         | 4.35%   |
| Bobcat      | 3         | 4.35%   |
| Bonnell     | 2         | 2.9%    |
| TigerLake   | 1         | 1.45%   |
| Skylake     | 1         | 1.45%   |
| Nehalem     | 1         | 1.45%   |
| Excavator   | 1         | 1.45%   |
| Core        | 1         | 1.45%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart_bsd/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 57        | 75%     |
| Nvidia | 13        | 17.11%  |
| AMD    | 6         | 7.89%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart_bsd/gpu_model.svg)


| Model                                                                     | Notebooks | Percent |
|---------------------------------------------------------------------------|-----------|---------|
| Intel 3rd Gen Core processor Graphics Controller                          | 16        | 21.05%  |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller | 8         | 10.53%  |
| Intel Core Processor Integrated Graphics Controller                       | 6         | 7.89%   |
| Intel Haswell-ULT Integrated Graphics Controller                          | 4         | 5.26%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]      | 3         | 3.95%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller              | 3         | 3.95%   |
| Intel HD Graphics 5500                                                    | 3         | 3.95%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display              | 3         | 3.95%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller               | 3         | 3.95%   |
| Intel HD Graphics 620                                                     | 2         | 2.63%   |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller   | 2         | 2.63%   |
| Nvidia GT218M [GeForce 310M]                                              | 1         | 1.32%   |
| Nvidia GK208M [GeForce GT 740M]                                           | 1         | 1.32%   |
| Nvidia GK107M [GeForce GT 640M LE]                                        | 1         | 1.32%   |
| Nvidia GF108M [GeForce GT 420M]                                           | 1         | 1.32%   |
| Nvidia GF108GLM [Quadro 1000M]                                            | 1         | 1.32%   |
| Nvidia GF106M [GeForce GTX 460M]                                          | 1         | 1.32%   |
| Nvidia GF106GLM [Quadro 2000M]                                            | 1         | 1.32%   |
| Nvidia G98M [GeForce G 105M]                                              | 1         | 1.32%   |
| Nvidia G84M [GeForce 8600M GT]                                            | 1         | 1.32%   |
| Nvidia C79 [GeForce 9400M]                                                | 1         | 1.32%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                | 1         | 1.32%   |
| Intel UHD Graphics 620                                                    | 1         | 1.32%   |
| Intel UHD Graphics 615                                                    | 1         | 1.32%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                 | 1         | 1.32%   |
| Intel Skylake GT2 [HD Graphics 520]                                       | 1         | 1.32%   |
| Intel HD Graphics 5300                                                    | 1         | 1.32%   |
| Intel Coffee Lake UHD 610 Graphics Controller                             | 1         | 1.32%   |
| AMD Wrestler [Radeon HD 6320]                                             | 1         | 1.32%   |
| AMD Wrestler [Radeon HD 6310]                                             | 1         | 1.32%   |
| AMD Wrestler [Radeon HD 6290]                                             | 1         | 1.32%   |
| AMD Venus PRO [Radeon HD 8850M / R9 M265X]                                | 1         | 1.32%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                  | 1         | 1.32%   |
| AMD RV730/M96 [Mobility Radeon HD 4650/5165]                              | 1         | 1.32%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart_bsd/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 45        | 65.22%  |
| 1 x Nvidia     | 7         | 10.14%  |
| Intel + Nvidia | 6         | 8.7%    |
| 2 x Intel      | 5         | 7.25%   |
| 1 x AMD        | 5         | 7.25%   |
| Intel + AMD    | 1         | 1.45%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart_bsd/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 60        | 86.96%  |
| Unknown     | 8         | 11.59%  |
| Proprietary | 1         | 1.45%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart_bsd/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 64        | 92.75%  |
| 0.01-0.5   | 4         | 5.8%    |
| 0.51-1.0   | 1         | 1.45%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart_bsd/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| LG Display              | 14        | 23.73%  |
| AU Optronics            | 10        | 16.95%  |
| Samsung Electronics     | 7         | 11.86%  |
| Chimei Innolux          | 7         | 11.86%  |
| BOE                     | 7         | 11.86%  |
| Lenovo                  | 3         | 5.08%   |
| InfoVision              | 3         | 5.08%   |
| Chi Mei Optoelectronics | 3         | 5.08%   |
| Apple                   | 2         | 3.39%   |
| KTC                     | 1         | 1.69%   |
| Hewlett-Packard         | 1         | 1.69%   |
| Fujitsu Siemens         | 1         | 1.69%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart_bsd/mon_model.svg)


| Model                                                                    | Notebooks | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| LG Display LCD Monitor LGD0385 1366x768 310x170mm 13.9-inch              | 2         | 3.39%   |
| LG Display LCD Monitor LGD02D8 1366x768 280x160mm 12.7-inch              | 2         | 3.39%   |
| InfoVision LCD Monitor IVO03F4 1024x600 220x130mm 10.1-inch              | 2         | 3.39%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A7 1366x768 350x190mm 15.7-inch | 2         | 3.39%   |
| Samsung Electronics LCD Monitor SEC5742 1366x768 310x170mm 13.9-inch     | 1         | 1.69%   |
| Samsung Electronics LCD Monitor SEC414C 1366x768 310x170mm 13.9-inch     | 1         | 1.69%   |
| Samsung Electronics LCD Monitor SEC3942 1366x768 310x170mm 13.9-inch     | 1         | 1.69%   |
| Samsung Electronics LCD Monitor SEC334A 1366x768 340x190mm 15.3-inch     | 1         | 1.69%   |
| Samsung Electronics LCD Monitor SEC3143 1366x768 310x180mm 14.1-inch     | 1         | 1.69%   |
| Samsung Electronics LCD Monitor SDC4445 1366x768 340x190mm 15.3-inch     | 1         | 1.69%   |
| Samsung Electronics LCD Monitor SDC434A 3200x1800 290x170mm 13.2-inch    | 1         | 1.69%   |
| LG Display LCD Monitor LGD11F9 1280x800 290x180mm 13.4-inch              | 1         | 1.69%   |
| LG Display LCD Monitor LGD048C 1920x1080 290x170mm 13.2-inch             | 1         | 1.69%   |
| LG Display LCD Monitor LGD0470 1920x1080 350x190mm 15.7-inch             | 1         | 1.69%   |
| LG Display LCD Monitor LGD0419 2560x1440 310x170mm 13.9-inch             | 1         | 1.69%   |
| LG Display LCD Monitor LGD03ED 1366x768 280x160mm 12.7-inch              | 1         | 1.69%   |
| LG Display LCD Monitor LGD03AB 1366x768 340x190mm 15.3-inch              | 1         | 1.69%   |
| LG Display LCD Monitor LGD0323 1920x1080 350x190mm 15.7-inch             | 1         | 1.69%   |
| LG Display LCD Monitor LGD02DC 1366x768 340x190mm 15.3-inch              | 1         | 1.69%   |
| LG Display LCD Monitor LGD0230 1366x768 340x190mm 15.3-inch              | 1         | 1.69%   |
| LG Display LCD Monitor LGD021D 1600x900 380x210mm 17.1-inch              | 1         | 1.69%   |
| Lenovo LEN X24A LEN60CF 1920x1080 530x300mm 24.0-inch                    | 1         | 1.69%   |
| Lenovo LCD Monitor LEN40B2 1920x1080 340x190mm 15.3-inch                 | 1         | 1.69%   |
| Lenovo LCD Monitor LEN4050 1280x800 330x210mm 15.4-inch                  | 1         | 1.69%   |
| KTC M-9005L11-D KTC1990 1280x1024 340x270mm 17.1-inch                    | 1         | 1.69%   |
| InfoVision LCD Monitor IVO057F 1920x1080 310x170mm 13.9-inch             | 1         | 1.69%   |
| Hewlett-Packard 2009 HWP2827 1600x900 440x250mm 19.9-inch                | 1         | 1.69%   |
| Fujitsu Siemens E19-5 FUS07CD 1280x1024 380x300mm 19.1-inch              | 1         | 1.69%   |
| Chimei Innolux LCD Monitor CMN15C6 1366x768 340x190mm 15.3-inch          | 1         | 1.69%   |
| Chimei Innolux LCD Monitor CMN15AB 1366x768 340x190mm 15.3-inch          | 1         | 1.69%   |
| Chimei Innolux LCD Monitor CMN1492 1366x768 310x170mm 13.9-inch          | 1         | 1.69%   |
| Chimei Innolux LCD Monitor CMN1482 1600x900 310x170mm 13.9-inch          | 1         | 1.69%   |
| Chimei Innolux LCD Monitor CMN1348 1920x1080 280x160mm 12.7-inch         | 1         | 1.69%   |
| Chimei Innolux LCD Monitor CMN1124 1920x1080 260x140mm 11.6-inch         | 1         | 1.69%   |
| Chimei Innolux LCD Monitor CMN1119 1366x768 260x140mm 11.6-inch          | 1         | 1.69%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A2 1366x768 350x190mm 15.7-inch | 1         | 1.69%   |
| BOE LCD Monitor BOE0757 1366x768 340x190mm 15.3-inch                     | 1         | 1.69%   |
| BOE LCD Monitor BOE06D3 1366x768 340x190mm 15.3-inch                     | 1         | 1.69%   |
| BOE LCD Monitor BOE06C8 1366x768 280x160mm 12.7-inch                     | 1         | 1.69%   |
| BOE LCD Monitor BOE0685 1600x900 380x210mm 17.1-inch                     | 1         | 1.69%   |
| BOE LCD Monitor BOE0615 1366x768 340x190mm 15.3-inch                     | 1         | 1.69%   |
| BOE LCD Monitor BOE05E9 1366x768 250x140mm 11.3-inch                     | 1         | 1.69%   |
| BOE LCD Monitor BOE05B1 1366x768 310x170mm 13.9-inch                     | 1         | 1.69%   |
| AU Optronics LCD Monitor AUO46EC 1366x768 340x190mm 15.3-inch            | 1         | 1.69%   |
| AU Optronics LCD Monitor AUO45EC 1366x768 340x190mm 15.3-inch            | 1         | 1.69%   |
| AU Optronics LCD Monitor AUO4100 1920x1200 220x140mm 10.3-inch           | 1         | 1.69%   |
| AU Optronics LCD Monitor AUO315C 1366x768 260x140mm 11.6-inch            | 1         | 1.69%   |
| AU Optronics LCD Monitor AUO313C 1366x768 310x170mm 13.9-inch            | 1         | 1.69%   |
| AU Optronics LCD Monitor AUO303E 1600x900 310x170mm 13.9-inch            | 1         | 1.69%   |
| AU Optronics LCD Monitor AUO253C 1366x768 310x170mm 13.9-inch            | 1         | 1.69%   |
| AU Optronics LCD Monitor AUO22EC 1366x768 340x190mm 15.3-inch            | 1         | 1.69%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 340x190mm 15.3-inch           | 1         | 1.69%   |
| AU Optronics LCD Monitor AUO206C 1366x768 280x160mm 12.7-inch            | 1         | 1.69%   |
| Apple LCD Monitor APP9CC3 1280x800 290x180mm 13.4-inch                   | 1         | 1.69%   |
| Apple Color LCD APP9CF3 1366x768 260x140mm 11.6-inch                     | 1         | 1.69%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart_bsd/mon_resolution.svg)


| Resolution        | Notebooks | Percent |
|-------------------|-----------|---------|
| 1366x768 (WXGA)   | 35        | 59.32%  |
| 1920x1080 (FHD)   | 9         | 15.25%  |
| 1600x900 (HD+)    | 5         | 8.47%   |
| 1280x800 (WXGA)   | 3         | 5.08%   |
| 1280x1024 (SXGA)  | 2         | 3.39%   |
| 1024x600          | 2         | 3.39%   |
| 3200x1800 (QHD+)  | 1         | 1.69%   |
| 2560x1440 (QHD)   | 1         | 1.69%   |
| 1920x1200 (WUXGA) | 1         | 1.69%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart_bsd/mon_diagonal.svg)


| Inches | Notebooks | Percent |
|--------|-----------|---------|
| 15     | 21        | 35.59%  |
| 13     | 17        | 28.81%  |
| 12     | 6         | 10.17%  |
| 11     | 5         | 8.47%   |
| 17     | 3         | 5.08%   |
| 10     | 3         | 5.08%   |
| 19     | 2         | 3.39%   |
| 24     | 1         | 1.69%   |
| 14     | 1         | 1.69%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart_bsd/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 35        | 60.34%  |
| 201-300     | 18        | 31.03%  |
| 351-400     | 3         | 5.17%   |
| 501-600     | 1         | 1.72%   |
| 401-500     | 1         | 1.72%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart_bsd/mon_ratio.svg)


| Ratio | Notebooks | Percent |
|-------|-----------|---------|
| 16/9  | 52        | 89.66%  |
| 16/10 | 4         | 6.9%    |
| 5/4   | 2         | 3.45%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart_bsd/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 81-90          | 16        | 27.12%  |
| 91-100         | 14        | 23.73%  |
| 101-110        | 7         | 11.86%  |
| 61-70          | 6         | 10.17%  |
| 51-60          | 5         | 8.47%   |
| 41-50          | 3         | 5.08%   |
| 71-80          | 2         | 3.39%   |
| 151-200        | 2         | 3.39%   |
| 121-130        | 2         | 3.39%   |
| 201-250        | 1         | 1.69%   |
| 141-150        | 1         | 1.69%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart_bsd/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 101-120       | 28        | 48.28%  |
| 121-160       | 16        | 27.59%  |
| 51-100        | 8         | 13.79%  |
| 161-240       | 5         | 8.62%   |
| More than 240 | 1         | 1.72%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart_bsd/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 56        | 81.16%  |
| 0     | 10        | 14.49%  |
| 2     | 3         | 4.35%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart_bsd/net_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 32        | 29.63%  |
| Realtek Semiconductor             | 28        | 25.93%  |
| Qualcomm Atheros                  | 19        | 17.59%  |
| Broadcom                          | 14        | 12.96%  |
| JMicron Technology                | 3         | 2.78%   |
| Ericsson Business Mobile Networks | 3         | 2.78%   |
| Marvell Technology Group          | 2         | 1.85%   |
| Huawei Technologies               | 2         | 1.85%   |
| Xiaomi                            | 1         | 0.93%   |
| Sierra Wireless                   | 1         | 0.93%   |
| Ralink                            | 1         | 0.93%   |
| Nvidia                            | 1         | 0.93%   |
| Google                            | 1         | 0.93%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart_bsd/net_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller              | 14        | 10%     |
| Realtek RTL810xE PCI Express Fast Ethernet controller                          | 8         | 5.71%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                               | 6         | 4.29%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                          | 6         | 4.29%   |
| Intel Wireless 7265                                                            | 5         | 3.57%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                 | 4         | 2.86%   |
| Intel Wireless 7260                                                            | 4         | 2.86%   |
| Realtek RTL8188EE Wireless Network Adapter                                     | 3         | 2.14%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                                     | 3         | 2.14%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                                   | 3         | 2.14%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                            | 2         | 1.43%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                     | 2         | 1.43%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                                         | 2         | 1.43%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                                       | 2         | 1.43%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                                       | 2         | 1.43%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller                         | 2         | 1.43%   |
| Intel Wireless 8265 / 8275                                                     | 2         | 1.43%   |
| Intel Ethernet Connection I217-LM                                              | 2         | 1.43%   |
| Intel Ethernet Connection (4) I219-LM                                          | 2         | 1.43%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                                   | 2         | 1.43%   |
| Intel Centrino Ultimate-N 6300                                                 | 2         | 1.43%   |
| Intel Centrino Advanced-N 6235                                                 | 2         | 1.43%   |
| Intel 82577LC Gigabit Network Connection                                       | 2         | 1.43%   |
| Ericsson Business Mobile Networks F5521 gw Mobile Broadband Serial Port III    | 2         | 1.43%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                                | 2         | 1.43%   |
| Broadcom BCM43142 802.11b/g/n                                                  | 2         | 1.43%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                            | 2         | 1.43%   |
| Xiaomi Mi/Redmi series (RNDIS)                                                 | 1         | 0.71%   |
| Sierra Wireless Sierra Wireless EM7345 4G LTE                                  | 1         | 0.71%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter                       | 1         | 0.71%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                       | 1         | 0.71%   |
| Realtek RTL8723DE Wireless Network Adapter                                     | 1         | 0.71%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                                | 1         | 0.71%   |
| Realtek Realtek Bluetooth 4.2 Adapter                                          | 1         | 0.71%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                                      | 1         | 0.71%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)                 | 1         | 0.71%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)                 | 1         | 0.71%   |
| Qualcomm Atheros AR8162 Fast Ethernet                                          | 1         | 0.71%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                                     | 1         | 0.71%   |
| Qualcomm Atheros AR8152 v1.1 Fast Ethernet                                     | 1         | 0.71%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                  | 1         | 0.71%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                          | 1         | 0.71%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express)        | 1         | 0.71%   |
| Nvidia MCP79 Ethernet                                                          | 1         | 0.71%   |
| Marvell Group Yukon Optima 88E8059 [PCIe Gigabit Ethernet Controller with AVB] | 1         | 0.71%   |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller                        | 1         | 0.71%   |
| JMicron JMC260 PCI Express Fast Ethernet Controller                            | 1         | 0.71%   |
| Intel Wireless 8260                                                            | 1         | 0.71%   |
| Intel Wireless 3160                                                            | 1         | 0.71%   |
| Intel WiFi Link 5100                                                           | 1         | 0.71%   |
| Intel Wi-Fi 6 AX201                                                            | 1         | 0.71%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection                        | 1         | 0.71%   |
| Intel Ethernet Connection I219-V                                               | 1         | 0.71%   |
| Intel Ethernet Connection I218-LM                                              | 1         | 0.71%   |
| Intel Ethernet Connection (3) I218-V                                           | 1         | 0.71%   |
| Intel Ethernet Connection (3) I218-LM                                          | 1         | 0.71%   |
| Intel Centrino Wireless-N 6150                                                 | 1         | 0.71%   |
| Intel Centrino Wireless-N 2200                                                 | 1         | 0.71%   |
| Intel Centrino Wireless-N 135                                                  | 1         | 0.71%   |
| Intel Centrino Wireless-N 1030 [Rainbow Peak]                                  | 1         | 0.71%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart_bsd/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 30        | 43.48%  |
| Qualcomm Atheros      | 15        | 21.74%  |
| Realtek Semiconductor | 11        | 15.94%  |
| Broadcom              | 11        | 15.94%  |
| Sierra Wireless       | 1         | 1.45%   |
| Ralink                | 1         | 1.45%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart_bsd/net_wireless_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 6         | 8.33%   |
| Intel Wireless 7265                                                     | 5         | 6.94%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 4         | 5.56%   |
| Intel Wireless 7260                                                     | 4         | 5.56%   |
| Realtek RTL8188EE Wireless Network Adapter                              | 3         | 4.17%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 3         | 4.17%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 3         | 4.17%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 2         | 2.78%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 2         | 2.78%   |
| Intel Wireless 8265 / 8275                                              | 2         | 2.78%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                            | 2         | 2.78%   |
| Intel Centrino Ultimate-N 6300                                          | 2         | 2.78%   |
| Intel Centrino Advanced-N 6235                                          | 2         | 2.78%   |
| Broadcom BCM43142 802.11b/g/n                                           | 2         | 2.78%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 2         | 2.78%   |
| Sierra Wireless Sierra Wireless EM7345 4G LTE                           | 1         | 1.39%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter                | 1         | 1.39%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 1         | 1.39%   |
| Realtek RTL8723DE Wireless Network Adapter                              | 1         | 1.39%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 1         | 1.39%   |
| Realtek Realtek Bluetooth 4.2 Adapter                                   | 1         | 1.39%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                               | 1         | 1.39%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 1         | 1.39%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)          | 1         | 1.39%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 1         | 1.39%   |
| Intel Wireless 8260                                                     | 1         | 1.39%   |
| Intel Wireless 3160                                                     | 1         | 1.39%   |
| Intel WiFi Link 5100                                                    | 1         | 1.39%   |
| Intel Wi-Fi 6 AX201                                                     | 1         | 1.39%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection                 | 1         | 1.39%   |
| Intel Centrino Wireless-N 6150                                          | 1         | 1.39%   |
| Intel Centrino Wireless-N 2200                                          | 1         | 1.39%   |
| Intel Centrino Wireless-N 135                                           | 1         | 1.39%   |
| Intel Centrino Wireless-N 1030 [Rainbow Peak]                           | 1         | 1.39%   |
| Intel Centrino WiMAX 6150                                               | 1         | 1.39%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 1         | 1.39%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                      | 1         | 1.39%   |
| Broadcom BCM4331 802.11a/b/g/n                                          | 1         | 1.39%   |
| Broadcom BCM43228 802.11a/b/g/n                                         | 1         | 1.39%   |
| Broadcom BCM43225 802.11b/g/n                                           | 1         | 1.39%   |
| Broadcom BCM43224 802.11a/b/g/n                                         | 1         | 1.39%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller                  | 1         | 1.39%   |
| Broadcom BCM4321 802.11a/b/g/n                                          | 1         | 1.39%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart_bsd/net_ethernet_vendor.svg)


| Vendor                   | Notebooks | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 22        | 34.38%  |
| Intel                    | 17        | 26.56%  |
| Qualcomm Atheros         | 11        | 17.19%  |
| Broadcom                 | 5         | 7.81%   |
| JMicron Technology       | 3         | 4.69%   |
| Marvell Technology Group | 2         | 3.13%   |
| Xiaomi                   | 1         | 1.56%   |
| Nvidia                   | 1         | 1.56%   |
| Huawei Technologies      | 1         | 1.56%   |
| Google                   | 1         | 1.56%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart_bsd/net_ethernet_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller              | 14        | 21.88%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                          | 8         | 12.5%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                          | 6         | 9.38%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                                         | 2         | 3.13%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                                       | 2         | 3.13%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                                       | 2         | 3.13%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller                         | 2         | 3.13%   |
| Intel Ethernet Connection I217-LM                                              | 2         | 3.13%   |
| Intel Ethernet Connection (4) I219-LM                                          | 2         | 3.13%   |
| Intel 82577LC Gigabit Network Connection                                       | 2         | 3.13%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                                | 2         | 3.13%   |
| Xiaomi Mi/Redmi series (RNDIS)                                                 | 1         | 1.56%   |
| Qualcomm Atheros AR8162 Fast Ethernet                                          | 1         | 1.56%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                                     | 1         | 1.56%   |
| Qualcomm Atheros AR8152 v1.1 Fast Ethernet                                     | 1         | 1.56%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                  | 1         | 1.56%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                          | 1         | 1.56%   |
| Nvidia MCP79 Ethernet                                                          | 1         | 1.56%   |
| Marvell Group Yukon Optima 88E8059 [PCIe Gigabit Ethernet Controller with AVB] | 1         | 1.56%   |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller                        | 1         | 1.56%   |
| JMicron JMC260 PCI Express Fast Ethernet Controller                            | 1         | 1.56%   |
| Intel Ethernet Connection I219-V                                               | 1         | 1.56%   |
| Intel Ethernet Connection I218-LM                                              | 1         | 1.56%   |
| Intel Ethernet Connection (3) I218-V                                           | 1         | 1.56%   |
| Intel Ethernet Connection (3) I218-LM                                          | 1         | 1.56%   |
| Intel 82567LM Gigabit Network Connection                                       | 1         | 1.56%   |
| Huawei USB Composite Device                                                    | 1         | 1.56%   |
| Google Nexus/Pixel Device (tether)                                             | 1         | 1.56%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                              | 1         | 1.56%   |
| Broadcom NetLink BCM5906M Fast Ethernet PCI Express                            | 1         | 1.56%   |
| Broadcom NetLink BCM5787M Gigabit Ethernet PCI Express                         | 1         | 1.56%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart_bsd/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 67        | 50.38%  |
| Ethernet | 62        | 46.62%  |
| Modem    | 2         | 1.5%    |
| Unknown  | 2         | 1.5%    |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart_bsd/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| Ethernet | 59        | 50%     |
| WiFi     | 56        | 47.46%  |
| Unknown  | 2         | 1.69%   |
| Modem    | 1         | 0.85%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart_bsd/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 58        | 84.06%  |
| 1     | 11        | 15.94%  |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart_bsd/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 67        | 97.1%   |
| Yes  | 2         | 2.9%    |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart_bsd/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 16        | 43.24%  |
| Broadcom                        | 7         | 18.92%  |
| Apple                           | 5         | 13.51%  |
| Realtek Semiconductor           | 3         | 8.11%   |
| Foxconn / Hon Hai               | 2         | 5.41%   |
| Ralink                          | 1         | 2.7%    |
| Qualcomm Atheros Communications | 1         | 2.7%    |
| Hewlett-Packard                 | 1         | 2.7%    |
| Cambridge Silicon Radio         | 1         | 2.7%    |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart_bsd/bt_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 11        | 29.73%  |
| Intel Centrino Bluetooth Wireless Transceiver       | 2         | 5.41%   |
| Broadcom BCM43142 Bluetooth 4.0                     | 2         | 5.41%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 2         | 5.41%   |
| Apple Apple Broadcom Built-in Bluetooth             | 2         | 5.41%   |
| Realtek RTL8723B Bluetooth                          | 1         | 2.7%    |
| Realtek  Bluetooth Adapter                          | 1         | 2.7%    |
| Realtek Bluetooth Radio                             | 1         | 2.7%    |
| Ralink RT3290 Bluetooth                             | 1         | 2.7%    |
| Qualcomm Atheros AR9462 Bluetooth                   | 1         | 2.7%    |
| Intel Centrino Advanced-N 6230 Bluetooth adapter    | 1         | 2.7%    |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 1         | 2.7%    |
| Intel AX201 Bluetooth                               | 1         | 2.7%    |
| HP Broadcom 2070 Bluetooth Combo                    | 1         | 2.7%    |
| Foxconn / Hon Hai Broadcom BCM20702 Bluetooth       | 1         | 2.7%    |
| Foxconn / Hon Hai Atheros AR3012 Bluetooth          | 1         | 2.7%    |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 1         | 2.7%    |
| Broadcom Broadcom Bluetooth 4.0                     | 1         | 2.7%    |
| Broadcom BCM2046 Bluetooth Device                   | 1         | 2.7%    |
| Broadcom BCM2045B (BDC-2.1)                         | 1         | 2.7%    |
| Apple Built-in Bluetooth 2.0+EDR HCI                | 1         | 2.7%    |
| Apple Bluetooth Host Controller                     | 1         | 2.7%    |
| Apple Bluetooth HCI                                 | 1         | 2.7%    |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart_bsd/snd_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 64        | 85.33%  |
| Nvidia | 5         | 6.67%   |
| AMD    | 5         | 6.67%   |
| XMOS   | 1         | 1.33%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart_bsd/snd_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 18        | 20.22%  |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 10        | 11.24%  |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 7         | 7.87%   |
| Intel Sunrise Point-LP HD Audio                                            | 5         | 5.62%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 4         | 4.49%   |
| Intel Broadwell-U Audio Controller                                         | 4         | 4.49%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 4         | 4.49%   |
| Intel 8 Series HD Audio Controller                                         | 4         | 4.49%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 3         | 3.37%   |
| Intel Haswell-ULT HD Audio Controller                                      | 3         | 3.37%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller | 3         | 3.37%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 3         | 3.37%   |
| AMD Wrestler HDMI Audio                                                    | 3         | 3.37%   |
| Nvidia GF108 High Definition Audio Controller                              | 2         | 2.25%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 2         | 2.25%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 2         | 2.25%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 2         | 2.25%   |
| XMOS retrieving string failed                                              | 1         | 1.12%   |
| Nvidia MCP79 High Definition Audio                                         | 1         | 1.12%   |
| Nvidia High Definition Audio Controller                                    | 1         | 1.12%   |
| Nvidia GF106 High Definition Audio Controller                              | 1         | 1.12%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 1         | 1.12%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                             | 1         | 1.12%   |
| AMD RV710/730 HDMI Audio [Radeon HD 4000 series]                           | 1         | 1.12%   |
| AMD High Definition Audio Controller                                       | 1         | 1.12%   |
| AMD FCH Azalia Controller                                                  | 1         | 1.12%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                           | 1         | 1.12%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart_bsd/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| SK Hynix            | 21        | 23.86%  |
| Samsung Electronics | 16        | 18.18%  |
| Micron Technology   | 9         | 10.23%  |
| Unknown             | 8         | 9.09%   |
| Kingston            | 8         | 9.09%   |
| Teikon              | 3         | 3.41%   |
| Smart               | 3         | 3.41%   |
| Nanya Technology    | 3         | 3.41%   |
| Elpida              | 3         | 3.41%   |
| Team                | 2         | 2.27%   |
| Ramaxel Technology  | 2         | 2.27%   |
| Apacer              | 2         | 2.27%   |
| Unknown             | 2         | 2.27%   |
| Smart Brazil        | 1         | 1.14%   |
| SHARETRONIC         | 1         | 1.14%   |
| PKI/Kingston        | 1         | 1.14%   |
| Crucial             | 1         | 1.14%   |
| ASint Technology    | 1         | 1.14%   |
| A-DATA Technology   | 1         | 1.14%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart_bsd/memory_model.svg)


| Model                                                        | Notebooks | Percent |
|--------------------------------------------------------------|-----------|---------|
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                   | 2         | 2.2%    |
| SK Hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s       | 2         | 2.2%    |
| SK Hynix RAM HMT351S6EFR8A-PB 4GB SODIMM DDR3 1600MT/s       | 2         | 2.2%    |
| SK Hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s       | 2         | 2.2%    |
| SK Hynix RAM HMT325S6BFR8C-H9 2GB SODIMM DDR3 1333MT/s       | 2         | 2.2%    |
| Samsung RAM M471B5673FH0-CH9 2GB SODIMM DDR3 1333MT/s        | 2         | 2.2%    |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s        | 2         | 2.2%    |
| Nanya RAM NT2GC64B8HA1NS-BE 2GB SODIMM DDR3 1067MT/s         | 2         | 2.2%    |
| Unknown                                                      | 2         | 2.2%    |
| Unknown RAM Module 4GB SODIMM DDR3 1600MT/s                  | 1         | 1.1%    |
| Unknown RAM Module 4GB SODIMM DDR3 1333MT/s                  | 1         | 1.1%    |
| Unknown RAM Module 4GB SODIMM DDR3                           | 1         | 1.1%    |
| Unknown RAM Module 4GB SODIMM DDR2 800MT/s                   | 1         | 1.1%    |
| Unknown RAM Module 4GB DIMM DDR3 1067MT/s                    | 1         | 1.1%    |
| Unknown RAM Module 2GB SODIMM DDR3                           | 1         | 1.1%    |
| Teikon RAM TMT451S6BFR8A-PBHC 4GB SODIMM DDR3 1333MT/s       | 1         | 1.1%    |
| Teikon RAM TMT41GS6BFR8A-PBSC 8GB SODIMM DDR3 1600MT/s       | 1         | 1.1%    |
| Teikon RAM TMT225S6FR8C-H9HC 2GB SODIMM DDR3 1334MT/s        | 1         | 1.1%    |
| Team RAM TEAMGROUP-SD3-1066 4GB SODIMM DDR3 1067MT/s         | 1         | 1.1%    |
| Team RAM Elite-1333 4GB SODIMM DDR3 1333MT/s                 | 1         | 1.1%    |
| Smart RAM SH564568FH8NZPHSCR 2GB SODIMM DDR3 1334MT/s        | 1         | 1.1%    |
| Smart RAM SH564128FJ8NWRNSQG 4GB SODIMM DDR3 1600MT/s        | 1         | 1.1%    |
| Smart RAM SH564128FH8NZPHSCR 4GB SODIMM DDR3 1333MT/s        | 1         | 1.1%    |
| Smart Brazil RAM SF4641G8CK8IEHLSBG 8GB SODIMM DDR4 2133MT/s | 1         | 1.1%    |
| SK Hynix RAM Module 8GB SODIMM DDR4 2400MT/s                 | 1         | 1.1%    |
| SK Hynix RAM Module 8GB Row Of Chips LPDDR3 1600MT/s         | 1         | 1.1%    |
| SK Hynix RAM Module 4GB SODIMM DDR3 1067MT/s                 | 1         | 1.1%    |
| SK Hynix RAM Module 2GB SODIMM DDR3 1600MT/s                 | 1         | 1.1%    |
| SK Hynix RAM HMT451S6AFR8C-PB 4GB SODIMM DDR3 1600MT/s       | 1         | 1.1%    |
| SK Hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s       | 1         | 1.1%    |
| SK Hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s       | 1         | 1.1%    |
| SK Hynix RAM HMT41GS6AFR8A-PB 8GB SODIMM DDR3 1600MT/s       | 1         | 1.1%    |
| SK Hynix RAM HMT351S6EFR8C-PB 4GB SODIMM DDR3 1600MT/s       | 1         | 1.1%    |
| SK Hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1333MT/s       | 1         | 1.1%    |
| SK Hynix RAM HMT351S6CFR8C-H9 4GB SODIMM DDR3 1333MT/s       | 1         | 1.1%    |
| SK Hynix RAM HMT351S6CFR8A-PB 4GB SODIMM DDR3 1600MT/s       | 1         | 1.1%    |
| SK Hynix RAM HMT351S6CFR8A-PB 4GB SODIMM DDR3 1333MT/s       | 1         | 1.1%    |
| SK Hynix RAM HMT351S6BFR8C-H9 4GB SODIMM DDR3 1333MT/s       | 1         | 1.1%    |
| SHARETRONIC RAM Module 2GB SODIMM DDR3 1600MT/s              | 1         | 1.1%    |
| Samsung RAM Module 2GB SODIMM DDR3 1067MT/s                  | 1         | 1.1%    |
| Samsung RAM M471B5674QH0-YK0 2GB SODIMM DDR3 1600MT/s        | 1         | 1.1%    |
| Samsung RAM M471B5674-H0-YK0--- 4GB Chip DDR3 1600MT/s       | 1         | 1.1%    |
| Samsung RAM M471B5673FH0-CF8 2GB SODIMM DDR3 1067MT/s        | 1         | 1.1%    |
| Samsung RAM M471B5673EH1-CF8 2GB SODIMM 1067MT/s             | 1         | 1.1%    |
| Samsung RAM M471B5273DH0-CK0 4GB SODIMM DDR3 1600MT/s        | 1         | 1.1%    |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s        | 1         | 1.1%    |
| Samsung RAM M471B5273CH0-CF8 4GB SODIMM DDR3 1067MT/s        | 1         | 1.1%    |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s        | 1         | 1.1%    |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1600MT/s        | 1         | 1.1%    |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s        | 1         | 1.1%    |
| Samsung RAM M471B1G73CB0-YK0 8GB SODIMM DDR3 1600MT/s        | 1         | 1.1%    |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 2667MT/s        | 1         | 1.1%    |
| Samsung RAM K4B8G1646B-MYK0 4GB SODIMM DDR3 1600MT/s         | 1         | 1.1%    |
| Ramaxel RAM RMT3190ME76F8F1600 2GB SODIMM DDR3 1067MT/s      | 1         | 1.1%    |
| Ramaxel RAM RMSA3230KB78HAF2133 8GB SODIMM DDR4 2133MT/s     | 1         | 1.1%    |
| PKI/Kingston RAM 9905428-043.A00LF 4GB SODIMM DDR3 1067MT/s  | 1         | 1.1%    |
| Nanya RAM NT4GC64B8HB0NS-CG 4GB SODIMM DDR3 1067MT/s         | 1         | 1.1%    |
| Micron RAM Module 2GB SODIMM DDR3 1333MT/s                   | 1         | 1.1%    |
| Micron RAM 8KTF51264HZ-1G6N1 4GB SODIMM DDR3 1600MT/s        | 1         | 1.1%    |
| Micron RAM 8KTF5126 4HZ-1G6D1 4GB SODIMM DDR3 1600MT/s       | 1         | 1.1%    |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart_bsd/memory_kind.svg)


| Kind   | Notebooks | Percent |
|--------|-----------|---------|
| DDR3   | 54        | 80.6%   |
| DDR4   | 6         | 8.96%   |
| DDR2   | 4         | 5.97%   |
| LPDDR3 | 2         | 2.99%   |
| LPDDR4 | 1         | 1.49%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart_bsd/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 63        | 94.03%  |
| Row Of Chips | 2         | 2.99%   |
| DIMM         | 1         | 1.49%   |
| Chip         | 1         | 1.49%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart_bsd/memory_size.svg)


| Size | Notebooks | Percent |
|------|-----------|---------|
| 4096 | 39        | 50%     |
| 2048 | 25        | 32.05%  |
| 8192 | 14        | 17.95%  |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart_bsd/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 1600    | 29        | 38.16%  |
| 1333    | 16        | 21.05%  |
| 1067    | 12        | 15.79%  |
| 1334    | 5         | 6.58%   |
| 667     | 3         | 3.95%   |
| 2667    | 2         | 2.63%   |
| 2400    | 2         | 2.63%   |
| 2133    | 2         | 2.63%   |
| Unknown | 2         | 2.63%   |
| 4267    | 1         | 1.32%   |
| 1066    | 1         | 1.32%   |
| 800     | 1         | 1.32%   |

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
| Chicony Electronics                    | 16        | 31.37%  |
| Acer                                   | 8         | 15.69%  |
| Sunplus Innovation Technology          | 4         | 7.84%   |
| Microdia                               | 4         | 7.84%   |
| Realtek Semiconductor                  | 3         | 5.88%   |
| Cheng Uei Precision Industry (Foxlink) | 3         | 5.88%   |
| Suyin                                  | 2         | 3.92%   |
| IMC Networks                           | 2         | 3.92%   |
| Apple                                  | 2         | 3.92%   |
| Tripath Technology                     | 1         | 1.96%   |
| Syntek                                 | 1         | 1.96%   |
| Lite-On Technology                     | 1         | 1.96%   |
| Lenovo                                 | 1         | 1.96%   |
| Importek                               | 1         | 1.96%   |
| Foxconn / Hon Hai                      | 1         | 1.96%   |
| ALi                                    | 1         | 1.96%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart_bsd/camera_model.svg)


| Model                                                          | Notebooks | Percent |
|----------------------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                                      | 8         | 15.69%  |
| Acer Lenovo EasyCamera                                         | 3         | 5.88%   |
| Acer Integrated Camera                                         | 3         | 5.88%   |
| Realtek Realtek USB2.0 PC Camera                               | 2         | 3.92%   |
| Tripath 2M Front Camera                                        | 1         | 1.96%   |
| Syntek EasyCamera                                              | 1         | 1.96%   |
| Suyin Integrated_Webcam_HD                                     | 1         | 1.96%   |
| Suyin 1.3M WebCam (notebook emachines E730, Acer sub-brand)    | 1         | 1.96%   |
| Sunplus Lenovo EasyCamera                                      | 1         | 1.96%   |
| Sunplus Laptop_Integrated_Webcam_FHD                           | 1         | 1.96%   |
| Sunplus Integrated Camera                                      | 1         | 1.96%   |
| Sunplus HP Universal Camera                                    | 1         | 1.96%   |
| Realtek Integrated_Webcam_HD                                   | 1         | 1.96%   |
| Microdia Webcam                                                | 1         | 1.96%   |
| Microdia Laptop_Integrated_Webcam_2M                           | 1         | 1.96%   |
| Microdia Integrated Webcam HD                                  | 1         | 1.96%   |
| Microdia Dell Laptop Integrated Webcam HD                      | 1         | 1.96%   |
| Lite-On Integrated Camera                                      | 1         | 1.96%   |
| Lenovo Integrated Webcam                                       | 1         | 1.96%   |
| Importek HP Webcam                                             | 1         | 1.96%   |
| IMC Networks USB2.0 UVC HD Webcam                              | 1         | 1.96%   |
| IMC Networks 2M Integrated Webcam                              | 1         | 1.96%   |
| Foxconn / Hon Hai USB2.0 Camera                                | 1         | 1.96%   |
| Chicony WebCam                                                 | 1         | 1.96%   |
| Chicony USB2.0 HD UVC WebCam                                   | 1         | 1.96%   |
| Chicony TOSHIBA Web Camera - HD                                | 1         | 1.96%   |
| Chicony Sony Visual Communication Camera                       | 1         | 1.96%   |
| Chicony Lenovo Integrated Camera (0.3MP)                       | 1         | 1.96%   |
| Chicony Lenovo EasyCamera                                      | 1         | 1.96%   |
| Chicony Asus 720p CMOS webcam                                  | 1         | 1.96%   |
| Chicony 1.3M Webcam                                            | 1         | 1.96%   |
| Cheng Uei Precision Industry (Foxlink) HP Webcam-101           | 1         | 1.96%   |
| Cheng Uei Precision Industry (Foxlink) HP Universal Camera     | 1         | 1.96%   |
| Cheng Uei Precision Industry (Foxlink) HP TrueVision HD Camera | 1         | 1.96%   |
| Apple FaceTime HD Camera (Built-in)                            | 1         | 1.96%   |
| Apple FaceTime HD Camera                                       | 1         | 1.96%   |
| ALi WebCam                                                     | 1         | 1.96%   |
| Acer ThinkPad Integrated Camera                                | 1         | 1.96%   |
| Acer HD Webcam                                                 | 1         | 1.96%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart_bsd/fingerprint_vendor.svg)


| Vendor           | Notebooks | Percent |
|------------------|-----------|---------|
| Validity Sensors | 7         | 53.85%  |
| Upek             | 3         | 23.08%  |
| AuthenTec        | 3         | 23.08%  |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart_bsd/fingerprint_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Validity Sensors VFS 5011 fingerprint sensor                               | 4         | 30.77%  |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 3         | 23.08%  |
| Validity Sensors VFS301 Fingerprint Reader                                 | 1         | 7.69%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 1         | 7.69%   |
| Validity Sensors Fingerprint scanner                                       | 1         | 7.69%   |
| AuthenTec AuthenTec Inc. AES1660                                           | 1         | 7.69%   |
| AuthenTec AES2810                                                          | 1         | 7.69%   |
| AuthenTec AES1600                                                          | 1         | 7.69%   |

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
| 2     | 21        | 30.43%  |
| 1     | 20        | 28.99%  |
| 3     | 12        | 17.39%  |
| 0     | 11        | 15.94%  |
| 4     | 5         | 7.25%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart_bsd/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Communication controller | 51        | 44.74%  |
| Card reader              | 22        | 19.3%   |
| Net/wireless             | 13        | 11.4%   |
| Fingerprint reader       | 13        | 11.4%   |
| Firewire controller      | 6         | 5.26%   |
| Bluetooth                | 6         | 5.26%   |
| Storage                  | 2         | 1.75%   |
| Network                  | 1         | 0.88%   |

