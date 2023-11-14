helloSystem 0.6.0 - Tested Hardware & Statistics (Notebooks)
------------------------------------------------------------

A project to collect tested hardware configurations for helloSystem 0.6.0.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe/blob/master/INSTALL.BSD.md) tool:

    hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

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
| Toshiba   | Satellite C55-A             | [f27ea283cf](https://bsd-hardware.info/?probe=f27ea283cf) | Oct 12, 2023 |
| Lenovo    | ThinkPad X61s 76693KG       | [445446cc28](https://bsd-hardware.info/?probe=445446cc28) | Jul 18, 2022 |
| Apple     | MacBookPro3,1               | [912d02aec2](https://bsd-hardware.info/?probe=912d02aec2) | Apr 28, 2022 |
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
| amd64 | 72        | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart_bsd/os_de.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| helloDesktop | 70        | 97.22%  |
| XFCE         | 1         | 1.39%   |
| KDE5         | 1         | 1.39%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart_bsd/os_display_server.svg)


| Name | Notebooks | Percent |
|------|-----------|---------|
| X11  | 72        | 100%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart_bsd/os_display_manager.svg)


| Name | Notebooks | Percent |
|------|-----------|---------|
| SLiM | 72        | 100%    |

OS Lang
-------

Language

![OS Lang](./images/pie_chart_bsd/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| en_US   | 68        | 94.44%  |
| de_DE   | 2         | 2.78%   |
| ru_RU   | 1         | 1.39%   |
| Unknown | 1         | 1.39%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart_bsd/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 55        | 75.34%  |
| BIOS | 18        | 24.66%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart_bsd/os_filesystem.svg)


| Type | Notebooks | Percent |
|------|-----------|---------|
| Zfs  | 72        | 100%    |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart_bsd/os_part_scheme.svg)


| Type | Notebooks | Percent |
|------|-----------|---------|
| GPT  | 72        | 100%    |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart_bsd/node_vendor.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| Lenovo           | 26        | 36.11%  |
| Hewlett-Packard  | 9         | 12.5%   |
| Dell             | 8         | 11.11%  |
| Toshiba          | 5         | 6.94%   |
| Apple            | 5         | 6.94%   |
| ASUSTek Computer | 4         | 5.56%   |
| Acer             | 4         | 5.56%   |
| Sony             | 3         | 4.17%   |
| Semp Toshiba     | 1         | 1.39%   |
| Positivo         | 1         | 1.39%   |
| Philco           | 1         | 1.39%   |
| MSI              | 1         | 1.39%   |
| Kraftway         | 1         | 1.39%   |
| Itautec          | 1         | 1.39%   |
| eMachines        | 1         | 1.39%   |
| Chuwi            | 1         | 1.39%   |

Model
-----

Motherboard model

![Model](./images/pie_chart_bsd/node_model.svg)


| Name                                       | Notebooks | Percent |
|--------------------------------------------|-----------|---------|
| Toshiba Satellite S55t-B                   | 1         | 1.39%   |
| Toshiba Satellite L50-A                    | 1         | 1.39%   |
| Toshiba Satellite C55-A                    | 1         | 1.39%   |
| Toshiba PORTEGE M780                       | 1         | 1.39%   |
| Toshiba dynabook RX3 SM240E/3HD            | 1         | 1.39%   |
| Sony VPCYB45JB                             | 1         | 1.39%   |
| Sony VPCEB1J1E                             | 1         | 1.39%   |
| Sony SVS1511AJB                            | 1         | 1.39%   |
| Semp Toshiba STI NA 1401                   | 1         | 1.39%   |
| Positivo C14CR01                           | 1         | 1.39%   |
| Philco 10B                                 | 1         | 1.39%   |
| MSI MS-16F1                                | 1         | 1.39%   |
| Lenovo Yoga 3 Pro-1370 80HE                | 1         | 1.39%   |
| Lenovo ThinkPad Yoga 11e 20DAS0AE00        | 1         | 1.39%   |
| Lenovo ThinkPad X61s 76693KG               | 1         | 1.39%   |
| Lenovo ThinkPad X250 20CLS2A11K            | 1         | 1.39%   |
| Lenovo ThinkPad X230 2325IG2               | 1         | 1.39%   |
| Lenovo ThinkPad X230 23062S2               | 1         | 1.39%   |
| Lenovo ThinkPad X1 Carbon Gen 9 20XWA003CD | 1         | 1.39%   |
| Lenovo ThinkPad X1 Carbon 2nd 20A70066UK   | 1         | 1.39%   |
| Lenovo ThinkPad W520 4276CTO               | 1         | 1.39%   |
| Lenovo ThinkPad T450s 20BX001PUS           | 1         | 1.39%   |
| Lenovo ThinkPad T440p 20AW007QMS           | 1         | 1.39%   |
| Lenovo ThinkPad T430u 3352AA5              | 1         | 1.39%   |
| Lenovo ThinkPad T420 4180EE8               | 1         | 1.39%   |
| Lenovo ThinkPad SL 2746M3C                 | 1         | 1.39%   |
| Lenovo ThinkPad R500 2718W92               | 1         | 1.39%   |
| Lenovo ThinkPad L440 20ASS0FP00            | 1         | 1.39%   |
| Lenovo ThinkPad 13 20GJCTO1WW              | 1         | 1.39%   |
| Lenovo S20-30 Touch 20434                  | 1         | 1.39%   |
| Lenovo IdeaPad Z360                        | 1         | 1.39%   |
| Lenovo IdeaPad S145-15IWL 81MV             | 1         | 1.39%   |
| Lenovo IdeaPad L340-15IWL 81LG             | 1         | 1.39%   |
| Lenovo G580 20150                          | 1         | 1.39%   |
| Lenovo G550 2958                           | 1         | 1.39%   |
| Lenovo G500s 20245                         | 1         | 1.39%   |
| Lenovo G500 20236                          | 1         | 1.39%   |
| Lenovo B590 62743PG                        | 1         | 1.39%   |
| Kraftway KW10T                             | 1         | 1.39%   |
| Itautec Infoway w7530                      | 1         | 1.39%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart_bsd/node_model_family.svg)


| Name              | Notebooks | Percent |
|-------------------|-----------|---------|
| Lenovo ThinkPad   | 16        | 22.22%  |
| Acer Aspire       | 4         | 5.56%   |
| Toshiba Satellite | 3         | 4.17%   |
| Lenovo IdeaPad    | 3         | 4.17%   |
| Dell Latitude     | 3         | 4.17%   |
| Dell Inspiron     | 3         | 4.17%   |
| HP Pavilion       | 2         | 2.78%   |
| HP EliteBook      | 2         | 2.78%   |
| Toshiba PORTEGE   | 1         | 1.39%   |
| Toshiba dynabook  | 1         | 1.39%   |
| Sony VPCYB45JB    | 1         | 1.39%   |
| Sony VPCEB1J1E    | 1         | 1.39%   |
| Sony SVS1511AJB   | 1         | 1.39%   |
| Semp Toshiba STI  | 1         | 1.39%   |
| Positivo C14CR01  | 1         | 1.39%   |
| Philco 10B        | 1         | 1.39%   |
| MSI MS-16F1       | 1         | 1.39%   |
| Lenovo Yoga       | 1         | 1.39%   |
| Lenovo S20-30     | 1         | 1.39%   |
| Lenovo G580       | 1         | 1.39%   |
| Lenovo G550       | 1         | 1.39%   |
| Lenovo G500s      | 1         | 1.39%   |
| Lenovo G500       | 1         | 1.39%   |
| Lenovo B590       | 1         | 1.39%   |
| Kraftway KW10T    | 1         | 1.39%   |
| Itautec Infoway   | 1         | 1.39%   |
| HP Presario       | 1         | 1.39%   |
| HP Laptop         | 1         | 1.39%   |
| HP 15             | 1         | 1.39%   |
| HP 14             | 1         | 1.39%   |
| eMachines eM350   | 1         | 1.39%   |
| Dell Studio       | 1         | 1.39%   |
| Dell Precision    | 1         | 1.39%   |
| Chuwi MiniBook    | 1         | 1.39%   |
| ASUS X502CA       | 1         | 1.39%   |
| ASUS UX31A        | 1         | 1.39%   |
| ASUS UX21A        | 1         | 1.39%   |
| ASUS U33Jc        | 1         | 1.39%   |
| Apple MacBookPro9 | 1         | 1.39%   |
| Apple MacBookPro5 | 1         | 1.39%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart_bsd/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2013 | 12        | 16.67%  |
| 2012 | 9         | 12.5%   |
| 2011 | 9         | 12.5%   |
| 2014 | 7         | 9.72%   |
| 2010 | 7         | 9.72%   |
| 2019 | 6         | 8.33%   |
| 2015 | 6         | 8.33%   |
| 2020 | 4         | 5.56%   |
| 2009 | 4         | 5.56%   |
| 2016 | 3         | 4.17%   |
| 2008 | 3         | 4.17%   |
| 2021 | 1         | 1.39%   |
| 2018 | 1         | 1.39%   |

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
| No   | 72        | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart_bsd/node_ram_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 4.01-8.0   | 36        | 50%     |
| 8.01-16.0  | 27        | 37.5%   |
| 16.01-24.0 | 8         | 11.11%  |
| 2.01-3.0   | 1         | 1.39%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart_bsd/node_ram_used.svg)


