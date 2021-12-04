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

| Vendor    | Model                       | Probe                                                     | Date         |
|-----------|-----------------------------|-----------------------------------------------------------|--------------|
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
| amd64 | 54        | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart_bsd/os_de.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| helloDesktop | 53        | 98.15%  |
| XFCE         | 1         | 1.85%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart_bsd/os_display_server.svg)


| Name | Notebooks | Percent |
|------|-----------|---------|
| X11  | 54        | 100%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart_bsd/os_display_manager.svg)


| Name | Notebooks | Percent |
|------|-----------|---------|
| SLiM | 54        | 100%    |

OS Lang
-------

Language

![OS Lang](./images/pie_chart_bsd/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| en_US   | 51        | 94.44%  |
| ru_RU   | 1         | 1.85%   |
| de_DE   | 1         | 1.85%   |
| Unknown | 1         | 1.85%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart_bsd/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 43        | 78.18%  |
| BIOS | 12        | 21.82%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart_bsd/os_filesystem.svg)


| Type | Notebooks | Percent |
|------|-----------|---------|
| Zfs  | 54        | 100%    |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart_bsd/os_part_scheme.svg)


| Type | Notebooks | Percent |
|------|-----------|---------|
| GPT  | 54        | 100%    |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart_bsd/node_vendor.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| Lenovo           | 20        | 37.04%  |
| Hewlett-Packard  | 8         | 14.81%  |
| Dell             | 8         | 14.81%  |
| Toshiba          | 3         | 5.56%   |
| ASUSTek Computer | 3         | 5.56%   |
| Apple            | 3         | 5.56%   |
| Acer             | 2         | 3.7%    |
| Sony             | 1         | 1.85%   |
| Semp Toshiba     | 1         | 1.85%   |
| MSI              | 1         | 1.85%   |
| Kraftway         | 1         | 1.85%   |
| Itautec          | 1         | 1.85%   |
| eMachines        | 1         | 1.85%   |
| Chuwi            | 1         | 1.85%   |

Model
-----

Motherboard model

![Model](./images/pie_chart_bsd/node_model.svg)


| Name                                       | Notebooks | Percent |
|--------------------------------------------|-----------|---------|
| Toshiba Satellite S55t-B                   | 1         | 1.85%   |
| Toshiba PORTEGE M780                       | 1         | 1.85%   |
| Toshiba dynabook RX3 SM240E/3HD            | 1         | 1.85%   |
| Sony SVS1511AJB                            | 1         | 1.85%   |
| Semp Toshiba STI NA 1401                   | 1         | 1.85%   |
| MSI MS-16F1                                | 1         | 1.85%   |
| Lenovo Yoga 3 Pro-1370 80HE                | 1         | 1.85%   |
| Lenovo ThinkPad Yoga 11e 20DAS0AE00        | 1         | 1.85%   |
| Lenovo ThinkPad X250 20CLS2A11K            | 1         | 1.85%   |
| Lenovo ThinkPad X230 2325IG2               | 1         | 1.85%   |
| Lenovo ThinkPad X230 23062S2               | 1         | 1.85%   |
| Lenovo ThinkPad X1 Carbon Gen 9 20XWA003CD | 1         | 1.85%   |
| Lenovo ThinkPad X1 Carbon 2nd 20A70066UK   | 1         | 1.85%   |
| Lenovo ThinkPad W520 4276CTO               | 1         | 1.85%   |
| Lenovo ThinkPad T450s 20BX001PUS           | 1         | 1.85%   |
| Lenovo ThinkPad T430u 3352AA5              | 1         | 1.85%   |
| Lenovo ThinkPad T420 4180EE8               | 1         | 1.85%   |
| Lenovo ThinkPad SL 2746M3C                 | 1         | 1.85%   |
| Lenovo ThinkPad R500 2718W92               | 1         | 1.85%   |
| Lenovo ThinkPad L440 20ASS0FP00            | 1         | 1.85%   |
| Lenovo ThinkPad 13 20GJCTO1WW              | 1         | 1.85%   |
| Lenovo S20-30 Touch 20434                  | 1         | 1.85%   |
| Lenovo IdeaPad Z360                        | 1         | 1.85%   |
| Lenovo IdeaPad S145-15IWL 81MV             | 1         | 1.85%   |
| Lenovo G500s 20245                         | 1         | 1.85%   |
| Lenovo B590 62743PG                        | 1         | 1.85%   |
| Kraftway KW10T                             | 1         | 1.85%   |
| Itautec Infoway w7530                      | 1         | 1.85%   |
| HP Presario CQ43                           | 1         | 1.85%   |
| HP Pavilion dm4                            | 1         | 1.85%   |
| HP Laptop 15-db0xxx                        | 1         | 1.85%   |
| HP EliteBook 840 G5                        | 1         | 1.85%   |
| HP EliteBook 2560p                         | 1         | 1.85%   |
| HP 15                                      | 1         | 1.85%   |
| HP 14                                      | 1         | 1.85%   |
| eMachines eM350                            | 1         | 1.85%   |
| Dell Studio 1747                           | 1         | 1.85%   |
| Dell Precision M4600                       | 1         | 1.85%   |
| Dell Latitude E4300                        | 1         | 1.85%   |
| Dell Latitude 7280                         | 1         | 1.85%   |
| Dell Latitude 3540                         | 1         | 1.85%   |
| Dell Inspiron 5566                         | 1         | 1.85%   |
| Dell Inspiron 3542                         | 1         | 1.85%   |
| Dell Inspiron 3521                         | 1         | 1.85%   |
| Chuwi MiniBook                             | 1         | 1.85%   |
| ASUS X540LA                                | 1         | 1.85%   |
| ASUS UX21A                                 | 1         | 1.85%   |
| ASUS U33Jc                                 | 1         | 1.85%   |
| Apple MacBookPro9,2                        | 1         | 1.85%   |
| Apple MacBookPro4,1                        | 1         | 1.85%   |
| Apple MacBookAir5,1                        | 1         | 1.85%   |
| Acer Aspire 5742G                          | 1         | 1.85%   |
| Acer Aspire 5741                           | 1         | 1.85%   |
| Unknown                                    | 1         | 1.85%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart_bsd/node_model_family.svg)


| Name              | Notebooks | Percent |
|-------------------|-----------|---------|
| Lenovo ThinkPad   | 14        | 25.93%  |
| Dell Latitude     | 3         | 5.56%   |
| Dell Inspiron     | 3         | 5.56%   |
| Lenovo IdeaPad    | 2         | 3.7%    |
| HP EliteBook      | 2         | 3.7%    |
| Acer Aspire       | 2         | 3.7%    |
| Toshiba Satellite | 1         | 1.85%   |
| Toshiba PORTEGE   | 1         | 1.85%   |
| Toshiba dynabook  | 1         | 1.85%   |
| Sony SVS1511AJB   | 1         | 1.85%   |
| Semp Toshiba STI  | 1         | 1.85%   |
| MSI MS-16F1       | 1         | 1.85%   |
| Lenovo Yoga       | 1         | 1.85%   |
| Lenovo S20-30     | 1         | 1.85%   |
| Lenovo G500s      | 1         | 1.85%   |
| Lenovo B590       | 1         | 1.85%   |
| Kraftway KW10T    | 1         | 1.85%   |
| Itautec Infoway   | 1         | 1.85%   |
| HP Presario       | 1         | 1.85%   |
| HP Pavilion       | 1         | 1.85%   |
| HP Laptop         | 1         | 1.85%   |
| HP 15             | 1         | 1.85%   |
| HP 14             | 1         | 1.85%   |
| eMachines eM350   | 1         | 1.85%   |
| Dell Studio       | 1         | 1.85%   |
| Dell Precision    | 1         | 1.85%   |
| Chuwi MiniBook    | 1         | 1.85%   |
| ASUS X540LA       | 1         | 1.85%   |
| ASUS UX21A        | 1         | 1.85%   |
| ASUS U33Jc        | 1         | 1.85%   |
| Apple MacBookPro9 | 1         | 1.85%   |
| Apple MacBookPro4 | 1         | 1.85%   |
| Apple MacBookAir5 | 1         | 1.85%   |
| Unknown           | 1         | 1.85%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart_bsd/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2019 | 7         | 12.96%  |
| 2011 | 6         | 11.11%  |
| 2020 | 5         | 9.26%   |
| 2018 | 5         | 9.26%   |
| 2014 | 5         | 9.26%   |
| 2013 | 5         | 9.26%   |
| 2012 | 5         | 9.26%   |
| 2010 | 5         | 9.26%   |
| 2021 | 4         | 7.41%   |
| 2015 | 3         | 5.56%   |
| 2016 | 2         | 3.7%    |
| 2009 | 1         | 1.85%   |
| 2008 | 1         | 1.85%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart_bsd/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 54        | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart_bsd/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 54        | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart_bsd/node_ram_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 4.01-8.0   | 26        | 48.15%  |
| 8.01-16.0  | 21        | 38.89%  |
| 16.01-24.0 | 6         | 11.11%  |
| 2.01-3.0   | 1         | 1.85%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart_bsd/node_ram_used.svg)