| Used GB  | Notebooks | Percent |
|----------|-----------|---------|
| 0.01-0.5 | 54        | 75%     |
| 0.51-1.0 | 18        | 25%     |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart_bsd/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 60        | 83.33%  |
| 2      | 9         | 12.5%   |
| 0      | 2         | 2.78%   |
| 3      | 1         | 1.39%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart_bsd/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 36        | 50%     |
| No        | 36        | 50%     |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart_bsd/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 65        | 90.28%  |
| No        | 7         | 9.72%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart_bsd/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 69        | 95.83%  |
| No        | 3         | 4.17%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart_bsd/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 36        | 50%     |
| No        | 36        | 50%     |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart_bsd/node_location.svg)


| Country     | Notebooks | Percent |
|-------------|-----------|---------|
| Brazil      | 10        | 13.89%  |
| USA         | 7         | 9.72%   |
| Germany     | 6         | 8.33%   |
| Ukraine     | 4         | 5.56%   |
| Russia      | 4         | 5.56%   |
| UK          | 3         | 4.17%   |
| Spain       | 3         | 4.17%   |
| Netherlands | 3         | 4.17%   |
| Mexico      | 3         | 4.17%   |
| Italy       | 3         | 4.17%   |
| China       | 3         | 4.17%   |
| South Korea | 2         | 2.78%   |
| Poland      | 2         | 2.78%   |
| New Zealand | 2         | 2.78%   |
| Australia   | 2         | 2.78%   |
| Syria       | 1         | 1.39%   |
| Slovakia    | 1         | 1.39%   |
| Singapore   | 1         | 1.39%   |
| Peru        | 1         | 1.39%   |
| Lithuania   | 1         | 1.39%   |
| Libya       | 1         | 1.39%   |
| Japan       | 1         | 1.39%   |
| Greece      | 1         | 1.39%   |
| France      | 1         | 1.39%   |
| Czechia     | 1         | 1.39%   |
| Cuba        | 1         | 1.39%   |
| Colombia    | 1         | 1.39%   |
| Chile       | 1         | 1.39%   |
| Canada      | 1         | 1.39%   |
| Bulgaria    | 1         | 1.39%   |

City
----

Geographic location (city)

![City](./images/pie_chart_bsd/node_city.svg)


| City               | Notebooks | Percent |
|--------------------|-----------|---------|
| Maraba             | 2         | 2.7%    |
| Harrisburg         | 2         | 2.7%    |
| Guangzhou          | 2         | 2.7%    |
| Frankfurt am Main  | 2         | 2.7%    |
| Barcelona          | 2         | 2.7%    |
| Yeongdong-gun      | 1         | 1.35%   |
| Wroclaw            | 1         | 1.35%   |
| Wellington         | 1         | 1.35%   |
| Ufa                | 1         | 1.35%   |
| Tyumen             | 1         | 1.35%   |
| Tula de Allende    | 1         | 1.35%   |
| Tripoli            | 1         | 1.35%   |
| The Hague          | 1         | 1.35%   |
| Taito              | 1         | 1.35%   |
| Stara Zagora       | 1         | 1.35%   |
| Stade              | 1         | 1.35%   |
| St Petersburg      | 1         | 1.35%   |
| Singapore          | 1         | 1.35%   |
| Seoul              | 1         | 1.35%   |
| Seattle            | 1         | 1.35%   |
| SÃ£o Paulo       | 1         | 1.35%   |
| Santiago           | 1         | 1.35%   |
| Rome               | 1         | 1.35%   |
| Rio de Janeiro     | 1         | 1.35%   |
| Redmond            | 1         | 1.35%   |
| Pruszcz Gdanski    | 1         | 1.35%   |
| Pilsen             | 1         | 1.35%   |
| Perth              | 1         | 1.35%   |
| Oegstgeest         | 1         | 1.35%   |
| Odessa             | 1         | 1.35%   |
| Obninsk            | 1         | 1.35%   |
| Nughedu San Nicolo | 1         | 1.35%   |
| Nogent-sur-Marne   | 1         | 1.35%   |
| New Plymouth       | 1         | 1.35%   |
| Nampa              | 1         | 1.35%   |
| Mykolayiv          | 1         | 1.35%   |
| Monterrey          | 1         | 1.35%   |
| Monte Belo         | 1         | 1.35%   |
| Mission            | 1         | 1.35%   |
| Memphis            | 1         | 1.35%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart_bsd/drive_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 16        | 17     | 19.75%  |
| Samsung Electronics | 11        | 12     | 13.58%  |
| Toshiba             | 10        | 12     | 12.35%  |
| WDC                 | 8         | 8      | 9.88%   |
| Kingston            | 5         | 6      | 6.17%   |
| SanDisk             | 3         | 3      | 3.7%    |
| Hitachi             | 3         | 3      | 3.7%    |
| Crucial             | 3         | 3      | 3.7%    |
| HGST                | 2         | 2      | 2.47%   |
| Corsair             | 2         | 2      | 2.47%   |
| Transcend           | 1         | 1      | 1.23%   |
| SPCC                | 1         | 1      | 1.23%   |
| Plextor             | 1         | 1      | 1.23%   |
| Patriot             | 1         | 1      | 1.23%   |
| OCZ                 | 1         | 1      | 1.23%   |
| Micron Technology   | 1         | 1      | 1.23%   |
| LITEON              | 1         | 1      | 1.23%   |
| Lexar               | 1         | 1      | 1.23%   |
| Leven               | 1         | 1      | 1.23%   |
| KingSpec            | 1         | 1      | 1.23%   |
| Intel               | 1         | 1      | 1.23%   |
| Gigabyte Technology | 1         | 1      | 1.23%   |
| FORESEE             | 1         | 1      | 1.23%   |
| China               | 1         | 1      | 1.23%   |
| Apple               | 1         | 1      | 1.23%   |
| Apacer              | 1         | 1      | 1.23%   |
| AMD                 | 1         | 1      | 1.23%   |
| A-DATA Technology   | 1         | 1      | 1.23%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart_bsd/drive_model.svg)


| Model                               | Notebooks | Percent |
|-------------------------------------|-----------|---------|
| Toshiba MQ01ABF050 500GB            | 3         | 3.66%   |
| Toshiba MQ01ABD100 1TB              | 3         | 3.66%   |
| Seagate ST9500325AS 500GB           | 3         | 3.66%   |
| Seagate ST9500420AS 500GB           | 2         | 2.44%   |
| Seagate ST1000LM024 HN-M101MBB 1TB  | 2         | 2.44%   |
| SanDisk SD5SE2256G1002E 256GB       | 2         | 2.44%   |
| Samsung SSD 860 EVO 1TB             | 2         | 2.44%   |
| Samsung MZ7TE128HMGR-000L1 128GB    | 2         | 2.44%   |
| Kingston SA400S37960G 960GB         | 2         | 2.44%   |
| WDC WDS240G2G0A-00JH30 240GB        | 1         | 1.22%   |
| WDC WD5000BPKT-00PK4T0 500GB        | 1         | 1.22%   |
| WDC WD5000BEKT-60KA9T0 500GB        | 1         | 1.22%   |
| WDC WD3200BEVT-80A0RT0 320GB        | 1         | 1.22%   |
| WDC WD2500BEVS-08VAT2 250GB         | 1         | 1.22%   |
| WDC WD1600BPVT-11JJ5T0 160GB        | 1         | 1.22%   |
| WDC WD1200BEVS-07RST0 120GB         | 1         | 1.22%   |
| WDC WD10SPZX-24Z10 1TB              | 1         | 1.22%   |
| Transcend TS120GMTS420S 120GB       | 1         | 1.22%   |
| Toshiba MQ01ABD050 500GB            | 1         | 1.22%   |
| Toshiba MK5061GSYN 500GB            | 1         | 1.22%   |
| Toshiba MK3261GSYN 320GB            | 1         | 1.22%   |
| Toshiba MK1252GSX 120GB             | 1         | 1.22%   |
| SPCC Solid State Disk 1TB           | 1         | 1.22%   |
| Seagate ST9250315ASG 250GB          | 1         | 1.22%   |
| Seagate ST9160412ASG 160GB          | 1         | 1.22%   |
| Seagate ST500LT012-1DG142 500GB     | 1         | 1.22%   |
| Seagate ST500LM021-1KJ152 500GB     | 1         | 1.22%   |
| Seagate ST500LM012 HN-M500MBB 500GB | 1         | 1.22%   |
| Seagate ST320LT012-9WS14C 320GB     | 1         | 1.22%   |
| Seagate ST2000LM007-1R8174 2TB      | 1         | 1.22%   |
| Seagate ST1000LM049-2GH172 1TB      | 1         | 1.22%   |
| Seagate ST1000LM048-2E7172 1TB      | 1         | 1.22%   |
| SanDisk SSD U110 16GB               | 1         | 1.22%   |
| Samsung SSD 850 EVO 500GB           | 1         | 1.22%   |
| Samsung SSD 840 EVO 250GB           | 1         | 1.22%   |
| Samsung MZVL21T0HCLR-00BL7 1TB      | 1         | 1.22%   |
| Samsung MZNTE256HMHP-000L2 256GB    | 1         | 1.22%   |
| Samsung MZNLN512HMJP-000L7 512GB    | 1         | 1.22%   |
| Samsung MZNLN512HMJP-000H1 512GB    | 1         | 1.22%   |
| Samsung HM320II 320GB               | 1         | 1.22%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart_bsd/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 16        | 17     | 41.03%  |
| Toshiba             | 10        | 12     | 25.64%  |
| WDC                 | 7         | 7      | 17.95%  |
| Hitachi             | 3         | 3      | 7.69%   |
| HGST                | 2         | 2      | 5.13%   |
| Samsung Electronics | 1         | 1      | 2.56%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart_bsd/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 9         | 10     | 22.5%   |
| Kingston            | 5         | 6      | 12.5%   |
| SanDisk             | 3         | 3      | 7.5%    |
| Crucial             | 3         | 3      | 7.5%    |
| Corsair             | 2         | 2      | 5%      |
| WDC                 | 1         | 1      | 2.5%    |
| Transcend           | 1         | 1      | 2.5%    |
| SPCC                | 1         | 1      | 2.5%    |
| Plextor             | 1         | 1      | 2.5%    |
| Patriot             | 1         | 1      | 2.5%    |
| OCZ                 | 1         | 1      | 2.5%    |
| Micron Technology   | 1         | 1      | 2.5%    |
| LITEON              | 1         | 1      | 2.5%    |
| Lexar               | 1         | 1      | 2.5%    |
| Leven               | 1         | 1      | 2.5%    |
| KingSpec            | 1         | 1      | 2.5%    |
| Intel               | 1         | 1      | 2.5%    |
| Gigabyte Technology | 1         | 1      | 2.5%    |
| FORESEE             | 1         | 1      | 2.5%    |
| China               | 1         | 1      | 2.5%    |
| Apple               | 1         | 1      | 2.5%    |
| Apacer              | 1         | 1      | 2.5%    |
| AMD                 | 1         | 1      | 2.5%    |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart_bsd/drive_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SSD  | 37        | 42     | 48.68%  |
| HDD  | 37        | 42     | 48.68%  |
| NVMe | 2         | 2      | 2.63%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart_bsd/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 69        | 84     | 97.18%  |
| NVMe | 2         | 2      | 2.82%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart_bsd/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 56        | 67     | 76.71%  |
| 0.51-1.0   | 15        | 15     | 20.55%  |
| 1.01-2.0   | 2         | 2      | 2.74%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart_bsd/drive_space_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 1-20       | 40        | 52.63%  |
| 101-250    | 18        | 23.68%  |
| 251-500    | 11        | 14.47%  |
| 501-1000   | 6         | 7.89%   |
| 51-100     | 1         | 1.32%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart_bsd/drive_space_used.svg)


| Used GB | Notebooks | Percent |
|---------|-----------|---------|
| 1-20    | 72        | 100%    |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart_bsd/drive_malfunc.svg)


| Model                                           | Notebooks | Drives | Percent |
|-------------------------------------------------|-----------|--------|---------|
| Seagate ST9500420AS 500GB                       | 2         | 2      | 10%     |
| WDC WD3200BEVT-80A0RT0 320GB                    | 1         | 1      | 5%      |
| Toshiba MQ01ABF050 500GB                        | 1         | 2      | 5%      |
| Toshiba MQ01ABD050 500GB                        | 1         | 1      | 5%      |
| Toshiba MK5061GSYN 500GB                        | 1         | 1      | 5%      |
| Toshiba MK3261GSYN 320GB                        | 1         | 2      | 5%      |
| Toshiba MK1252GSX 120GB                         | 1         | 1      | 5%      |
| Seagate ST9500325AS 500GB                       | 1         | 1      | 5%      |
| Seagate ST500LM021-1KJ152 500GB                 | 1         | 1      | 5%      |
| Seagate ST320LT012-9WS14C 320GB                 | 1         | 1      | 5%      |
| Seagate ST1000LM048-2E7172 1TB                  | 1         | 1      | 5%      |
| Seagate ST1000LM024 HN-M101MBB 1TB              | 1         | 1      | 5%      |
| SanDisk SD5SE2256G1002E 256GB                   | 1         | 1      | 5%      |
| Micron Technology MTFDDAV256TBN-1AR15ABHA 256GB | 1         | 1      | 5%      |
| Hitachi HTS541616J9SA00 160GB                   | 1         | 1      | 5%      |
| Hitachi HTS541080G9SA00 80GB                    | 1         | 1      | 5%      |
| HGST HTS541010A9E680 1TB                        | 1         | 1      | 5%      |
| Corsair Force GT 120GB                          | 1         | 1      | 5%      |
| China SH00M128GB                                | 1         | 1      | 5%      |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart_bsd/drive_malfunc_vendor.svg)


| Vendor            | Notebooks | Drives | Percent |
|-------------------|-----------|--------|---------|
| Seagate           | 7         | 7      | 35%     |
| Toshiba           | 5         | 7      | 25%     |
| Hitachi           | 2         | 2      | 10%     |
| WDC               | 1         | 1      | 5%      |
| SanDisk           | 1         | 1      | 5%      |
| Micron Technology | 1         | 1      | 5%      |
| HGST              | 1         | 1      | 5%      |
| Corsair           | 1         | 1      | 5%      |
| China             | 1         | 1      | 5%      |

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
| HDD  | 16        | 18     | 80%     |
| SSD  | 4         | 4      | 20%     |

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
| Works   | 53        | 63     | 71.62%  |
| Malfunc | 20        | 22     | 27.03%  |
| Failed  | 1         | 1      | 1.35%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart_bsd/storage_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 66        | 90.41%  |
| AMD                   | 4         | 5.48%   |
| Samsung Electronics   | 1         | 1.37%   |
| Realtek Semiconductor | 1         | 1.37%   |
| Nvidia                | 1         | 1.37%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart_bsd/storage_model.svg)


| Model                                                                                  | Notebooks | Percent |
|----------------------------------------------------------------------------------------|-----------|---------|
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                       | 18        | 22.5%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                         | 7         | 8.75%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller           | 6         | 7.5%    |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                     | 5         | 6.25%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                                     | 4         | 5%      |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                           | 4         | 5%      |
| Intel Atom Processor E3800 Series SATA AHCI Controller                                 | 3         | 3.75%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]                  | 3         | 3.75%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                          | 3         | 3.75%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                       | 3         | 3.75%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                         | 3         | 3.75%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                                     | 2         | 2.5%    |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                      | 2         | 2.5%    |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]         | 2         | 2.5%    |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                         | 2         | 2.5%    |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                      | 2         | 2.5%    |
| AMD FCH SATA Controller [AHCI mode]                                                    | 2         | 2.5%    |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                         | 1         | 1.25%   |
| Realtek RTS5763DL NVMe SSD Controller (DRAM-less)                                      | 1         | 1.25%   |
| Nvidia MCP79 AHCI Controller                                                           | 1         | 1.25%   |
| Intel 8 Series/C220 Series Chipset Family 2-port SATA Controller 2 [IDE mode]          | 1         | 1.25%   |
| Intel 8 Series Chipset Family 4-port SATA Controller 1 [IDE mode] - Mobile             | 1         | 1.25%   |
| Intel 6 Series/C200 Series Chipset Family Mobile SATA Controller (IDE mode, ports 4-5) | 1         | 1.25%   |
| Intel 6 Series/C200 Series Chipset Family Mobile SATA Controller (IDE mode, ports 0-3) | 1         | 1.25%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA IDE Controller                          | 1         | 1.25%   |
| Intel 5 Series/3400 Series Chipset 2 port SATA IDE Controller                          | 1         | 1.25%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart_bsd/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 66        | 85.71%  |
| IDE  | 6         | 7.79%   |
| RAID | 3         | 3.9%    |
| NVMe | 2         | 2.6%    |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart_bsd/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 68        | 94.44%  |
| AMD    | 4         | 5.56%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart_bsd/cpu_model.svg)