| Used GB  | Notebooks | Percent |
|----------|-----------|---------|
| 0.01-0.5 | 41        | 75.93%  |
| 0.51-1.0 | 13        | 24.07%  |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart_bsd/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 46        | 85.19%  |
| 2      | 5         | 9.26%   |
| 0      | 2         | 3.7%    |
| 3      | 1         | 1.85%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart_bsd/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 28        | 51.85%  |
| Yes       | 26        | 48.15%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart_bsd/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 48        | 88.89%  |
| No        | 6         | 11.11%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart_bsd/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 53        | 98.15%  |
| No        | 1         | 1.85%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart_bsd/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 30        | 55.56%  |
| No        | 24        | 44.44%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart_bsd/node_location.svg)


| Country     | Notebooks | Percent |
|-------------|-----------|---------|
| Brazil      | 6         | 11.11%  |
| Germany     | 5         | 9.26%   |
| USA         | 4         | 7.41%   |
| Russia      | 4         | 7.41%   |
| Ukraine     | 3         | 5.56%   |
| UK          | 3         | 5.56%   |
| China       | 3         | 5.56%   |
| Spain       | 2         | 3.7%    |
| South Korea | 2         | 3.7%    |
| Peru        | 2         | 3.7%    |
| New Zealand | 2         | 3.7%    |
| Netherlands | 2         | 3.7%    |
| Mexico      | 2         | 3.7%    |
| Italy       | 2         | 3.7%    |
| Syria       | 1         | 1.85%   |
| Singapore   | 1         | 1.85%   |
| Poland      | 1         | 1.85%   |
| Lithuania   | 1         | 1.85%   |
| Libya       | 1         | 1.85%   |
| Japan       | 1         | 1.85%   |
| Greece      | 1         | 1.85%   |
| Czechia     | 1         | 1.85%   |
| Cuba        | 1         | 1.85%   |
| Colombia    | 1         | 1.85%   |
| Chile       | 1         | 1.85%   |
| Canada      | 1         | 1.85%   |

City
----

Geographic location (city)

![City](./images/pie_chart_bsd/node_city.svg)


| City                    | Notebooks | Percent |
|-------------------------|-----------|---------|
| Lima                    | 2         | 3.64%   |
| Guangzhou               | 2         | 3.64%   |
| Barcelona               | 2         | 3.64%   |
| Yeongdong-gun           | 1         | 1.82%   |
| Wellington              | 1         | 1.82%   |
| Ufa                     | 1         | 1.82%   |
| Tyumen                  | 1         | 1.82%   |
| Tripoli                 | 1         | 1.82%   |
| The Hague               | 1         | 1.82%   |
| Taito                   | 1         | 1.82%   |
| Stade                   | 1         | 1.82%   |
| St Petersburg           | 1         | 1.82%   |
| Singapore               | 1         | 1.82%   |
| Seoul                   | 1         | 1.82%   |
| Seattle                 | 1         | 1.82%   |
| S??o Paulo              | 1         | 1.82%   |
| Santiago                | 1         | 1.82%   |
| Rio de Janeiro          | 1         | 1.82%   |
| Redmond                 | 1         | 1.82%   |
| Pruszcz Gdanski         | 1         | 1.82%   |
| Pilsen                  | 1         | 1.82%   |
| Oegstgeest              | 1         | 1.82%   |
| Odessa                  | 1         | 1.82%   |
| Obninsk                 | 1         | 1.82%   |
| Nughedu San Nicolo      | 1         | 1.82%   |
| New Plymouth            | 1         | 1.82%   |
| Mykolayiv               | 1         | 1.82%   |
| Monterrey               | 1         | 1.82%   |
| Monte Belo              | 1         | 1.82%   |
| Mission                 | 1         | 1.82%   |
| Memphis                 | 1         | 1.82%   |
| Medell?�n               | 1         | 1.82%   |
| Leatherhead             | 1         | 1.82%   |
| La Paz                  | 1         | 1.82%   |
| Kyiv                    | 1         | 1.82%   |
| Kaunas                  | 1         | 1.82%   |
| Jag??ey Grande          | 1         | 1.82%   |
| Ipojuca                 | 1         | 1.82%   |
| Ibiuna                  | 1         | 1.82%   |
| Frankfurt am Main       | 1         | 1.82%   |
| Finchley                | 1         | 1.82%   |
| Farneto                 | 1         | 1.82%   |
| Dulles                  | 1         | 1.82%   |
| Detmold                 | 1         | 1.82%   |
| Damascus                | 1         | 1.82%   |
| Chengdu                 | 1         | 1.82%   |
| Chapec??                | 1         | 1.82%   |
| Cabo de Santo Agostinho | 1         | 1.82%   |
| Buttelborn              | 1         | 1.82%   |
| Bensheim                | 1         | 1.82%   |
| Athens                  | 1         | 1.82%   |
| Ashton-under-Lyne       | 1         | 1.82%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart_bsd/drive_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 10        | 11     | 16.95%  |
| Samsung Electronics | 9         | 10     | 15.25%  |
| WDC                 | 7         | 7      | 11.86%  |
| Toshiba             | 7         | 8      | 11.86%  |
| Kingston            | 3         | 4      | 5.08%   |
| SanDisk             | 2         | 2      | 3.39%   |
| Hitachi             | 2         | 2      | 3.39%   |
| Crucial             | 2         | 2      | 3.39%   |
| Corsair             | 2         | 2      | 3.39%   |
| SPCC                | 1         | 1      | 1.69%   |
| PLEXTOR             | 1         | 1      | 1.69%   |
| Patriot             | 1         | 1      | 1.69%   |
| Micron Technology   | 1         | 1      | 1.69%   |
| LITEON              | 1         | 1      | 1.69%   |
| Lexar               | 1         | 1      | 1.69%   |
| Leven               | 1         | 1      | 1.69%   |
| KingSpec            | 1         | 1      | 1.69%   |
| Intel               | 1         | 1      | 1.69%   |
| HGST                | 1         | 1      | 1.69%   |
| FORESEE             | 1         | 1      | 1.69%   |
| Apple               | 1         | 1      | 1.69%   |
| Apacer              | 1         | 1      | 1.69%   |
| AMD                 | 1         | 1      | 1.69%   |
| A-DATA Technology   | 1         | 1      | 1.69%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart_bsd/drive_model.svg)