| Model                              | Notebooks | Percent |
|------------------------------------|-----------|---------|
| Intel Core i5-3317U CPU @ 1.70GHz  | 3         | 4.17%   |
| Intel CPU Version                  | 2         | 2.78%   |
| Intel Core i7-3520M CPU @ 2.90GHz  | 2         | 2.78%   |
| Intel Core i5-5200U CPU @ 2.20GHz  | 2         | 2.78%   |
| Intel Core i5-4210U CPU @ 1.70GHz  | 2         | 2.78%   |
| Intel Core i5-3230M CPU @ 2.60GHz  | 2         | 2.78%   |
| Intel Core i5-2520M CPU @ 2.50GHz  | 2         | 2.78%   |
| Intel Core i3-3110M CPU @ 2.40GHz  | 2         | 2.78%   |
| Intel Core i3 CPU M 370 @ 2.40GHz  | 2         | 2.78%   |
| Intel Core i3 CPU M 330 @ 2.13GHz  | 2         | 2.78%   |
| Intel Processor 5Y70 CPU @ 1.10GHz | 1         | 1.39%   |
| Intel Pentium CPU N3530 @ 2.16GHz  | 1         | 1.39%   |
| Intel Pentium CPU B960 @ 2.20GHz   | 1         | 1.39%   |
| Intel Pentium CPU 5405U @ 2.30GHz  | 1         | 1.39%   |
| Intel Genuine CPU                  | 1         | 1.39%   |
| Intel Core m3-8100Y CPU @ 1.10GHz  | 1         | 1.39%   |
| Intel Core i7-7500U CPU @ 2.70GHz  | 1         | 1.39%   |
| Intel Core i7-4712MQ CPU @ 2.30GHz | 1         | 1.39%   |
| Intel Core i7-4700MQ CPU @ 2.40GHz | 1         | 1.39%   |
| Intel Core i7-3632QM CPU @ 2.20GHz | 1         | 1.39%   |
| Intel Core i7-3517U CPU @ 1.90GHz  | 1         | 1.39%   |
| Intel Core i7-2860QM CPU @ 2.50GHz | 1         | 1.39%   |
| Intel Core i7-2640M CPU @ 2.80GH   | 1         | 1.39%   |
| Intel Core i5-8350U CPU @ 1.70GHz  | 1         | 1.39%   |
| Intel Core i5-7300U CPU @ 2.60GHz  | 1         | 1.39%   |
| Intel Core i5-5300U CPU @ 2.30GHz  | 1         | 1.39%   |
| Intel Core i5-4300U CPU @ 1.90GHz  | 1         | 1.39%   |
| Intel Core i5-4300M CPU @ 2.60GHz  | 1         | 1.39%   |
| Intel Core i5-3320M CPU @ 2.60GHz  | 1         | 1.39%   |
| Intel Core i5-3210M CPU @ 2.50GHz  | 1         | 1.39%   |
| Intel Core i5-2450M CPU @ 2.50GHz  | 1         | 1.39%   |
| Intel Core i5-2410M CPU @ 2.30GHz  | 1         | 1.39%   |
| Intel Core i5 CPU M 520 @ 2.40GHz  | 1         | 1.39%   |
| Intel Core i5 CPU M 460 @ 2.53GHz  | 1         | 1.39%   |
| Intel Core i5 CPU M 450 @ 2.40GHz  | 1         | 1.39%   |
| Intel Core i3-8145U CPU @ 2.10GHz  | 1         | 1.39%   |
| Intel Core i3-6100U CPU @ 2.30GHz  | 1         | 1.39%   |
| Intel Core i3-4005U CPU @ 1.70GHz  | 1         | 1.39%   |
| Intel Core i3-3227U CPU @ 1.90GHz  | 1         | 1.39%   |
| Intel Core i3 CPU M 370 @ 2.40GH   | 1         | 1.39%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart_bsd/cpu_family.svg)


| Model            | Notebooks | Percent |
|------------------|-----------|---------|
| Intel Core i5    | 23        | 31.94%  |
| Intel Core i3    | 11        | 15.28%  |
| Intel Core i7    | 9         | 12.5%   |
| Intel Core 2 Duo | 7         | 9.72%   |
| Intel Celeron    | 6         | 8.33%   |
| Other            | 4         | 5.56%   |
| Intel Pentium    | 3         | 4.17%   |
| Intel Atom       | 3         | 4.17%   |
| AMD E            | 2         | 2.78%   |
| Intel Genuine    | 1         | 1.39%   |
| Intel Core m3    | 1         | 1.39%   |
| AMD C-60         | 1         | 1.39%   |
| AMD A6           | 1         | 1.39%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart_bsd/cpu_cores.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 55        | 76.39%  |
| 4       | 9         | 12.5%   |
| Unknown | 6         | 8.33%   |
| 1       | 2         | 2.78%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart_bsd/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 69        | 95.83%  |
| 2      | 3         | 4.17%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart_bsd/cpu_threads.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 51        | 70.83%  |
| 1       | 15        | 20.83%  |
| Unknown | 6         | 8.33%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart_bsd/cpu_microarch.svg)


| Name        | Notebooks | Percent |
|-------------|-----------|---------|
| IvyBridge   | 17        | 23.61%  |
| Westmere    | 9         | 12.5%   |
| SandyBridge | 9         | 12.5%   |
| Haswell     | 7         | 9.72%   |
| KabyLake    | 6         | 8.33%   |
| Penryn      | 5         | 6.94%   |
| Broadwell   | 4         | 5.56%   |
| Silvermont  | 3         | 4.17%   |
| Core        | 3         | 4.17%   |
| Bobcat      | 3         | 4.17%   |
| Bonnell     | 2         | 2.78%   |
| TigerLake   | 1         | 1.39%   |
| Skylake     | 1         | 1.39%   |
| Nehalem     | 1         | 1.39%   |
| Excavator   | 1         | 1.39%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart_bsd/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 59        | 74.68%  |
| Nvidia | 14        | 17.72%  |
| AMD    | 6         | 7.59%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart_bsd/gpu_model.svg)


| Model                                                                     | Notebooks | Percent |
|---------------------------------------------------------------------------|-----------|---------|
| Intel 3rd Gen Core processor Graphics Controller                          | 17        | 21.25%  |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller | 8         | 10%     |
| Intel Core Processor Integrated Graphics Controller                       | 6         | 7.5%    |
| Intel Haswell-ULT Integrated Graphics Controller                          | 4         | 5%      |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]      | 3         | 3.75%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller              | 3         | 3.75%   |
| Intel HD Graphics 5500                                                    | 3         | 3.75%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display              | 3         | 3.75%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller               | 3         | 3.75%   |
| Nvidia G84M [GeForce 8600M GT]                                            | 2         | 2.5%    |
| Intel HD Graphics 620                                                     | 2         | 2.5%    |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller   | 2         | 2.5%    |
| Nvidia GT218M [GeForce 310M]                                              | 1         | 1.25%   |
| Nvidia GK208M [GeForce GT 740M]                                           | 1         | 1.25%   |
| Nvidia GK107M [GeForce GT 640M LE]                                        | 1         | 1.25%   |
| Nvidia GF108M [GeForce GT 420M]                                           | 1         | 1.25%   |
| Nvidia GF108GLM [Quadro 1000M]                                            | 1         | 1.25%   |
| Nvidia GF106M [GeForce GTX 460M]                                          | 1         | 1.25%   |
| Nvidia GF106GLM [Quadro 2000M]                                            | 1         | 1.25%   |
| Nvidia G98M [GeForce G 105M]                                              | 1         | 1.25%   |
| Nvidia C79 [GeForce 9400M]                                                | 1         | 1.25%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                | 1         | 1.25%   |
| Intel Whiskey Lake-U GT1 [UHD Graphics 610]                               | 1         | 1.25%   |
| Intel UHD Graphics 620                                                    | 1         | 1.25%   |
| Intel UHD Graphics 615                                                    | 1         | 1.25%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                 | 1         | 1.25%   |
| Intel Skylake GT2 [HD Graphics 520]                                       | 1         | 1.25%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)       | 1         | 1.25%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)         | 1         | 1.25%   |
| Intel HD Graphics 5300                                                    | 1         | 1.25%   |
| AMD Wrestler [Radeon HD 6320]                                             | 1         | 1.25%   |
| AMD Wrestler [Radeon HD 6310]                                             | 1         | 1.25%   |
| AMD Wrestler [Radeon HD 6290]                                             | 1         | 1.25%   |
| AMD Venus PRO [Radeon HD 8850M / R9 M265X]                                | 1         | 1.25%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                  | 1         | 1.25%   |
| AMD RV730/M96 [Mobility Radeon HD 4650/5165]                              | 1         | 1.25%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart_bsd/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 46        | 63.89%  |
| 1 x Nvidia     | 8         | 11.11%  |
| 2 x Intel      | 6         | 8.33%   |
| Intel + Nvidia | 6         | 8.33%   |
| 1 x AMD        | 5         | 6.94%   |
| Intel + AMD    | 1         | 1.39%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart_bsd/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 62        | 86.11%  |
| Unknown     | 9         | 12.5%   |
| Proprietary | 1         | 1.39%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart_bsd/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 67        | 93.06%  |
| 0.01-0.5   | 4         | 5.56%   |
| 0.51-1.0   | 1         | 1.39%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart_bsd/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| LG Display              | 14        | 22.95%  |
| AU Optronics            | 10        | 16.39%  |
| Samsung Electronics     | 7         | 11.48%  |
| Chimei Innolux          | 7         | 11.48%  |
| BOE                     | 7         | 11.48%  |
| Lenovo                  | 4         | 6.56%   |
| Chi Mei Optoelectronics | 4         | 6.56%   |
| InfoVision              | 3         | 4.92%   |
| Apple                   | 2         | 3.28%   |
| KTC                     | 1         | 1.64%   |
| Hewlett-Packard         | 1         | 1.64%   |
| Fujitsu Siemens         | 1         | 1.64%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart_bsd/mon_model.svg)


| Model                                                                    | Notebooks | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| Chi Mei Optoelectronics LCD Monitor CMO15A7 1366x768 350x190mm 15.7-inch | 3         | 4.92%   |
| LG Display LCD Monitor LGD0385 1366x768 310x170mm 13.9-inch              | 2         | 3.28%   |
| LG Display LCD Monitor LGD02D8 1366x768 280x160mm 12.7-inch              | 2         | 3.28%   |
| InfoVision LCD Monitor IVO03F4 1024x600 220x130mm 10.1-inch              | 2         | 3.28%   |
| Samsung Electronics LCD Monitor SEC5742 1366x768 310x170mm 13.9-inch     | 1         | 1.64%   |
| Samsung Electronics LCD Monitor SEC414C 1366x768 310x170mm 13.9-inch     | 1         | 1.64%   |
| Samsung Electronics LCD Monitor SEC3942 1366x768 310x170mm 13.9-inch     | 1         | 1.64%   |
| Samsung Electronics LCD Monitor SEC334A 1366x768 340x190mm 15.3-inch     | 1         | 1.64%   |
| Samsung Electronics LCD Monitor SEC3143 1366x768 310x180mm 14.1-inch     | 1         | 1.64%   |
| Samsung Electronics LCD Monitor SDC4445 1366x768 340x190mm 15.3-inch     | 1         | 1.64%   |
| Samsung Electronics LCD Monitor SDC434A 3200x1800 290x170mm 13.2-inch    | 1         | 1.64%   |
| LG Display LP156WH2-TLAA LGD0230 1366x768 340x190mm 15.3-inch            | 1         | 1.64%   |
| LG Display LCD Monitor LGD11F9 1280x800 290x180mm 13.4-inch              | 1         | 1.64%   |
| LG Display LCD Monitor LGD048C 1920x1080 290x170mm 13.2-inch             | 1         | 1.64%   |
| LG Display LCD Monitor LGD0470 1920x1080 350x190mm 15.7-inch             | 1         | 1.64%   |
| LG Display LCD Monitor LGD0419 2560x1440 310x170mm 13.9-inch             | 1         | 1.64%   |
| LG Display LCD Monitor LGD03ED 1366x768 280x160mm 12.7-inch              | 1         | 1.64%   |
| LG Display LCD Monitor LGD03AB 1366x768 340x190mm 15.3-inch              | 1         | 1.64%   |
| LG Display LCD Monitor LGD0323 1920x1080 350x190mm 15.7-inch             | 1         | 1.64%   |
| LG Display LCD Monitor LGD02DC 1366x768 340x190mm 15.3-inch              | 1         | 1.64%   |
| LG Display LCD Monitor LGD021D 1600x900 380x210mm 17.1-inch              | 1         | 1.64%   |
| Lenovo LEN X24A LEN60CF 1920x1080 530x300mm 24.0-inch                    | 1         | 1.64%   |
| Lenovo LCD Monitor LEN40B2 1920x1080 340x190mm 15.3-inch                 | 1         | 1.64%   |
| Lenovo LCD Monitor LEN4050 1280x800 330x210mm 15.4-inch                  | 1         | 1.64%   |
| Lenovo LCD Monitor LEN4000 1024x768 250x180mm 12.1-inch                  | 1         | 1.64%   |
| KTC M-9005L11-D KTC1990 1280x1024 340x270mm 17.1-inch                    | 1         | 1.64%   |
| InfoVision LCD Monitor IVO057F 1920x1080 310x170mm 13.9-inch             | 1         | 1.64%   |
| Hewlett-Packard 2009 HWP2827 1600x900 440x250mm 19.9-inch                | 1         | 1.64%   |
| Fujitsu Siemens E19-5 FUS07CD 1280x1024 380x300mm 19.1-inch              | 1         | 1.64%   |
| Chimei Innolux LCD Monitor CMN15C6 1366x768 340x190mm 15.3-inch          | 1         | 1.64%   |
| Chimei Innolux LCD Monitor CMN15AB 1366x768 340x190mm 15.3-inch          | 1         | 1.64%   |
| Chimei Innolux LCD Monitor CMN1492 1366x768 310x170mm 13.9-inch          | 1         | 1.64%   |
| Chimei Innolux LCD Monitor CMN1482 1600x900 310x170mm 13.9-inch          | 1         | 1.64%   |
| Chimei Innolux LCD Monitor CMN1348 1920x1080 280x160mm 12.7-inch         | 1         | 1.64%   |
| Chimei Innolux LCD Monitor CMN1124 1920x1080 260x140mm 11.6-inch         | 1         | 1.64%   |
| Chimei Innolux LCD Monitor CMN1119 1366x768 260x140mm 11.6-inch          | 1         | 1.64%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A2 1366x768 340x190mm 15.3-inch | 1         | 1.64%   |
| BOE LCD Monitor BOE0757 1366x768 340x190mm 15.3-inch                     | 1         | 1.64%   |
| BOE LCD Monitor BOE06D3 1366x768 340x190mm 15.3-inch                     | 1         | 1.64%   |
| BOE LCD Monitor BOE06C8 1366x768 280x160mm 12.7-inch                     | 1         | 1.64%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart_bsd/mon_resolution.svg)


| Resolution        | Notebooks | Percent |
|-------------------|-----------|---------|
| 1366x768 (WXGA)   | 36        | 59.02%  |
| 1920x1080 (FHD)   | 10        | 16.39%  |
| 1600x900 (HD+)    | 5         | 8.2%    |
| 1280x800 (WXGA)   | 3         | 4.92%   |
| 1280x1024 (SXGA)  | 2         | 3.28%   |
| 1024x600          | 2         | 3.28%   |
| 3200x1800 (QHD+)  | 1         | 1.64%   |
| 2560x1440 (QHD)   | 1         | 1.64%   |
| 1920x1200 (WUXGA) | 1         | 1.64%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart_bsd/mon_diagonal.svg)


| Inches | Notebooks | Percent |
|--------|-----------|---------|
| 15     | 22        | 36.07%  |
| 13     | 17        | 27.87%  |
| 12     | 6         | 9.84%   |
| 11     | 5         | 8.2%    |
| 17     | 3         | 4.92%   |
| 10     | 3         | 4.92%   |
| 19     | 2         | 3.28%   |
| 24     | 1         | 1.64%   |
| 23     | 1         | 1.64%   |
| 14     | 1         | 1.64%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart_bsd/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 36        | 60%     |
| 201-300     | 18        | 30%     |
| 351-400     | 3         | 5%      |
| 501-600     | 2         | 3.33%   |
| 401-500     | 1         | 1.67%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart_bsd/mon_ratio.svg)