| Model                                | Notebooks | Percent |
|--------------------------------------|-----------|---------|
| Toshiba MQ01ABD100 1TB               | 3         | 5%      |
| Seagate ST9500325AS 500GB            | 3         | 5%      |
| Toshiba MQ01ABF050 500GB             | 2         | 3.33%   |
| Samsung SSD 860 EVO 1TB              | 2         | 3.33%   |
| WDC WDS240G2G0A-00JH30 240GB         | 1         | 1.67%   |
| WDC WD5000BPKT-00PK4T0 500GB         | 1         | 1.67%   |
| WDC WD5000BEKT-60KA9T0 500GB         | 1         | 1.67%   |
| WDC WD3200BEVT-80A0RT0 320GB         | 1         | 1.67%   |
| WDC WD2500BEVS-08VAT2 250GB          | 1         | 1.67%   |
| WDC WD1600BPVT-11JJ5T0 160GB         | 1         | 1.67%   |
| WDC WD1200BEVS-07RST0 120GB          | 1         | 1.67%   |
| Toshiba MK5061GSYN 500GB             | 1         | 1.67%   |
| Toshiba MK3261GSYN 320GB             | 1         | 1.67%   |
| SPCC Solid State Disk 1TB            | 1         | 1.67%   |
| Seagate ST9500420AS 500GB            | 1         | 1.67%   |
| Seagate ST9160412ASG 160GB           | 1         | 1.67%   |
| Seagate ST500LT012-1DG142 500GB      | 1         | 1.67%   |
| Seagate ST500LM021-1KJ152 500GB      | 1         | 1.67%   |
| Seagate ST500LM012 HN-M500MBB 500GB  | 1         | 1.67%   |
| Seagate ST1000LM048-2E7172 1TB       | 1         | 1.67%   |
| Seagate ST1000LM024 HN-M101MBB 1TB   | 1         | 1.67%   |
| SanDisk SSD U110 16GB                | 1         | 1.67%   |
| SanDisk SD5SE2256G1002E 256GB        | 1         | 1.67%   |
| Samsung SSD 850 EVO 500GB            | 1         | 1.67%   |
| Samsung SSD 840 EVO 250GB            | 1         | 1.67%   |
| Samsung MZVL21T0HCLR-00BL7 1TB       | 1         | 1.67%   |
| Samsung MZNTE256HMHP-000L2 256GB     | 1         | 1.67%   |
| Samsung MZNLN512HMJP-000L7 512GB     | 1         | 1.67%   |
| Samsung MZNLN512HMJP-000H1 512GB     | 1         | 1.67%   |
| Samsung MZ7TE128HMGR-000L1 128GB     | 1         | 1.67%   |
| PLEXTOR PX-128M5Pro 128GB            | 1         | 1.67%   |
| Patriot Burst 120GB                  | 1         | 1.67%   |
| Micron MTFDDAV256TBN-1AR15ABHA 256GB | 1         | 1.67%   |
| LITEON IT LCS-128L9S-HP 128GB        | 1         | 1.67%   |
| Lexar 256GB SSD                      | 1         | 1.67%   |
| Leven JAJS300M480C 480GB             | 1         | 1.67%   |
| Kingston SVP200S37A60G 64GB          | 1         | 1.67%   |
| Kingston SUV300S37A120G 120GB        | 1         | 1.67%   |
| Kingston SMS200S360G 64GB            | 1         | 1.67%   |
| Kingston SKC300S37A240G 240GB        | 1         | 1.67%   |
| KingSpec MT-256 256GB                | 1         | 1.67%   |
| Intel SSDSCKGF180A4L 180GB           | 1         | 1.67%   |
| Hitachi HTS545025B9A300 250GB        | 1         | 1.67%   |
| Hitachi HTS541080G9SA00 80GB         | 1         | 1.67%   |
| HGST HTS541010A9E680 1TB             | 1         | 1.67%   |
| FORESEE 128GB SSD                    | 1         | 1.67%   |
| Crucial CT480BX200SSD1 480GB         | 1         | 1.67%   |
| Crucial CT250MX500SSD1 250GB         | 1         | 1.67%   |
| Corsair Force GT 120GB               | 1         | 1.67%   |
| Corsair Force 3 SSD 120GB            | 1         | 1.67%   |
| Apple SSD TS128E 121GB               | 1         | 1.67%   |
| Apacer AS681 240GB                   | 1         | 1.67%   |
| AMD R5SL120G 120GB                   | 1         | 1.67%   |
| A-DATA SX6000PNP 1TB                 | 1         | 1.67%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart_bsd/drive_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 10        | 11     | 38.46%  |
| Toshiba | 7         | 8      | 26.92%  |
| WDC     | 6         | 6      | 23.08%  |
| Hitachi | 2         | 2      | 7.69%   |
| HGST    | 1         | 1      | 3.85%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart_bsd/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 8         | 9      | 25.81%  |
| Kingston            | 3         | 4      | 9.68%   |
| SanDisk             | 2         | 2      | 6.45%   |
| Crucial             | 2         | 2      | 6.45%   |
| Corsair             | 2         | 2      | 6.45%   |
| WDC                 | 1         | 1      | 3.23%   |
| SPCC                | 1         | 1      | 3.23%   |
| PLEXTOR             | 1         | 1      | 3.23%   |
| Patriot             | 1         | 1      | 3.23%   |
| Micron Technology   | 1         | 1      | 3.23%   |
| LITEON              | 1         | 1      | 3.23%   |
| Lexar               | 1         | 1      | 3.23%   |
| Leven               | 1         | 1      | 3.23%   |
| KingSpec            | 1         | 1      | 3.23%   |
| Intel               | 1         | 1      | 3.23%   |
| FORESEE             | 1         | 1      | 3.23%   |
| Apple               | 1         | 1      | 3.23%   |
| Apacer              | 1         | 1      | 3.23%   |
| AMD                 | 1         | 1      | 3.23%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart_bsd/drive_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SSD  | 29        | 33     | 51.79%  |
| HDD  | 25        | 28     | 44.64%  |
| NVMe | 2         | 2      | 3.57%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart_bsd/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 51        | 61     | 96.23%  |
| NVMe | 2         | 2      | 3.77%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart_bsd/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 42        | 50     | 79.25%  |
| 0.51-1.0   | 10        | 10     | 18.87%  |
| 1.01-2.0   | 1         | 1      | 1.89%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart_bsd/drive_space_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 1-20       | 32        | 56.14%  |
| 101-250    | 13        | 22.81%  |
| 251-500    | 8         | 14.04%  |
| 501-1000   | 3         | 5.26%   |
| 51-100     | 1         | 1.75%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart_bsd/drive_space_used.svg)


| Used GB | Notebooks | Percent |
|---------|-----------|---------|
| 1-20    | 54        | 100%    |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart_bsd/drive_malfunc.svg)


| Model                                           | Notebooks | Drives | Percent |
|-------------------------------------------------|-----------|--------|---------|
| WDC WD3200BEVT-80A0RT0 320GB                    | 1         | 1      | 7.14%   |
| Toshiba MQ01ABF050 500GB                        | 1         | 2      | 7.14%   |
| Toshiba MQ01ABD100 1TB                          | 1         | 1      | 7.14%   |
| Toshiba MK5061GSYN 500GB                        | 1         | 1      | 7.14%   |
| Toshiba MK3261GSYN 320GB                        | 1         | 1      | 7.14%   |
| Seagate ST9500420AS 500GB                       | 1         | 1      | 7.14%   |
| Seagate ST9500325AS 500GB                       | 1         | 1      | 7.14%   |
| Seagate ST500LM021-1KJ152 500GB                 | 1         | 1      | 7.14%   |
| Seagate ST1000LM048-2E7172 1TB                  | 1         | 1      | 7.14%   |
| Seagate ST1000LM024 HN-M101MBB 1TB              | 1         | 1      | 7.14%   |
| Micron Technology MTFDDAV256TBN-1AR15ABHA 256GB | 1         | 1      | 7.14%   |
| Hitachi HTS541080G9SA00 80GB                    | 1         | 1      | 7.14%   |
| HGST HTS541010A9E680 1TB                        | 1         | 1      | 7.14%   |
| Corsair Force GT 120GB                          | 1         | 1      | 7.14%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart_bsd/drive_malfunc_vendor.svg)


| Vendor            | Notebooks | Drives | Percent |
|-------------------|-----------|--------|---------|
| Seagate           | 5         | 5      | 35.71%  |
| Toshiba           | 4         | 5      | 28.57%  |
| WDC               | 1         | 1      | 7.14%   |
| Micron Technology | 1         | 1      | 7.14%   |
| Hitachi           | 1         | 1      | 7.14%   |
| HGST              | 1         | 1      | 7.14%   |
| Corsair           | 1         | 1      | 7.14%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart_bsd/drive_malfunc_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 5         | 5      | 41.67%  |
| Toshiba | 4         | 5      | 33.33%  |
| WDC     | 1         | 1      | 8.33%   |
| Hitachi | 1         | 1      | 8.33%   |
| HGST    | 1         | 1      | 8.33%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart_bsd/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 12        | 13     | 85.71%  |
| SSD  | 2         | 2      | 14.29%  |

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
| Works   | 39        | 47     | 72.22%  |
| Malfunc | 14        | 15     | 25.93%  |
| Failed  | 1         | 1      | 1.85%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart_bsd/storage_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 51        | 92.73%  |
| AMD                   | 2         | 3.64%   |
| Samsung Electronics   | 1         | 1.82%   |
| Realtek Semiconductor | 1         | 1.82%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart_bsd/storage_model.svg)


| Model                                                                                  | Notebooks | Percent |
|----------------------------------------------------------------------------------------|-----------|---------|
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                       | 12        | 20%     |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                         | 6         | 10%     |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                     | 5         | 8.33%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                           | 5         | 8.33%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                                     | 4         | 6.67%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller           | 4         | 6.67%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                                 | 3         | 5%      |
| Intel 82801 Mobile SATA Controller [RAID mode]                                         | 3         | 5%      |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]                  | 2         | 3.33%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                         | 2         | 3.33%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                         | 1         | 1.67%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                                     | 1         | 1.67%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                      | 1         | 1.67%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                          | 1         | 1.67%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                       | 1         | 1.67%   |
| Intel 8 Series/C220 Series Chipset Family 2-port SATA Controller 2 [IDE mode]          | 1         | 1.67%   |
| Intel 8 Series Chipset Family 4-port SATA Controller 1 [IDE mode] - Mobile             | 1         | 1.67%   |
| Intel 6 Series/C200 Series Chipset Family Mobile SATA Controller (IDE mode, ports 4-5) | 1         | 1.67%   |
| Intel 6 Series/C200 Series Chipset Family Mobile SATA Controller (IDE mode, ports 0-3) | 1         | 1.67%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA IDE Controller                          | 1         | 1.67%   |
| Intel 5 Series/3400 Series Chipset 2 port SATA IDE Controller                          | 1         | 1.67%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                      | 1         | 1.67%   |
| AMD FCH SATA Controller [AHCI mode]                                                    | 1         | 1.67%   |
| Unknown                                                                                | 1         | 1.67%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart_bsd/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 48        | 84.21%  |
| IDE  | 4         | 7.02%   |
| RAID | 3         | 5.26%   |
| NVMe | 2         | 3.51%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart_bsd/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 52        | 96.3%   |
| AMD    | 2         | 3.7%    |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart_bsd/cpu_model.svg)