| Ratio | Notebooks | Percent |
|-------|-----------|---------|
| 16/9  | 54        | 90%     |
| 16/10 | 4         | 6.67%   |
| 5/4   | 2         | 3.33%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart_bsd/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 81-90          | 16        | 26.23%  |
| 91-100         | 14        | 22.95%  |
| 101-110        | 8         | 13.11%  |
| 61-70          | 6         | 9.84%   |
| 51-60          | 5         | 8.2%    |
| 41-50          | 3         | 4.92%   |
| 71-80          | 2         | 3.28%   |
| 201-250        | 2         | 3.28%   |
| 151-200        | 2         | 3.28%   |
| 121-130        | 2         | 3.28%   |
| 141-150        | 1         | 1.64%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart_bsd/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 101-120       | 28        | 46.67%  |
| 121-160       | 16        | 26.67%  |
| 51-100        | 10        | 16.67%  |
| 161-240       | 5         | 8.33%   |
| More than 240 | 1         | 1.67%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart_bsd/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 58        | 80.56%  |
| 0     | 11        | 15.28%  |
| 2     | 3         | 4.17%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart_bsd/net_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 33        | 28.95%  |
| Realtek Semiconductor             | 29        | 25.44%  |
| Qualcomm Atheros                  | 20        | 17.54%  |
| Broadcom                          | 15        | 13.16%  |
| Marvell Technology Group          | 3         | 2.63%   |
| JMicron Technology                | 3         | 2.63%   |
| Ericsson Business Mobile Networks | 3         | 2.63%   |
| Ralink                            | 2         | 1.75%   |
| Huawei Technologies               | 2         | 1.75%   |
| Xiaomi                            | 1         | 0.88%   |
| Sierra Wireless                   | 1         | 0.88%   |
| Nvidia                            | 1         | 0.88%   |
| Google                            | 1         | 0.88%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart_bsd/net_model.svg)


| Model                                                                       | Notebooks | Percent |
|-----------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller           | 14        | 9.59%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                       | 8         | 5.48%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                            | 6         | 4.11%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                       | 6         | 4.11%   |
| Intel Wireless 7265                                                         | 5         | 3.42%   |
| Realtek RTL8188EE Wireless Network Adapter                                  | 4         | 2.74%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)              | 4         | 2.74%   |
| Intel Wireless 7260                                                         | 4         | 2.74%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                                  | 3         | 2.05%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                                | 3         | 2.05%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                         | 2         | 1.37%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                  | 2         | 1.37%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                                      | 2         | 1.37%   |
| Qualcomm Atheros AR8162 Fast Ethernet                                       | 2         | 1.37%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                                    | 2         | 1.37%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                                    | 2         | 1.37%   |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller                     | 2         | 1.37%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller                      | 2         | 1.37%   |
| Intel Wireless 8265 / 8275                                                  | 2         | 1.37%   |
| Intel Ethernet Connection I217-LM                                           | 2         | 1.37%   |
| Intel Ethernet Connection (4) I219-LM                                       | 2         | 1.37%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                                | 2         | 1.37%   |
| Intel Centrino Ultimate-N 6300                                              | 2         | 1.37%   |
| Intel Centrino Advanced-N 6235                                              | 2         | 1.37%   |
| Intel 82577LC Gigabit Network Connection                                    | 2         | 1.37%   |
| Ericsson Business Mobile Networks F5521 gw Mobile Broadband Serial Port III | 2         | 1.37%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                             | 2         | 1.37%   |
| Broadcom BCM4321 802.11a/b/g/n                                              | 2         | 1.37%   |
| Broadcom BCM43142 802.11b/g/n                                               | 2         | 1.37%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                         | 2         | 1.37%   |
| Xiaomi Mi/Redmi series (RNDIS)                                              | 1         | 0.68%   |
| Sierra Wireless EM7345 4G LTE                                               | 1         | 0.68%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter                    | 1         | 0.68%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                    | 1         | 0.68%   |
| Realtek RTL8723DE Wireless Network Adapter                                  | 1         | 0.68%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                             | 1         | 0.68%   |
| Realtek Realtek Bluetooth 4.2 Adapter                                       | 1         | 0.68%   |
| Ralink RT3592 Wireless 802.11abgn 2T/2R PCIe                                | 1         | 0.68%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                                   | 1         | 0.68%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)              | 1         | 0.68%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart_bsd/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 30        | 41.67%  |
| Qualcomm Atheros      | 15        | 20.83%  |
| Realtek Semiconductor | 12        | 16.67%  |
| Broadcom              | 12        | 16.67%  |
| Ralink                | 2         | 2.78%   |
| Sierra Wireless       | 1         | 1.39%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart_bsd/net_wireless_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 6         | 8%      |
| Intel Wireless 7265                                                     | 5         | 6.67%   |
| Realtek RTL8188EE Wireless Network Adapter                              | 4         | 5.33%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 4         | 5.33%   |
| Intel Wireless 7260                                                     | 4         | 5.33%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 3         | 4%      |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 3         | 4%      |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 2         | 2.67%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 2         | 2.67%   |
| Intel Wireless 8265 / 8275                                              | 2         | 2.67%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                            | 2         | 2.67%   |
| Intel Centrino Ultimate-N 6300                                          | 2         | 2.67%   |
| Intel Centrino Advanced-N 6235                                          | 2         | 2.67%   |
| Broadcom BCM4321 802.11a/b/g/n                                          | 2         | 2.67%   |
| Broadcom BCM43142 802.11b/g/n                                           | 2         | 2.67%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 2         | 2.67%   |
| Sierra Wireless EM7345 4G LTE                                           | 1         | 1.33%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter                | 1         | 1.33%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 1         | 1.33%   |
| Realtek RTL8723DE Wireless Network Adapter                              | 1         | 1.33%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 1         | 1.33%   |
| Realtek Realtek Bluetooth 4.2 Adapter                                   | 1         | 1.33%   |
| Ralink RT3592 Wireless 802.11abgn 2T/2R PCIe                            | 1         | 1.33%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                               | 1         | 1.33%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 1         | 1.33%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)          | 1         | 1.33%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 1         | 1.33%   |
| Intel Wireless 8260                                                     | 1         | 1.33%   |
| Intel Wireless 3160                                                     | 1         | 1.33%   |
| Intel WiFi Link 5100                                                    | 1         | 1.33%   |
| Intel Wi-Fi 6 AX201                                                     | 1         | 1.33%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection                 | 1         | 1.33%   |
| Intel Centrino Wireless-N 6150                                          | 1         | 1.33%   |
| Intel Centrino Wireless-N 2200                                          | 1         | 1.33%   |
| Intel Centrino Wireless-N 135                                           | 1         | 1.33%   |
| Intel Centrino Wireless-N 1030 [Rainbow Peak]                           | 1         | 1.33%   |
| Intel Centrino WiMAX 6150                                               | 1         | 1.33%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 1         | 1.33%   |
| Broadcom BCM4360 802.11ac Dual Band Wireless Network Adapter            | 1         | 1.33%   |
| Broadcom BCM4331 802.11a/b/g/n                                          | 1         | 1.33%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart_bsd/net_ethernet_vendor.svg)


| Vendor                   | Notebooks | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 22        | 32.84%  |
| Intel                    | 18        | 26.87%  |
| Qualcomm Atheros         | 12        | 17.91%  |
| Broadcom                 | 5         | 7.46%   |
| Marvell Technology Group | 3         | 4.48%   |
| JMicron Technology       | 3         | 4.48%   |
| Xiaomi                   | 1         | 1.49%   |
| Nvidia                   | 1         | 1.49%   |
| Huawei Technologies      | 1         | 1.49%   |
| Google                   | 1         | 1.49%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart_bsd/net_ethernet_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller              | 14        | 20.9%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                          | 8         | 11.94%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)                          | 6         | 8.96%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                                         | 2         | 2.99%   |
| Qualcomm Atheros AR8162 Fast Ethernet                                          | 2         | 2.99%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                                       | 2         | 2.99%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                                       | 2         | 2.99%   |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller                        | 2         | 2.99%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller                         | 2         | 2.99%   |
| Intel Ethernet Connection I217-LM                                              | 2         | 2.99%   |
| Intel Ethernet Connection (4) I219-LM                                          | 2         | 2.99%   |
| Intel 82577LC Gigabit Network Connection                                       | 2         | 2.99%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                                | 2         | 2.99%   |
| Xiaomi Mi/Redmi series (RNDIS)                                                 | 1         | 1.49%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                                     | 1         | 1.49%   |
| Qualcomm Atheros AR8152 v1.1 Fast Ethernet                                     | 1         | 1.49%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                  | 1         | 1.49%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                          | 1         | 1.49%   |
| Nvidia MCP79 Ethernet                                                          | 1         | 1.49%   |
| Marvell Group Yukon Optima 88E8059 [PCIe Gigabit Ethernet Controller with AVB] | 1         | 1.49%   |
| JMicron JMC260 PCI Express Fast Ethernet Controller                            | 1         | 1.49%   |
| Intel Ethernet Connection I219-V                                               | 1         | 1.49%   |
| Intel Ethernet Connection I218-LM                                              | 1         | 1.49%   |
| Intel Ethernet Connection (3) I218-V                                           | 1         | 1.49%   |
| Intel Ethernet Connection (3) I218-LM                                          | 1         | 1.49%   |
| Intel 82567LM Gigabit Network Connection                                       | 1         | 1.49%   |
| Intel 82566MM Gigabit Network Connection                                       | 1         | 1.49%   |
| Huawei USB Device                                                              | 1         | 1.49%   |
| Google Nexus/Pixel Device (tether)                                             | 1         | 1.49%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                              | 1         | 1.49%   |
| Broadcom NetLink BCM5906M Fast Ethernet PCI Express                            | 1         | 1.49%   |
| Broadcom NetLink BCM5787M Gigabit Ethernet PCI Express                         | 1         | 1.49%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart_bsd/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 70        | 50.36%  |
| Ethernet | 65        | 46.76%  |
| Modem    | 2         | 1.44%   |
| Unknown  | 2         | 1.44%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart_bsd/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| Ethernet | 61        | 50.83%  |
| WiFi     | 56        | 46.67%  |
| Unknown  | 2         | 1.67%   |
| Modem    | 1         | 0.83%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart_bsd/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 61        | 84.72%  |
| 1     | 11        | 15.28%  |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart_bsd/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 70        | 97.22%  |
| Yes  | 2         | 2.78%   |

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
| Apple Bluetooth Host Controller                     | 2         | 5.41%   |
| Realtek Wireless Bluetooth Adapter                  | 1         | 2.7%    |
| Realtek RTL8723B Bluetooth                          | 1         | 2.7%    |
| Realtek Bluetooth Adapter                           | 1         | 2.7%    |
| Ralink RT3290 Bluetooth                             | 1         | 2.7%    |
| Qualcomm Atheros AR9462 Bluetooth                   | 1         | 2.7%    |
| Intel Centrino Advanced-N 6230 Bluetooth adapter    | 1         | 2.7%    |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 1         | 2.7%    |
| Intel AX201 Bluetooth                               | 1         | 2.7%    |
| HP Broadcom 2070 Bluetooth Combo                    | 1         | 2.7%    |
| Foxconn / Hon Hai Broadcom BCM20702 Bluetooth       | 1         | 2.7%    |
| Foxconn / Hon Hai Atheros AR3012 Bluetooth          | 1         | 2.7%    |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 1         | 2.7%    |
| Broadcom Bluetooth 4.0                              | 1         | 2.7%    |
| Broadcom BCM2046 Bluetooth Device                   | 1         | 2.7%    |
| Broadcom BCM2045B (BDC-2.1)                         | 1         | 2.7%    |
| Apple Built-in Bluetooth 2.0+EDR HCI                | 1         | 2.7%    |
| Apple Broadcom Built-in Bluetooth                   | 1         | 2.7%    |
| Apple Bluetooth HCI                                 | 1         | 2.7%    |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart_bsd/snd_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 67        | 85.9%   |
| Nvidia | 5         | 6.41%   |
| AMD    | 5         | 6.41%   |
| XMOS   | 1         | 1.28%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart_bsd/snd_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 19        | 20.65%  |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 10        | 10.87%  |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 7         | 7.61%   |
| Intel Sunrise Point-LP HD Audio                                            | 5         | 5.43%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 4         | 4.35%   |
| Intel Broadwell-U Audio Controller                                         | 4         | 4.35%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 4         | 4.35%   |
| Intel 8 Series HD Audio Controller                                         | 4         | 4.35%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 3         | 3.26%   |
| Intel Haswell-ULT HD Audio Controller                                      | 3         | 3.26%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller | 3         | 3.26%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                             | 3         | 3.26%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 3         | 3.26%   |
| AMD Wrestler HDMI Audio                                                    | 3         | 3.26%   |
| Nvidia GF108 High Definition Audio Controller                              | 2         | 2.17%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 2         | 2.17%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 2         | 2.17%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 2         | 2.17%   |
| XMOS USB Audio                                                             | 1         | 1.09%   |
| Nvidia MCP79 High Definition Audio                                         | 1         | 1.09%   |
| Nvidia High Definition Audio Controller                                    | 1         | 1.09%   |
| Nvidia GF106 High Definition Audio Controller                              | 1         | 1.09%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 1         | 1.09%   |
| AMD RV710/730 HDMI Audio [Radeon HD 4000 series]                           | 1         | 1.09%   |
| AMD High Definition Audio Controller                                       | 1         | 1.09%   |
| AMD FCH Azalia Controller                                                  | 1         | 1.09%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                           | 1         | 1.09%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart_bsd/memory_vendor.svg)


| Vendor                       | Notebooks | Percent |
|------------------------------|-----------|---------|
| SK hynix                     | 21        | 23.08%  |
| Samsung Electronics          | 17        | 18.68%  |
| Unknown                      | 9         | 9.89%   |
| Micron Technology            | 9         | 9.89%   |
| Kingston                     | 8         | 8.79%   |
| Teikon                       | 3         | 3.3%    |
| Smart                        | 3         | 3.3%    |
| Nanya Technology             | 3         | 3.3%    |
| Elpida                       | 3         | 3.3%    |
| Team                         | 2         | 2.2%    |
| Ramaxel Technology           | 2         | 2.2%    |
| Apacer                       | 2         | 2.2%    |
| Unknown                      | 2         | 2.2%    |
| Unknown (0x7F7F7F94FFFFFFFF) | 1         | 1.1%    |
| Smart Brazil                 | 1         | 1.1%    |
| SHARETRONIC                  | 1         | 1.1%    |
| PKI/Kingston                 | 1         | 1.1%    |
| Crucial                      | 1         | 1.1%    |
| ASint Technology             | 1         | 1.1%    |
| A-DATA Technology            | 1         | 1.1%    |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart_bsd/memory_model.svg)


| Model                                                           | Notebooks | Percent |
|-----------------------------------------------------------------|-----------|---------|
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                      | 3         | 3.19%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s          | 2         | 2.13%   |
| SK hynix RAM HMT351S6EFR8A-PB 4GB SODIMM DDR3 1600MT/s          | 2         | 2.13%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s          | 2         | 2.13%   |
| SK hynix RAM HMT325S6BFR8C-H9 2GB SODIMM DDR3 1333MT/s          | 2         | 2.13%   |
| Samsung RAM M471B5673FH0-CH9 2GB SODIMM DDR3 1334MT/s           | 2         | 2.13%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s           | 2         | 2.13%   |
| Nanya RAM NT2GC64B8HA1NS-BE 2GB SODIMM DDR3 1067MT/s            | 2         | 2.13%   |
| Unknown                                                         | 2         | 2.13%   |
| Unknown RAM Module 4GB SODIMM DDR3 1600MT/s                     | 1         | 1.06%   |
| Unknown RAM Module 4GB SODIMM DDR3 1333MT/s                     | 1         | 1.06%   |
| Unknown RAM Module 4GB SODIMM DDR3                              | 1         | 1.06%   |
| Unknown RAM Module 4GB SODIMM DDR2 800MT/s                      | 1         | 1.06%   |
| Unknown RAM Module 4GB DIMM DDR3 1067MT/s                       | 1         | 1.06%   |
| Unknown RAM Module 2GB SODIMM DDR3                              | 1         | 1.06%   |
| Unknown (0x7F7F7F94FFFFFFFF) RAM Module 2GB SODIMM DDR2 667MT/s | 1         | 1.06%   |
| Teikon RAM TMT451S6BFR8A-PBHC 4GB SODIMM DDR3 1333MT/s          | 1         | 1.06%   |
| Teikon RAM TMT41GS6BFR8A-PBSC 8GB SODIMM DDR3 1600MT/s          | 1         | 1.06%   |
| Teikon RAM TMT225S6FR8C-H9HC 2GB SODIMM DDR3 1334MT/s           | 1         | 1.06%   |
| Team RAM TEAMGROUP-SD3-1066 4GB SODIMM DDR3 1067MT/s            | 1         | 1.06%   |
| Team RAM Elite-1333 4GB SODIMM DDR3 1333MT/s                    | 1         | 1.06%   |
| Smart RAM SH564568FH8NZPHSCR 2GB SODIMM DDR3 1334MT/s           | 1         | 1.06%   |
| Smart RAM SH564128FJ8NWRNSQG 4GB SODIMM DDR3 1600MT/s           | 1         | 1.06%   |
| Smart RAM SH564128FH8NZPHSCR 4GB SODIMM DDR3 1333MT/s           | 1         | 1.06%   |
| Smart Brazil RAM SF4641G8CK8IEHLSBG 8GB SODIMM DDR4 2133MT/s    | 1         | 1.06%   |
| SK hynix RAM Module 8GB SODIMM DDR4 2400MT/s                    | 1         | 1.06%   |
| SK hynix RAM Module 8GB Row Of Chips LPDDR3 1600MT/s            | 1         | 1.06%   |
| SK hynix RAM Module 4GB SODIMM DDR3 1067MT/s                    | 1         | 1.06%   |
| SK hynix RAM Module 2GB SODIMM DDR3 1600MT/s                    | 1         | 1.06%   |
| SK hynix RAM HMT451S6AFR8C-PB 4GB SODIMM DDR3 1600MT/s          | 1         | 1.06%   |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s          | 1         | 1.06%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s          | 1         | 1.06%   |
| SK hynix RAM HMT41GS6AFR8A-PB 8GB SODIMM DDR3 1600MT/s          | 1         | 1.06%   |
| SK hynix RAM HMT351S6EFR8C-PB 4GB SODIMM DDR3 1600MT/s          | 1         | 1.06%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1333MT/s          | 1         | 1.06%   |
| SK hynix RAM HMT351S6CFR8C-H9 4GB SODIMM DDR3 1333MT/s          | 1         | 1.06%   |
| SK hynix RAM HMT351S6CFR8A-PB 4GB SODIMM DDR3 1600MT/s          | 1         | 1.06%   |
| SK hynix RAM HMT351S6CFR8A-PB 4GB SODIMM DDR3 1333MT/s          | 1         | 1.06%   |
| SK hynix RAM HMT351S6BFR8C-H9 4GB SODIMM DDR3 1333MT/s          | 1         | 1.06%   |
| SHARETRONIC RAM Module 2GB SODIMM DDR3 1600MT/s                 | 1         | 1.06%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart_bsd/memory_kind.svg)