| Model                                        | Notebooks | Percent |
|----------------------------------------------|-----------|---------|
| Intel Core i7-3520M CPU @ 2.90GHz            | 2         | 3.7%    |
| Intel Core i5-5200U CPU @ 2.20GHz            | 2         | 3.7%    |
| Intel Core i5-4210U CPU @ 1.70GHz            | 2         | 3.7%    |
| Intel Core i5-3317U CPU @ 1.70GHz            | 2         | 3.7%    |
| Intel Core i5-2520M CPU @ 2.50GHz            | 2         | 3.7%    |
| Intel Core i3-4005U CPU @ 1.70GHz            | 2         | 3.7%    |
| Intel Core i3-3110M CPU @ 2.40GHz            | 2         | 3.7%    |
| Intel Core i3 CPU M 370 @ 2.40GHz            | 2         | 3.7%    |
| Intel Processor 5Y70 CPU @ 1.10GHz           | 1         | 1.85%   |
| Intel Pentium CPU N3530 @ 2.16GHz            | 1         | 1.85%   |
| Intel Pentium CPU 5405U @ 2.30GHz            | 1         | 1.85%   |
| Intel Genuine CPU                            | 1         | 1.85%   |
| Intel CPU Version                            | 1         | 1.85%   |
| Intel Core m3-8100Y CPU @ 1.10GHz            | 1         | 1.85%   |
| Intel Core i7-7500U CPU @ 2.70GHz            | 1         | 1.85%   |
| Intel Core i7-3632QM CPU @ 2.20GHz           | 1         | 1.85%   |
| Intel Core i7-3517U CPU @ 1.90GHz            | 1         | 1.85%   |
| Intel Core i7-2860QM CPU @ 2.50GHz           | 1         | 1.85%   |
| Intel Core i7-2640M CPU @ 2.80GH             | 1         | 1.85%   |
| Intel Core i5-8350U CPU @ 1.70GHz            | 1         | 1.85%   |
| Intel Core i5-7300U CPU @ 2.60GHz            | 1         | 1.85%   |
| Intel Core i5-5300U CPU @ 2.30GHz            | 1         | 1.85%   |
| Intel Core i5-4300U CPU @ 1.90GHz            | 1         | 1.85%   |
| Intel Core i5-4300M CPU @ 2.60GHz            | 1         | 1.85%   |
| Intel Core i5-3320M CPU @ 2.60GHz            | 1         | 1.85%   |
| Intel Core i5-3230M CPU @ 2.60GHz            | 1         | 1.85%   |
| Intel Core i5-3210M CPU @ 2.50GHz            | 1         | 1.85%   |
| Intel Core i5 CPU M 520 @ 2.40GHz            | 1         | 1.85%   |
| Intel Core i5 CPU M 460 @ 2.53GHz            | 1         | 1.85%   |
| Intel Core i5 CPU M 450 @ 2.40GHz            | 1         | 1.85%   |
| Intel Core i3-6100U CPU @ 2.30GHz            | 1         | 1.85%   |
| Intel Core i3-3227U CPU @ 1.90GHz            | 1         | 1.85%   |
| Intel Core i3 CPU M 370 @ 2.40GH             | 1         | 1.85%   |
| Intel Core i3 CPU M 330 @ 2.13GHz            | 1         | 1.85%   |
| Intel Core 2 Duo CPU T8300 @ 2.40GHz         | 1         | 1.85%   |
| Intel Core 2 Duo CPU T5870 @ 2.00GHz         | 1         | 1.85%   |
| Intel Core 2 Duo CPU P8600 @ 2.40GHz         | 1         | 1.85%   |
| Intel Core 2 Duo                             | 1         | 1.85%   |
| Intel Celeron CPU N2930 @ 1.83GHz            | 1         | 1.85%   |
| Intel Celeron CPU B815 @ 1.60GHz             | 1         | 1.85%   |
| Intel Celeron CPU 847 @ 1.10GHz              | 1         | 1.85%   |
| Intel Atom CPU N450 @ 1.66GHz                | 1         | 1.85%   |
| Intel Atom CPU E3825 @ 1.33GHz               | 1         | 1.85%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz      | 1         | 1.85%   |
| AMD C-60 APU with Radeon HD Graphics         | 1         | 1.85%   |
| AMD A6-9225 RADEON R4, 5 COMPUTE CORES 2C+3G | 1         | 1.85%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart_bsd/cpu_family.svg)


| Model            | Notebooks | Percent |
|------------------|-----------|---------|
| Intel Core i5    | 19        | 35.19%  |
| Intel Core i3    | 10        | 18.52%  |
| Intel Core i7    | 7         | 12.96%  |
| Intel Core 2 Duo | 4         | 7.41%   |
| Other            | 3         | 5.56%   |
| Intel Celeron    | 3         | 5.56%   |
| Intel Pentium    | 2         | 3.7%    |
| Intel Atom       | 2         | 3.7%    |
| Intel Genuine    | 1         | 1.85%   |
| Intel Core m3    | 1         | 1.85%   |
| AMD C-60         | 1         | 1.85%   |
| AMD A6           | 1         | 1.85%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart_bsd/cpu_cores.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 43        | 79.63%  |
| 4       | 7         | 12.96%  |
| Unknown | 3         | 5.56%   |
| 1       | 1         | 1.85%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart_bsd/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 53        | 98.15%  |
| 2      | 1         | 1.85%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart_bsd/cpu_threads.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 43        | 79.63%  |
| 1       | 8         | 14.81%  |
| Unknown | 3         | 5.56%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart_bsd/cpu_microarch.svg)


| Name        | Notebooks | Percent |
|-------------|-----------|---------|
| IvyBridge   | 12        | 22.22%  |
| Westmere    | 8         | 14.81%  |
| SandyBridge | 6         | 11.11%  |
| Haswell     | 6         | 11.11%  |
| KabyLake    | 5         | 9.26%   |
| Broadwell   | 4         | 7.41%   |
| Silvermont  | 3         | 5.56%   |
| Penryn      | 3         | 5.56%   |
| TigerLake   | 1         | 1.85%   |
| Skylake     | 1         | 1.85%   |
| Nehalem     | 1         | 1.85%   |
| Excavator   | 1         | 1.85%   |
| Core        | 1         | 1.85%   |
| Bonnell     | 1         | 1.85%   |
| Bobcat      | 1         | 1.85%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart_bsd/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 45        | 76.27%  |
| Nvidia | 10        | 16.95%  |
| AMD    | 4         | 6.78%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart_bsd/gpu_model.svg)


| Model                                                                     | Notebooks | Percent |
|---------------------------------------------------------------------------|-----------|---------|
| Intel 3rd Gen Core processor Graphics Controller                          | 12        | 20.34%  |
| Intel Haswell-ULT Integrated Graphics Controller                          | 5         | 8.47%   |
| Intel Core Processor Integrated Graphics Controller                       | 5         | 8.47%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller | 5         | 8.47%   |
| Intel HD Graphics 5500                                                    | 3         | 5.08%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display              | 3         | 5.08%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]      | 2         | 3.39%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller              | 2         | 3.39%   |
| Intel HD Graphics 620                                                     | 2         | 3.39%   |
| Nvidia GT218M [GeForce 310M]                                              | 1         | 1.69%   |
| Nvidia GK107M [GeForce GT 640M LE]                                        | 1         | 1.69%   |
| Nvidia GF108M [GeForce GT 420M]                                           | 1         | 1.69%   |
| Nvidia GF108GLM [Quadro 1000M]                                            | 1         | 1.69%   |
| Nvidia GF106M [GeForce GTX 460M]                                          | 1         | 1.69%   |
| Nvidia GF106GLM [Quadro 2000M]                                            | 1         | 1.69%   |
| Nvidia G98M [GeForce G 105M]                                              | 1         | 1.69%   |
| Nvidia G84M [GeForce 8600M GT]                                            | 1         | 1.69%   |
| Intel UHD Graphics 620                                                    | 1         | 1.69%   |
| Intel UHD Graphics 615                                                    | 1         | 1.69%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                 | 1         | 1.69%   |
| Intel Skylake GT2 [HD Graphics 520]                                       | 1         | 1.69%   |
| Intel HD Graphics 5300                                                    | 1         | 1.69%   |
| Intel Coffee Lake UHD 610 Graphics Controller                             | 1         | 1.69%   |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller   | 1         | 1.69%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller               | 1         | 1.69%   |
| AMD Wrestler [Radeon HD 6290]                                             | 1         | 1.69%   |
| AMD Venus PRO [Radeon HD 8850M / R9 M265X]                                | 1         | 1.69%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                  | 1         | 1.69%   |
| AMD RV730/M96 [Mobility Radeon HD 4650/5165]                              | 1         | 1.69%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart_bsd/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 37        | 68.52%  |
| 1 x Nvidia     | 6         | 11.11%  |
| Intel + Nvidia | 4         | 7.41%   |
| 2 x Intel      | 3         | 5.56%   |
| 1 x AMD        | 3         | 5.56%   |
| Intel + AMD    | 1         | 1.85%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart_bsd/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 45        | 83.33%  |
| Unknown     | 8         | 14.81%  |
| Proprietary | 1         | 1.85%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart_bsd/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 51        | 94.44%  |
| 0.01-0.5   | 2         | 3.7%    |
| 0.51-1.0   | 1         | 1.85%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart_bsd/mon_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| LG Display          | 11        | 25%     |
| AU Optronics        | 10        | 22.73%  |
| BOE                 | 6         | 13.64%  |
| Samsung Electronics | 5         | 11.36%  |
| Chimei Innolux      | 5         | 11.36%  |
| Lenovo              | 3         | 6.82%   |
| InfoVision          | 2         | 4.55%   |
| Apple               | 2         | 4.55%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart_bsd/mon_model.svg)