| Kind   | Notebooks | Percent |
|--------|-----------|---------|
| DDR3   | 55        | 78.57%  |
| DDR4   | 6         | 8.57%   |
| DDR2   | 6         | 8.57%   |
| LPDDR3 | 2         | 2.86%   |
| LPDDR4 | 1         | 1.43%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart_bsd/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 66        | 94.29%  |
| Row Of Chips | 2         | 2.86%   |
| DIMM         | 1         | 1.43%   |
| Chip         | 1         | 1.43%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart_bsd/memory_size.svg)


| Size | Notebooks | Percent |
|------|-----------|---------|
| 4096 | 38        | 46.34%  |
| 2048 | 27        | 32.93%  |
| 8192 | 17        | 20.73%  |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart_bsd/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 1600    | 30        | 37.97%  |
| 1333    | 14        | 17.72%  |
| 1067    | 11        | 13.92%  |
| 1334    | 7         | 8.86%   |
| 667     | 5         | 6.33%   |
| 2667    | 2         | 2.53%   |
| 2400    | 2         | 2.53%   |
| 2133    | 2         | 2.53%   |
| Unknown | 2         | 2.53%   |
| 4267    | 1         | 1.27%   |
| 1867    | 1         | 1.27%   |
| 1066    | 1         | 1.27%   |
| 800     | 1         | 1.27%   |

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
| Chicony Electronics                    | 16        | 30.77%  |
| Bison Electronics                      | 8         | 15.38%  |
| Sunplus Innovation Technology          | 4         | 7.69%   |
| Microdia                               | 4         | 7.69%   |
| Realtek Semiconductor                  | 3         | 5.77%   |
| Cheng Uei Precision Industry (Foxlink) | 3         | 5.77%   |
| Suyin                                  | 2         | 3.85%   |
| Importek                               | 2         | 3.85%   |
| IMC Networks                           | 2         | 3.85%   |
| Apple                                  | 2         | 3.85%   |
| Tripath Technology                     | 1         | 1.92%   |
| Syntek                                 | 1         | 1.92%   |
| Lite-On Technology                     | 1         | 1.92%   |
| Lenovo                                 | 1         | 1.92%   |
| Foxconn / Hon Hai                      | 1         | 1.92%   |
| ALi                                    | 1         | 1.92%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart_bsd/camera_model.svg)


| Model                                                          | Notebooks | Percent |
|----------------------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                                      | 8         | 15.38%  |
| Bison Lenovo EasyCamera                                        | 3         | 5.77%   |
| Bison Integrated Camera                                        | 3         | 5.77%   |
| Realtek USB 2.0 PC Camera                                      | 2         | 3.85%   |
| Tripath 2M Front Camera                                        | 1         | 1.92%   |
| Syntek EasyCamera                                              | 1         | 1.92%   |
| Suyin Integrated_Webcam_HD                                     | 1         | 1.92%   |
| Suyin 1.3M WebCam (notebook emachines E730, Acer sub-brand)    | 1         | 1.92%   |
| Sunplus Lenovo EasyCamera                                      | 1         | 1.92%   |
| Sunplus Laptop_Integrated_Webcam_FHD                           | 1         | 1.92%   |
| Sunplus Integrated Camera                                      | 1         | 1.92%   |
| Sunplus HP Universal Camera                                    | 1         | 1.92%   |
| Realtek Dell EasyCamera                                        | 1         | 1.92%   |
| Microdia Webcam                                                | 1         | 1.92%   |
| Microdia Laptop_Integrated_Webcam_2M                           | 1         | 1.92%   |
| Microdia Integrated Webcam HD                                  | 1         | 1.92%   |
| Microdia Dell Laptop Integrated Webcam HD                      | 1         | 1.92%   |
| Lite-On Integrated Camera                                      | 1         | 1.92%   |
| Lenovo Integrated Webcam                                       | 1         | 1.92%   |
| Importek TOSHIBA HD Web Camera                                 | 1         | 1.92%   |
| Importek HP Webcam                                             | 1         | 1.92%   |
| IMC Networks USB 2.0 UVC HD Webcam                             | 1         | 1.92%   |
| IMC Networks 2M Integrated Webcam                              | 1         | 1.92%   |
| Foxconn / Hon Hai USB2.0 Camera                                | 1         | 1.92%   |
| Chicony WebCam                                                 | 1         | 1.92%   |
| Chicony USB2.0 HD UVC WebCam                                   | 1         | 1.92%   |
| Chicony USB Video Device                                       | 1         | 1.92%   |
| Chicony Sony Visual Communication Camera                       | 1         | 1.92%   |
| Chicony Lenovo Integrated Camera (0.3MP)                       | 1         | 1.92%   |
| Chicony Lenovo EasyCamera                                      | 1         | 1.92%   |
| Chicony Asus 720p CMOS webcam                                  | 1         | 1.92%   |
| Chicony 1.3M Webcam                                            | 1         | 1.92%   |
| Cheng Uei Precision Industry (Foxlink) HP Webcam-101           | 1         | 1.92%   |
| Cheng Uei Precision Industry (Foxlink) HP Universal Camera     | 1         | 1.92%   |
| Cheng Uei Precision Industry (Foxlink) HP TrueVision HD Camera | 1         | 1.92%   |
| Bison ThinkPad Integrated Camera                               | 1         | 1.92%   |
| Bison HD Webcam                                                | 1         | 1.92%   |
| Apple FaceTime HD Camera (Built-in)                            | 1         | 1.92%   |
| Apple FaceTime HD Camera                                       | 1         | 1.92%   |
| ALi WebCam                                                     | 1         | 1.92%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart_bsd/fingerprint_vendor.svg)


| Vendor             | Notebooks | Percent |
|--------------------|-----------|---------|
| Validity Sensors   | 7         | 50%     |
| Upek               | 3         | 21.43%  |
| AuthenTec          | 3         | 21.43%  |
| STMicroelectronics | 1         | 7.14%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart_bsd/fingerprint_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Validity Sensors VFS 5011 fingerprint sensor                               | 4         | 28.57%  |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 3         | 21.43%  |
| Validity Sensors VFS301 Fingerprint Reader                                 | 1         | 7.14%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 1         | 7.14%   |
| Validity Sensors Fingerprint scanner                                       | 1         | 7.14%   |
| STMicroelectronics Fingerprint Reader                                      | 1         | 7.14%   |
| AuthenTec AES2810                                                          | 1         | 7.14%   |
| AuthenTec AES1660                                                          | 1         | 7.14%   |
| AuthenTec AES1600                                                          | 1         | 7.14%   |

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
| 2     | 22        | 30.56%  |
| 1     | 21        | 29.17%  |
| 3     | 12        | 16.67%  |
| 0     | 12        | 16.67%  |
| 4     | 5         | 6.94%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart_bsd/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Communication controller | 52        | 44.44%  |
| Card reader              | 23        | 19.66%  |
| Fingerprint reader       | 14        | 11.97%  |
| Net/wireless             | 13        | 11.11%  |
| Firewire controller      | 6         | 5.13%   |
| Bluetooth                | 6         | 5.13%   |
| Storage                  | 2         | 1.71%   |
| Network                  | 1         | 0.85%   |