| Model                                                                 | Notebooks | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| LG Display LCD Monitor LGD02D8 1366x768 280x160mm 12.7-inch           | 2         | 4.55%   |
| Samsung Electronics LCD Monitor SEC5742 1366x768 310x170mm 13.9-inch  | 1         | 2.27%   |
| Samsung Electronics LCD Monitor SEC414C 1366x768 310x170mm 13.9-inch  | 1         | 2.27%   |
| Samsung Electronics LCD Monitor SEC3942 1366x768 310x170mm 13.9-inch  | 1         | 2.27%   |
| Samsung Electronics LCD Monitor SEC3143 1366x768 310x180mm 14.1-inch  | 1         | 2.27%   |
| Samsung Electronics LCD Monitor SDC434A 3200x1800 290x170mm 13.2-inch | 1         | 2.27%   |
| LG Display LCD Monitor LGD11F9 1280x800 290x180mm 13.4-inch           | 1         | 2.27%   |
| LG Display LCD Monitor LGD048C 1920x1080 290x170mm 13.2-inch          | 1         | 2.27%   |
| LG Display LCD Monitor LGD0470 1920x1080 350x190mm 15.7-inch          | 1         | 2.27%   |
| LG Display LCD Monitor LGD0419 2560x1440 310x170mm 13.9-inch          | 1         | 2.27%   |
| LG Display LCD Monitor LGD03ED 1366x768 280x160mm 12.7-inch           | 1         | 2.27%   |
| LG Display LCD Monitor LGD03AB 1366x768 340x190mm 15.3-inch           | 1         | 2.27%   |
| LG Display LCD Monitor LGD0385 1366x768 310x170mm 13.9-inch           | 1         | 2.27%   |
| LG Display LCD Monitor LGD0323 1920x1080 350x190mm 15.7-inch          | 1         | 2.27%   |
| LG Display LCD Monitor LGD021D 1600x900 380x210mm 17.1-inch           | 1         | 2.27%   |
| Lenovo LEN X24A LEN60CF 1920x1080 530x300mm 24.0-inch                 | 1         | 2.27%   |
| Lenovo LCD Monitor LEN40B2 1920x1080 340x190mm 15.3-inch              | 1         | 2.27%   |
| Lenovo LCD Monitor LEN4050 1280x800 330x210mm 15.4-inch               | 1         | 2.27%   |
| InfoVision LCD Monitor IVO057F 1920x1080 310x170mm 13.9-inch          | 1         | 2.27%   |
| InfoVision LCD Monitor IVO03F4 1024x600 220x130mm 10.1-inch           | 1         | 2.27%   |
| Chimei Innolux LCD Monitor CMN15CA 1366x768 340x190mm 15.3-inch       | 1         | 2.27%   |
| Chimei Innolux LCD Monitor CMN15C6 1366x768 340x190mm 15.3-inch       | 1         | 2.27%   |
| Chimei Innolux LCD Monitor CMN15AB 1366x768 340x190mm 15.3-inch       | 1         | 2.27%   |
| Chimei Innolux LCD Monitor CMN1492 1366x768 310x170mm 13.9-inch       | 1         | 2.27%   |
| Chimei Innolux LCD Monitor CMN1124 1920x1080 260x140mm 11.6-inch      | 1         | 2.27%   |
| BOE LCD Monitor BOE0757 1366x768 340x190mm 15.3-inch                  | 1         | 2.27%   |
| BOE LCD Monitor BOE06D3 1366x768 340x190mm 15.3-inch                  | 1         | 2.27%   |
| BOE LCD Monitor BOE06C8 1366x768 280x160mm 12.7-inch                  | 1         | 2.27%   |
| BOE LCD Monitor BOE0615 1366x768 340x190mm 15.3-inch                  | 1         | 2.27%   |
| BOE LCD Monitor BOE05E9 1366x768 250x140mm 11.3-inch                  | 1         | 2.27%   |
| BOE LCD Monitor BOE05B1 1366x768 310x170mm 13.9-inch                  | 1         | 2.27%   |
| AU Optronics LCD Monitor AUO46EC 1366x768 340x190mm 15.3-inch         | 1         | 2.27%   |
| AU Optronics LCD Monitor AUO45EC 1366x768 340x190mm 15.3-inch         | 1         | 2.27%   |
| AU Optronics LCD Monitor AUO4100 1920x1200 220x140mm 10.3-inch        | 1         | 2.27%   |
| AU Optronics LCD Monitor AUO315C 1366x768 260x140mm 11.6-inch         | 1         | 2.27%   |
| AU Optronics LCD Monitor AUO313C 1366x768 310x170mm 13.9-inch         | 1         | 2.27%   |
| AU Optronics LCD Monitor AUO303E 1600x900 310x170mm 13.9-inch         | 1         | 2.27%   |
| AU Optronics LCD Monitor AUO253C 1366x768 310x170mm 13.9-inch         | 1         | 2.27%   |
| AU Optronics LCD Monitor AUO22EC 1366x768 340x190mm 15.3-inch         | 1         | 2.27%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 340x190mm 15.3-inch        | 1         | 2.27%   |
| AU Optronics LCD Monitor AUO206C 1366x768 280x160mm 12.7-inch         | 1         | 2.27%   |
| Apple LCD Monitor APP9CC3 1280x800 290x180mm 13.4-inch                | 1         | 2.27%   |
| Apple Color LCD APP9CF3 1366x768 260x140mm 11.6-inch                  | 1         | 2.27%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart_bsd/mon_resolution.svg)


| Resolution        | Notebooks | Percent |
|-------------------|-----------|---------|
| 1366x768 (WXGA)   | 27        | 61.36%  |
| 1920x1080 (FHD)   | 8         | 18.18%  |
| 1280x800 (WXGA)   | 3         | 6.82%   |
| 1600x900 (HD+)    | 2         | 4.55%   |
| 3200x1800 (QHD+)  | 1         | 2.27%   |
| 2560x1440 (QHD)   | 1         | 2.27%   |
| 1920x1200 (WUXGA) | 1         | 2.27%   |
| 1024x600          | 1         | 2.27%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart_bsd/mon_diagonal.svg)


| Inches | Notebooks | Percent |
|--------|-----------|---------|
| 15     | 15        | 34.09%  |
| 13     | 15        | 34.09%  |
| 12     | 5         | 11.36%  |
| 11     | 4         | 9.09%   |
| 10     | 2         | 4.55%   |
| 24     | 1         | 2.27%   |
| 17     | 1         | 2.27%   |
| 14     | 1         | 2.27%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart_bsd/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 27        | 61.36%  |
| 201-300     | 15        | 34.09%  |
| 501-600     | 1         | 2.27%   |
| 351-400     | 1         | 2.27%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart_bsd/mon_ratio.svg)


| Ratio | Notebooks | Percent |
|-------|-----------|---------|
| 16/9  | 39        | 90.7%   |
| 16/10 | 4         | 9.3%    |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart_bsd/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 81-90          | 14        | 31.82%  |
| 91-100         | 11        | 25%     |
| 61-70          | 5         | 11.36%  |
| 51-60          | 4         | 9.09%   |
| 101-110        | 4         | 9.09%   |
| 71-80          | 2         | 4.55%   |
| 41-50          | 2         | 4.55%   |
| 201-250        | 1         | 2.27%   |
| 121-130        | 1         | 2.27%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart_bsd/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 101-120       | 22        | 50%     |
| 121-160       | 14        | 31.82%  |
| 161-240       | 4         | 9.09%   |
| 51-100        | 3         | 6.82%   |
| More than 240 | 1         | 2.27%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart_bsd/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 44        | 81.48%  |
| 0     | 9         | 16.67%  |
| 2     | 1         | 1.85%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart_bsd/net_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 28        | 32.18%  |
| Realtek Semiconductor             | 25        | 28.74%  |
| Qualcomm Atheros                  | 12        | 13.79%  |
| Broadcom                          | 11        | 12.64%  |
| Ericsson Business Mobile Networks | 3         | 3.45%   |
| Huawei Technologies               | 2         | 2.3%    |
| Xiaomi                            | 1         | 1.15%   |
| Sierra Wireless                   | 1         | 1.15%   |
| Ralink                            | 1         | 1.15%   |
| Marvell Technology Group          | 1         | 1.15%   |
| JMicron Technology                | 1         | 1.15%   |
| Google                            | 1         | 1.15%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart_bsd/net_model.svg)


| Model                                                                       | Notebooks | Percent |
|-----------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller           | 12        | 10.62%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                       | 9         | 7.96%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                       | 6         | 5.31%   |
| Intel Wireless 7265                                                         | 5         | 4.42%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                                  | 3         | 2.65%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)              | 3         | 2.65%   |
| Intel Wireless 7260                                                         | 3         | 2.65%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                                | 3         | 2.65%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                         | 2         | 1.77%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                  | 2         | 1.77%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                            | 2         | 1.77%   |
| Intel Wireless 8265 / 8275                                                  | 2         | 1.77%   |
| Intel Ethernet Connection (4) I219-LM                                       | 2         | 1.77%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                                | 2         | 1.77%   |
| Intel Centrino Ultimate-N 6300                                              | 2         | 1.77%   |
| Intel 82577LC Gigabit Network Connection                                    | 2         | 1.77%   |
| Ericsson Business Mobile Networks F5521 gw Mobile Broadband Serial Port III | 2         | 1.77%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                             | 2         | 1.77%   |
| Broadcom BCM43142 802.11b/g/n                                               | 2         | 1.77%   |
| Xiaomi Mi/Redmi series (RNDIS)                                              | 1         | 0.88%   |
| Sierra Wireless Sierra Wireless EM7345 4G LTE                               | 1         | 0.88%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter                    | 1         | 0.88%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                    | 1         | 0.88%   |
| Realtek RTL8723DE Wireless Network Adapter                                  | 1         | 0.88%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                             | 1         | 0.88%   |
| Realtek RTL8188EE Wireless Network Adapter                                  | 1         | 0.88%   |
| Realtek Realtek Bluetooth 4.2 Adapter                                       | 1         | 0.88%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                                   | 1         | 0.88%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                                      | 1         | 0.88%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)              | 1         | 0.88%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)              | 1         | 0.88%   |
| Qualcomm Atheros AR8152 v1.1 Fast Ethernet                                  | 1         | 0.88%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                       | 1         | 0.88%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                                    | 1         | 0.88%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express)     | 1         | 0.88%   |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller                     | 1         | 0.88%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller                      | 1         | 0.88%   |
| Intel Wireless 8260                                                         | 1         | 0.88%   |
| Intel Wireless 3160                                                         | 1         | 0.88%   |
| Intel WiFi Link 5100                                                        | 1         | 0.88%   |
| Intel Wi-Fi 6 AX201                                                         | 1         | 0.88%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection                     | 1         | 0.88%   |
| Intel Ethernet Connection I219-V                                            | 1         | 0.88%   |
| Intel Ethernet Connection I218-LM                                           | 1         | 0.88%   |
| Intel Ethernet Connection I217-LM                                           | 1         | 0.88%   |
| Intel Ethernet Connection (3) I218-V                                        | 1         | 0.88%   |
| Intel Ethernet Connection (3) I218-LM                                       | 1         | 0.88%   |
| Intel Centrino Wireless-N 6150                                              | 1         | 0.88%   |
| Intel Centrino Wireless-N 2200                                              | 1         | 0.88%   |
| Intel Centrino Wireless-N 135                                               | 1         | 0.88%   |
| Intel Centrino WiMAX 6150                                                   | 1         | 0.88%   |
| Intel Centrino Advanced-N 6235                                              | 1         | 0.88%   |
| Intel 82567LM Gigabit Network Connection                                    | 1         | 0.88%   |
| Huawei USB Composite Device                                                 | 1         | 0.88%   |
| Huawei ME936 LTE/HSDPA+ 4G modem                                            | 1         | 0.88%   |
| Google Nexus/Pixel Device (tether)                                          | 1         | 0.88%   |
| Ericsson Business Mobile Networks N5321 gw Mobile Broadband Serial Port III | 1         | 0.88%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                           | 1         | 0.88%   |
| Broadcom NetLink BCM5787M Gigabit Ethernet PCI Express                      | 1         | 0.88%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                          | 1         | 0.88%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart_bsd/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 26        | 46.43%  |
| Qualcomm Atheros      | 10        | 17.86%  |
| Realtek Semiconductor | 9         | 16.07%  |
| Broadcom              | 9         | 16.07%  |
| Sierra Wireless       | 1         | 1.79%   |
| Ralink                | 1         | 1.79%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart_bsd/net_wireless_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Intel Wireless 7265                                                     | 5         | 8.47%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 3         | 5.08%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 3         | 5.08%   |
| Intel Wireless 7260                                                     | 3         | 5.08%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 3         | 5.08%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 2         | 3.39%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 2         | 3.39%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 2         | 3.39%   |
| Intel Wireless 8265 / 8275                                              | 2         | 3.39%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                            | 2         | 3.39%   |
| Intel Centrino Ultimate-N 6300                                          | 2         | 3.39%   |
| Broadcom BCM43142 802.11b/g/n                                           | 2         | 3.39%   |
| Sierra Wireless Sierra Wireless EM7345 4G LTE                           | 1         | 1.69%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter                | 1         | 1.69%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 1         | 1.69%   |
| Realtek RTL8723DE Wireless Network Adapter                              | 1         | 1.69%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 1         | 1.69%   |
| Realtek RTL8188EE Wireless Network Adapter                              | 1         | 1.69%   |
| Realtek Realtek Bluetooth 4.2 Adapter                                   | 1         | 1.69%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                               | 1         | 1.69%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 1         | 1.69%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)          | 1         | 1.69%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 1         | 1.69%   |
| Intel Wireless 8260                                                     | 1         | 1.69%   |
| Intel Wireless 3160                                                     | 1         | 1.69%   |
| Intel WiFi Link 5100                                                    | 1         | 1.69%   |
| Intel Wi-Fi 6 AX201                                                     | 1         | 1.69%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection                 | 1         | 1.69%   |
| Intel Centrino Wireless-N 6150                                          | 1         | 1.69%   |
| Intel Centrino Wireless-N 2200                                          | 1         | 1.69%   |
| Intel Centrino Wireless-N 135                                           | 1         | 1.69%   |
| Intel Centrino WiMAX 6150                                               | 1         | 1.69%   |
| Intel Centrino Advanced-N 6235                                          | 1         | 1.69%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                      | 1         | 1.69%   |
| Broadcom BCM4331 802.11a/b/g/n                                          | 1         | 1.69%   |
| Broadcom BCM43228 802.11a/b/g/n                                         | 1         | 1.69%   |
| Broadcom BCM43225 802.11b/g/n                                           | 1         | 1.69%   |
| Broadcom BCM43224 802.11a/b/g/n                                         | 1         | 1.69%   |
| Broadcom BCM4321 802.11a/b/g/n                                          | 1         | 1.69%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 1         | 1.69%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart_bsd/net_ethernet_vendor.svg)


| Vendor                   | Notebooks | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 21        | 42%     |
| Intel                    | 16        | 32%     |
| Qualcomm Atheros         | 4         | 8%      |
| Broadcom                 | 4         | 8%      |
| Xiaomi                   | 1         | 2%      |
| Marvell Technology Group | 1         | 2%      |
| JMicron Technology       | 1         | 2%      |
| Huawei Technologies      | 1         | 2%      |
| Google                   | 1         | 2%      |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart_bsd/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 12        | 24%     |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 9         | 18%     |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 6         | 12%     |
| Intel Ethernet Connection (4) I219-LM                             | 2         | 4%      |
| Intel 82577LC Gigabit Network Connection                          | 2         | 4%      |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 2         | 4%      |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 1         | 2%      |
| Qualcomm Atheros QCA8172 Fast Ethernet                            | 1         | 2%      |
| Qualcomm Atheros AR8152 v1.1 Fast Ethernet                        | 1         | 2%      |
| Qualcomm Atheros AR8132 Fast Ethernet                             | 1         | 2%      |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 1         | 2%      |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller           | 1         | 2%      |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller            | 1         | 2%      |
| Intel Ethernet Connection I219-V                                  | 1         | 2%      |
| Intel Ethernet Connection I218-LM                                 | 1         | 2%      |
| Intel Ethernet Connection I217-LM                                 | 1         | 2%      |
| Intel Ethernet Connection (3) I218-V                              | 1         | 2%      |
| Intel Ethernet Connection (3) I218-LM                             | 1         | 2%      |
| Intel 82567LM Gigabit Network Connection                          | 1         | 2%      |
| Huawei USB Composite Device                                       | 1         | 2%      |
| Google Nexus/Pixel Device (tether)                                | 1         | 2%      |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 1         | 2%      |
| Broadcom NetLink BCM5787M Gigabit Ethernet PCI Express            | 1         | 2%      |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart_bsd/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 54        | 50.94%  |
| Ethernet | 48        | 45.28%  |
| Modem    | 2         | 1.89%   |
| Unknown  | 2         | 1.89%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart_bsd/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| Ethernet | 45        | 48.91%  |
| WiFi     | 44        | 47.83%  |
| Unknown  | 2         | 2.17%   |
| Modem    | 1         | 1.09%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart_bsd/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 46        | 85.19%  |
| 1     | 8         | 14.81%  |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart_bsd/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 53        | 98.15%  |
| Yes  | 1         | 1.85%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart_bsd/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 12        | 38.71%  |
| Broadcom                        | 6         | 19.35%  |
| Apple                           | 4         | 12.9%   |
| Realtek Semiconductor           | 3         | 9.68%   |
| Ralink                          | 1         | 3.23%   |
| Qualcomm Atheros Communications | 1         | 3.23%   |
| IMC Networks                    | 1         | 3.23%   |
| Hewlett-Packard                 | 1         | 3.23%   |
| Foxconn / Hon Hai               | 1         | 3.23%   |
| Cambridge Silicon Radio         | 1         | 3.23%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart_bsd/bt_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 10        | 32.26%  |
| Broadcom BCM43142 Bluetooth 4.0                     | 2         | 6.45%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 2         | 6.45%   |
| Apple Apple Broadcom Built-in Bluetooth             | 2         | 6.45%   |
| Realtek RTL8723B Bluetooth                          | 1         | 3.23%   |
| Realtek  Bluetooth Adapter                          | 1         | 3.23%   |
| Realtek Bluetooth Radio                             | 1         | 3.23%   |
| Ralink RT3290 Bluetooth                             | 1         | 3.23%   |
| Qualcomm Atheros AR9462 Bluetooth                   | 1         | 3.23%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 1         | 3.23%   |
| Intel AX201 Bluetooth                               | 1         | 3.23%   |
| IMC Networks Qualcomm Atheros Bluetooth 4.0 + HS    | 1         | 3.23%   |
| HP Broadcom 2070 Bluetooth Combo                    | 1         | 3.23%   |
| Foxconn / Hon Hai Atheros AR3012 Bluetooth          | 1         | 3.23%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 1         | 3.23%   |
| Broadcom Broadcom Bluetooth 4.0                     | 1         | 3.23%   |
| Broadcom BCM2045B (BDC-2.1)                         | 1         | 3.23%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                | 1         | 3.23%   |
| Apple Bluetooth HCI                                 | 1         | 3.23%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart_bsd/snd_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 52        | 86.67%  |
| Nvidia | 4         | 6.67%   |
| AMD    | 3         | 5%      |
| XMOS   | 1         | 1.67%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart_bsd/snd_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 13        | 18.31%  |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 9         | 12.68%  |
| Intel Sunrise Point-LP HD Audio                                            | 5         | 7.04%   |
| Intel 8 Series HD Audio Controller                                         | 5         | 7.04%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 5         | 7.04%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 4         | 5.63%   |
| Intel Haswell-ULT HD Audio Controller                                      | 4         | 5.63%   |
| Intel Broadwell-U Audio Controller                                         | 4         | 5.63%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller | 3         | 4.23%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 3         | 4.23%   |
| Nvidia GF108 High Definition Audio Controller                              | 2         | 2.82%   |
| XMOS retrieving string failed                                              | 1         | 1.41%   |
| Nvidia High Definition Audio Controller                                    | 1         | 1.41%   |
| Nvidia GF106 High Definition Audio Controller                              | 1         | 1.41%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 1         | 1.41%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 1         | 1.41%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 1         | 1.41%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 1         | 1.41%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                             | 1         | 1.41%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 1         | 1.41%   |
| AMD Wrestler HDMI Audio                                                    | 1         | 1.41%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 1         | 1.41%   |
| AMD RV710/730 HDMI Audio [Radeon HD 4000 series]                           | 1         | 1.41%   |
| AMD High Definition Audio Controller                                       | 1         | 1.41%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                           | 1         | 1.41%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart_bsd/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| SK Hynix            | 18        | 26.47%  |
| Samsung Electronics | 12        | 17.65%  |
| Micron Technology   | 7         | 10.29%  |
| Unknown             | 6         | 8.82%   |
| Kingston            | 6         | 8.82%   |
| Teikon              | 2         | 2.94%   |
| Team                | 2         | 2.94%   |
| Smart               | 2         | 2.94%   |
| Ramaxel Technology  | 2         | 2.94%   |
| Nanya Technology    | 2         | 2.94%   |
| Elpida              | 2         | 2.94%   |
| Unknown             | 2         | 2.94%   |
| Smart Brazil        | 1         | 1.47%   |
| PKI/Kingston        | 1         | 1.47%   |
| Crucial             | 1         | 1.47%   |
| ASint Technology    | 1         | 1.47%   |
| A-DATA Technology   | 1         | 1.47%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart_bsd/memory_model.svg)


| Model                                                        | Notebooks | Percent |
|--------------------------------------------------------------|-----------|---------|
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                   | 2         | 2.86%   |
| SK Hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s       | 2         | 2.86%   |
| SK Hynix RAM HMT351S6EFR8A-PB 4GB SODIMM DDR3 1600MT/s       | 2         | 2.86%   |
| SK Hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s       | 2         | 2.86%   |
| Samsung RAM M471B5673FH0-CH9 2GB SODIMM DDR3 1333MT/s        | 2         | 2.86%   |
| Nanya RAM NT2GC64B8HA1NS-BE 2GB SODIMM DDR3 1067MT/s         | 2         | 2.86%   |
| Unknown                                                      | 2         | 2.86%   |
| Unknown RAM Module 4GB SODIMM DDR3 1600MT/s                  | 1         | 1.43%   |
| Unknown RAM Module 4GB SODIMM DDR3 1333MT/s                  | 1         | 1.43%   |
| Unknown RAM Module 4GB SODIMM DDR3                           | 1         | 1.43%   |
| Unknown RAM Module 4GB DIMM DDR3 1067MT/s                    | 1         | 1.43%   |
| Teikon RAM TMT451S6BFR8A-PBHC 4GB SODIMM DDR3 1333MT/s       | 1         | 1.43%   |
| Teikon RAM TMT41GS6BFR8A-PBSC 8GB SODIMM DDR3 1600MT/s       | 1         | 1.43%   |
| Team RAM TEAMGROUP-SD3-1066 4GB SODIMM DDR3 1067MT/s         | 1         | 1.43%   |
| Team RAM Elite-1333 4GB SODIMM DDR3 1333MT/s                 | 1         | 1.43%   |
| Smart RAM SH564568FH8NZPHSCR 2GB SODIMM DDR3 1334MT/s        | 1         | 1.43%   |
| Smart RAM SH564128FJ8NWRNSQG 4GB SODIMM DDR3 1600MT/s        | 1         | 1.43%   |
| Smart Brazil RAM SF4641G8CK8IEHLSBG 8GB SODIMM DDR4 2133MT/s | 1         | 1.43%   |
| SK Hynix RAM Module 8GB SODIMM DDR4 2400MT/s                 | 1         | 1.43%   |
| SK Hynix RAM Module 8GB Row Of Chips LPDDR3 1600MT/s         | 1         | 1.43%   |
| SK Hynix RAM Module 2GB SODIMM DDR3 1600MT/s                 | 1         | 1.43%   |
| SK Hynix RAM HMT451S6AFR8C-PB 4GB SODIMM DDR3 1600MT/s       | 1         | 1.43%   |
| SK Hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s       | 1         | 1.43%   |
| SK Hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s       | 1         | 1.43%   |
| SK Hynix RAM HMT41GS6AFR8A-PB 8GB SODIMM DDR3 1600MT/s       | 1         | 1.43%   |
| SK Hynix RAM HMT351S6EFR8C-PB 4GB SODIMM DDR3 1600MT/s       | 1         | 1.43%   |
| SK Hynix RAM HMT351S6CFR8C-H9 4GB SODIMM DDR3 1333MT/s       | 1         | 1.43%   |
| SK Hynix RAM HMT351S6CFR8A-PB 4GB SODIMM DDR3 1600MT/s       | 1         | 1.43%   |
| SK Hynix RAM HMT351S6CFR8A-PB 4GB SODIMM DDR3 1333MT/s       | 1         | 1.43%   |
| SK Hynix RAM HMT351S6BFR8C-H9 4GB SODIMM DDR3 1333MT/s       | 1         | 1.43%   |
| SK Hynix RAM HMT325S6BFR8C-H9 2GB SODIMM DDR3 1333MT/s       | 1         | 1.43%   |
| Samsung RAM M471B5674QH0-YK0 2GB SODIMM DDR3 1600MT/s        | 1         | 1.43%   |
| Samsung RAM M471B5674-H0-YK0--- 4GB Chip DDR3 1600MT/s       | 1         | 1.43%   |
| Samsung RAM M471B5673FH0-CF8 2GB SODIMM DDR3 1067MT/s        | 1         | 1.43%   |
| Samsung RAM M471B5273DH0-CK0 4GB SODIMM DDR3 1600MT/s        | 1         | 1.43%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s        | 1         | 1.43%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1333MT/s        | 1         | 1.43%   |
| Samsung RAM M471B5273CH0-CF8 4GB SODIMM DDR3 1067MT/s        | 1         | 1.43%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s        | 1         | 1.43%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s        | 1         | 1.43%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 2667MT/s        | 1         | 1.43%   |
| Samsung RAM K4B8G1646B-MYK0 4GB SODIMM DDR3 1600MT/s         | 1         | 1.43%   |
| Ramaxel RAM RMT3190ME76F8F1600 2GB SODIMM DDR3 1067MT/s      | 1         | 1.43%   |
| Ramaxel RAM RMSA3230KB78HAF2133 8GB SODIMM DDR4 2133MT/s     | 1         | 1.43%   |
| PKI/Kingston RAM 9905428-043.A00LF 4GB SODIMM DDR3 1067MT/s  | 1         | 1.43%   |
| Micron RAM Module 2GB SODIMM DDR3 1333MT/s                   | 1         | 1.43%   |
| Micron RAM 8KTF51264HZ-1G6N1 4GB SODIMM DDR3 1600MT/s        | 1         | 1.43%   |
| Micron RAM 8JSF25664HZ-1G4D1 2GB SODIMM DDR3 1333MT/s        | 1         | 1.43%   |
| Micron RAM 8ATF1G64HZ-2G3H1 8GB SODIMM DDR4 2400MT/s         | 1         | 1.43%   |
| Micron RAM 53E1G32D2NP-046 2GB Row Of Chips LPDDR4 4267MT/s  | 1         | 1.43%   |
| Micron RAM 16KTF1G64HZ-1G6E1 8GB SODIMM DDR3 1600MT/s        | 1         | 1.43%   |
| Micron RAM 16JSF25664HY-1G1D1 2GB SODIMM DDR3 1066MT/s       | 1         | 1.43%   |
| Kingston RAM TSB16D3LS1KFG/4G 4GB SODIMM DDR3 1600MT/s       | 1         | 1.43%   |
| Kingston RAM KFYHV1-HYC 4GB SODIMM DDR3 1600MT/s             | 1         | 1.43%   |
| Kingston RAM ACR256X64D3S1066C7 2GB SODIMM DDR3 1067MT/s     | 1         | 1.43%   |
| Kingston RAM ACR16D3LS1KFG/8G 8GB SODIMM DDR3 1600MT/s       | 1         | 1.43%   |
| Kingston RAM ACR16D3LS1KDG/2G 2GB SODIMM DDR3 1066MT/s       | 1         | 1.43%   |
| Kingston RAM 9905428-012.A00LF 4GB SODIMM DDR3 1333MT/s      | 1         | 1.43%   |
| Elpida RAM Module 2GB SODIMM DDR3 1600MT/s                   | 1         | 1.43%   |
| Elpida RAM EBJ20UF8BCS0-DJ-F 2GB SODIMM DDR3 1333MT/s        | 1         | 1.43%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart_bsd/memory_kind.svg)


| Kind   | Notebooks | Percent |
|--------|-----------|---------|
| DDR3   | 41        | 78.85%  |
| DDR4   | 5         | 9.62%   |
| DDR2   | 3         | 5.77%   |
| LPDDR3 | 2         | 3.85%   |
| LPDDR4 | 1         | 1.92%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart_bsd/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 48        | 92.31%  |
| Row Of Chips | 2         | 3.85%   |
| DIMM         | 1         | 1.92%   |
| Chip         | 1         | 1.92%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart_bsd/memory_size.svg)


| Size | Notebooks | Percent |
|------|-----------|---------|
| 4096 | 31        | 50.82%  |
| 2048 | 19        | 31.15%  |
| 8192 | 11        | 18.03%  |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart_bsd/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 1600    | 24        | 40.68%  |
| 1333    | 13        | 22.03%  |
| 1067    | 9         | 15.25%  |
| 667     | 3         | 5.08%   |
| 2400    | 2         | 3.39%   |
| 2133    | 2         | 3.39%   |
| 1334    | 2         | 3.39%   |
| 4267    | 1         | 1.69%   |
| 2667    | 1         | 1.69%   |
| 1066    | 1         | 1.69%   |
| Unknown | 1         | 1.69%   |

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
| Chicony Electronics                    | 12        | 27.91%  |
| Acer                                   | 6         | 13.95%  |
| Sunplus Innovation Technology          | 4         | 9.3%    |
| Realtek Semiconductor                  | 3         | 6.98%   |
| Microdia                               | 3         | 6.98%   |
| Cheng Uei Precision Industry (Foxlink) | 3         | 6.98%   |
| Suyin                                  | 2         | 4.65%   |
| Apple                                  | 2         | 4.65%   |
| Tripath Technology                     | 1         | 2.33%   |
| Syntek                                 | 1         | 2.33%   |
| Lite-On Technology                     | 1         | 2.33%   |
| Lenovo                                 | 1         | 2.33%   |
| Importek                               | 1         | 2.33%   |
| IMC Networks                           | 1         | 2.33%   |
| Foxconn / Hon Hai                      | 1         | 2.33%   |
| ALi                                    | 1         | 2.33%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart_bsd/camera_model.svg)


| Model                                                          | Notebooks | Percent |
|----------------------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                                      | 6         | 13.95%  |
| Acer Integrated Camera                                         | 3         | 6.98%   |
| Realtek Realtek USB2.0 PC Camera                               | 2         | 4.65%   |
| Tripath 2M Front Camera                                        | 1         | 2.33%   |
| Syntek EasyCamera                                              | 1         | 2.33%   |
| Suyin Integrated_Webcam_HD                                     | 1         | 2.33%   |
| Suyin 1.3M WebCam (notebook emachines E730, Acer sub-brand)    | 1         | 2.33%   |
| Sunplus Lenovo EasyCamera                                      | 1         | 2.33%   |
| Sunplus Laptop_Integrated_Webcam_FHD                           | 1         | 2.33%   |
| Sunplus Integrated Camera                                      | 1         | 2.33%   |
| Sunplus HP Universal Camera                                    | 1         | 2.33%   |
| Realtek Integrated_Webcam_HD                                   | 1         | 2.33%   |
| Microdia Laptop_Integrated_Webcam_2M                           | 1         | 2.33%   |
| Microdia Integrated Webcam HD                                  | 1         | 2.33%   |
| Microdia Dell Laptop Integrated Webcam HD                      | 1         | 2.33%   |
| Lite-On Integrated Camera                                      | 1         | 2.33%   |
| Lenovo Integrated Webcam                                       | 1         | 2.33%   |
| Importek HP Webcam                                             | 1         | 2.33%   |
| IMC Networks 2M Integrated Webcam                              | 1         | 2.33%   |
| Foxconn / Hon Hai USB2.0 Camera                                | 1         | 2.33%   |
| Chicony USB2.0 VGA UVC WebCam                                  | 1         | 2.33%   |
| Chicony TOSHIBA Web Camera - HD                                | 1         | 2.33%   |
| Chicony Lenovo Integrated Camera (0.3MP)                       | 1         | 2.33%   |
| Chicony Lenovo EasyCamera                                      | 1         | 2.33%   |
| Chicony Asus 720p CMOS webcam                                  | 1         | 2.33%   |
| Chicony 1.3M Webcam                                            | 1         | 2.33%   |
| Cheng Uei Precision Industry (Foxlink) HP Webcam-101           | 1         | 2.33%   |
| Cheng Uei Precision Industry (Foxlink) HP Universal Camera     | 1         | 2.33%   |
| Cheng Uei Precision Industry (Foxlink) HP TrueVision HD Camera | 1         | 2.33%   |
| Apple FaceTime HD Camera (Built-in)                            | 1         | 2.33%   |
| Apple FaceTime HD Camera                                       | 1         | 2.33%   |
| ALi WebCam                                                     | 1         | 2.33%   |
| Acer ThinkPad Integrated Camera                                | 1         | 2.33%   |
| Acer Lenovo EasyCamera                                         | 1         | 2.33%   |
| Acer HD Webcam                                                 | 1         | 2.33%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart_bsd/fingerprint_vendor.svg)


| Vendor           | Notebooks | Percent |
|------------------|-----------|---------|
| Validity Sensors | 5         | 45.45%  |
| Upek             | 3         | 27.27%  |
| AuthenTec        | 3         | 27.27%  |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart_bsd/fingerprint_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Validity Sensors VFS 5011 fingerprint sensor                               | 3         | 27.27%  |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 3         | 27.27%  |
| Validity Sensors VFS301 Fingerprint Reader                                 | 1         | 9.09%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 1         | 9.09%   |
| AuthenTec AuthenTec Inc. AES1660                                           | 1         | 9.09%   |
| AuthenTec AES2810                                                          | 1         | 9.09%   |
| AuthenTec AES1600                                                          | 1         | 9.09%   |

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
| 2     | 18        | 33.33%  |
| 1     | 16        | 29.63%  |
| 3     | 10        | 18.52%  |
| 0     | 6         | 11.11%  |
| 4     | 4         | 7.41%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart_bsd/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Communication controller | 42        | 44.21%  |
| Card reader              | 17        | 17.89%  |
| Net/wireless             | 12        | 12.63%  |
| Fingerprint reader       | 11        | 11.58%  |
| Firewire controller      | 5         | 5.26%   |
| Bluetooth                | 5         | 5.26%   |
| Storage                  | 2         | 2.11%   |
| Network                  | 1         | 1.05%   |

