helloSystem 0.8.0 - Tested Hardware & Statistics (Notebooks)
------------------------------------------------------------

A project to collect tested hardware configurations for helloSystem 0.8.0.

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

Total: 107

| Vendor        | Model                       | Probe                                                     | Date         |
|---------------|-----------------------------|-----------------------------------------------------------|--------------|
| HP            | ENVY TS m6 Sleekbook        | [402494618a](https://bsd-hardware.info/?probe=402494618a) | Feb 01, 2023 |
| HP            | ENVY TS m6 Sleekbook        | [63d90da096](https://bsd-hardware.info/?probe=63d90da096) | Feb 01, 2023 |
| MSI           | Modern 15 A5M               | [afda1bcf60](https://bsd-hardware.info/?probe=afda1bcf60) | Jan 31, 2023 |
| HP            | EliteBook 8440p             | [d732f4d6c4](https://bsd-hardware.info/?probe=d732f4d6c4) | Jan 31, 2023 |
| MSI           | Modern 15 A5M               | [26d140b290](https://bsd-hardware.info/?probe=26d140b290) | Jan 31, 2023 |
| Dell          | Precision 5540              | [de7ac2f8d1](https://bsd-hardware.info/?probe=de7ac2f8d1) | Jan 30, 2023 |
| Apple         | MacBookAir5,1               | [eeed92ab62](https://bsd-hardware.info/?probe=eeed92ab62) | Jan 29, 2023 |
| Lenovo        | ThinkPad X1 Carbon 3448A... | [6da773c078](https://bsd-hardware.info/?probe=6da773c078) | Jan 29, 2023 |
| Packard Be... | DOT S                       | [09a2057767](https://bsd-hardware.info/?probe=09a2057767) | Jan 28, 2023 |
| Razer         | Blade Stealth               | [14760d0c64](https://bsd-hardware.info/?probe=14760d0c64) | Jan 28, 2023 |
| Lenovo        | ThinkPad E585 20KV0010US    | [9cfe2dd858](https://bsd-hardware.info/?probe=9cfe2dd858) | Jan 28, 2023 |
| Dell          | Latitude 5400               | [a266199ace](https://bsd-hardware.info/?probe=a266199ace) | Jan 27, 2023 |
| Google        | Cave                        | [76ac12f1e2](https://bsd-hardware.info/?probe=76ac12f1e2) | Jan 25, 2023 |
| HP            | EliteBook 2560p             | [80c808de34](https://bsd-hardware.info/?probe=80c808de34) | Jan 25, 2023 |
| Timi          | TM1607                      | [57113d2886](https://bsd-hardware.info/?probe=57113d2886) | Jan 25, 2023 |
| Lenovo        | G500 20236                  | [081d22fbe2](https://bsd-hardware.info/?probe=081d22fbe2) | Jan 24, 2023 |
| Lenovo        | G500 20236                  | [a35053ad38](https://bsd-hardware.info/?probe=a35053ad38) | Jan 24, 2023 |
| MSI           | PS63 Modern 8M              | [f740e313e5](https://bsd-hardware.info/?probe=f740e313e5) | Jan 24, 2023 |
| Timi          | TM1607                      | [27db14fdbd](https://bsd-hardware.info/?probe=27db14fdbd) | Jan 24, 2023 |
| Fujitsu       | LIFEBOOK S935               | [5c07c1a47e](https://bsd-hardware.info/?probe=5c07c1a47e) | Jan 24, 2023 |
| Dell          | Latitude 3540               | [a180a149f5](https://bsd-hardware.info/?probe=a180a149f5) | Jan 24, 2023 |
| Dell          | Latitude 5580               | [90cd22ad55](https://bsd-hardware.info/?probe=90cd22ad55) | Jan 24, 2023 |
| Toshiba       | PORTEGE Z930                | [476203ee86](https://bsd-hardware.info/?probe=476203ee86) | Jan 23, 2023 |
| Apple         | MacBookPro9,2               | [aaccb6df1a](https://bsd-hardware.info/?probe=aaccb6df1a) | Jan 23, 2023 |
| Toshiba       | PORTEGE Z930                | [4af2cc1909](https://bsd-hardware.info/?probe=4af2cc1909) | Jan 23, 2023 |
| ASUSTek       | K50IN                       | [6f7a8f3338](https://bsd-hardware.info/?probe=6f7a8f3338) | Jan 23, 2023 |
| Lenovo        | ThinkPad W541 20EF000NUS    | [200a92d510](https://bsd-hardware.info/?probe=200a92d510) | Jan 23, 2023 |
| Star Labs     | StarBook                    | [d222f381b0](https://bsd-hardware.info/?probe=d222f381b0) | Jan 23, 2023 |
| Star Labs     | StarBook                    | [045d4bb6e8](https://bsd-hardware.info/?probe=045d4bb6e8) | Jan 23, 2023 |
| Dell          | Inspiron 15-7568            | [44e36adfa4](https://bsd-hardware.info/?probe=44e36adfa4) | Jan 23, 2023 |
| Dell          | Inspiron 3442               | [8b137bca84](https://bsd-hardware.info/?probe=8b137bca84) | Jan 23, 2023 |
| Timi          | TM1607                      | [7636a0ef8f](https://bsd-hardware.info/?probe=7636a0ef8f) | Jan 23, 2023 |
| Timi          | TM1607                      | [1ca46404a1](https://bsd-hardware.info/?probe=1ca46404a1) | Jan 23, 2023 |
| Samsung       | 340XAA/350XAA/550XAA        | [881e97e41c](https://bsd-hardware.info/?probe=881e97e41c) | Jan 23, 2023 |
| Acer          | Aspire ES1-533              | [d2652b76cf](https://bsd-hardware.info/?probe=d2652b76cf) | Jan 22, 2023 |
| Lenovo        | ThinkPad P50 20EN0041MX     | [c27f1f53f2](https://bsd-hardware.info/?probe=c27f1f53f2) | Jan 22, 2023 |
| HP            | Laptop 15-bs0xx             | [7bd5f0c2e9](https://bsd-hardware.info/?probe=7bd5f0c2e9) | Jan 22, 2023 |
| Panasonic     | CF-C1BWFAZ1M                | [d129d929ac](https://bsd-hardware.info/?probe=d129d929ac) | Jan 22, 2023 |
| Lenovo        | ThinkPad P51 20HH001RMX     | [ab38c51298](https://bsd-hardware.info/?probe=ab38c51298) | Jan 22, 2023 |
| HP            | ZBook 15 G4                 | [e98d329586](https://bsd-hardware.info/?probe=e98d329586) | Jan 15, 2023 |
| HP            | ZBook 15 G4                 | [86875f01c2](https://bsd-hardware.info/?probe=86875f01c2) | Jan 15, 2023 |
| Lenovo        | ThinkPad P15v Gen 2i 21A... | [035f9afc5d](https://bsd-hardware.info/?probe=035f9afc5d) | Jan 14, 2023 |
| Lenovo        | ThinkPad P15v Gen 2i 21A... | [9ded9cc6ec](https://bsd-hardware.info/?probe=9ded9cc6ec) | Jan 14, 2023 |
| Razer         | Blade Stealth               | [2464314a65](https://bsd-hardware.info/?probe=2464314a65) | Jan 11, 2023 |
| Lenovo        | ThinkPad T61 64644YG        | [0657433463](https://bsd-hardware.info/?probe=0657433463) | Jan 03, 2023 |
| Apple         | MacBookAir5,1               | [0d398d5c59](https://bsd-hardware.info/?probe=0d398d5c59) | Dec 27, 2022 |
| Lenovo        | ThinkPad X1 Extreme Gen ... | [d19db2828c](https://bsd-hardware.info/?probe=d19db2828c) | Dec 16, 2022 |
| Dell          | Latitude 5590               | [0a17f04eba](https://bsd-hardware.info/?probe=0a17f04eba) | Dec 02, 2022 |
| Toshiba       | TECRA Z40-C-12Z             | [149e5c3de3](https://bsd-hardware.info/?probe=149e5c3de3) | Nov 28, 2022 |
| Acer          | Aspire 5251                 | [046bc722cb](https://bsd-hardware.info/?probe=046bc722cb) | Nov 16, 2022 |
| Dell          | Inspiron 3421               | [5c37012f33](https://bsd-hardware.info/?probe=5c37012f33) | Nov 10, 2022 |
| HP            | Pavilion g6                 | [c4e84b8104](https://bsd-hardware.info/?probe=c4e84b8104) | Oct 30, 2022 |
| Google        | Edgar                       | [318a750368](https://bsd-hardware.info/?probe=318a750368) | Oct 22, 2022 |
| MSI           | PS63 Modern 8M              | [949e472db5](https://bsd-hardware.info/?probe=949e472db5) | Oct 19, 2022 |
| TUXEDO        | Aura 15 Gen1                | [a49ac2701d](https://bsd-hardware.info/?probe=a49ac2701d) | Oct 02, 2022 |
| Kraftway      | KW10T                       | [db27da2e88](https://bsd-hardware.info/?probe=db27da2e88) | Sep 29, 2022 |
| Lenovo        | ThinkPad X250 20CLS1WP01    | [1b75ee6295](https://bsd-hardware.info/?probe=1b75ee6295) | Sep 19, 2022 |
| Apple         | MacBook5,2                  | [79503c0635](https://bsd-hardware.info/?probe=79503c0635) | Sep 10, 2022 |
| Apple         | MacBook5,2                  | [9c7a64970c](https://bsd-hardware.info/?probe=9c7a64970c) | Sep 10, 2022 |
| Dell          | Latitude E5550              | [867e56fb52](https://bsd-hardware.info/?probe=867e56fb52) | Sep 01, 2022 |
| Lenovo        | ThinkPad T420 4178A72       | [18a105546b](https://bsd-hardware.info/?probe=18a105546b) | Aug 29, 2022 |
| Lenovo        | ThinkPad T420 4178A72       | [1433351032](https://bsd-hardware.info/?probe=1433351032) | Aug 29, 2022 |
| Toshiba       | Satellite S55t-B            | [df9971d3aa](https://bsd-hardware.info/?probe=df9971d3aa) | Aug 27, 2022 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [2c7586b0ed](https://bsd-hardware.info/?probe=2c7586b0ed) | Aug 25, 2022 |
| TUXEDO        | Pulse 14 Gen1               | [5edf8a1bef](https://bsd-hardware.info/?probe=5edf8a1bef) | Aug 09, 2022 |
| ASUSTek       | F6A                         | [6626d18284](https://bsd-hardware.info/?probe=6626d18284) | Aug 08, 2022 |
| HP            | 250 G6 Notebook PC          | [511d057c70](https://bsd-hardware.info/?probe=511d057c70) | Jul 27, 2022 |
| HP            | OMEN by Laptop              | [25e43be096](https://bsd-hardware.info/?probe=25e43be096) | Jul 17, 2022 |
| Dell          | Latitude E5450              | [5f1183ab0b](https://bsd-hardware.info/?probe=5f1183ab0b) | Jul 14, 2022 |
| Dell          | Latitude E5450              | [1080ed5654](https://bsd-hardware.info/?probe=1080ed5654) | Jul 14, 2022 |
| Acer          | Aspire E5-571G              | [56fae2295e](https://bsd-hardware.info/?probe=56fae2295e) | Jul 08, 2022 |
| HP            | 250 G6 Notebook PC          | [bbe1d21883](https://bsd-hardware.info/?probe=bbe1d21883) | Jul 07, 2022 |
| Dell          | Inspiron 15-3552            | [8cdc3bd7ab](https://bsd-hardware.info/?probe=8cdc3bd7ab) | Jul 01, 2022 |
| Apple         | MacBook6,1                  | [a6d3cf9a30](https://bsd-hardware.info/?probe=a6d3cf9a30) | Jun 20, 2022 |
| Acer          | Aspire A315-34              | [90927fa85a](https://bsd-hardware.info/?probe=90927fa85a) | Jun 20, 2022 |
| HP            | Unknown                     | [11ef8f9a92](https://bsd-hardware.info/?probe=11ef8f9a92) | Jun 19, 2022 |
| Lenovo        | ThinkPad X250 20CLS23500    | [6a8b44bc47](https://bsd-hardware.info/?probe=6a8b44bc47) | Jun 03, 2022 |
| Lenovo        | IdeaPad 3 15IGL05 82BU      | [6a6450f264](https://bsd-hardware.info/?probe=6a6450f264) | May 30, 2022 |
| Timi          | TM1701                      | [a28220d11f](https://bsd-hardware.info/?probe=a28220d11f) | May 22, 2022 |
| Dell          | Studio 1747                 | [7ae292b282](https://bsd-hardware.info/?probe=7ae292b282) | May 21, 2022 |
| TUXEDO        | Aura 15 Gen1                | [20814a930a](https://bsd-hardware.info/?probe=20814a930a) | May 18, 2022 |
| Packard Be... | EasyNote_MX52-B-071         | [277c9e0a0a](https://bsd-hardware.info/?probe=277c9e0a0a) | May 08, 2022 |
| Dell          | Inspiron 5559               | [a7111b84cb](https://bsd-hardware.info/?probe=a7111b84cb) | May 08, 2022 |
| Lenovo        | ThinkPad X270 W10DG 20K5... | [f02e4345ff](https://bsd-hardware.info/?probe=f02e4345ff) | Apr 30, 2022 |
| Apple         | MacBookPro5,5               | [4b5603b38b](https://bsd-hardware.info/?probe=4b5603b38b) | Apr 29, 2022 |
| ASUSTek       | 1001PX                      | [b47a498f2e](https://bsd-hardware.info/?probe=b47a498f2e) | Apr 08, 2022 |
| Dell          | Latitude E5470              | [a7d087a428](https://bsd-hardware.info/?probe=a7d087a428) | Apr 05, 2022 |
| Sony          | VGN-AW21S_B                 | [11edcb4e82](https://bsd-hardware.info/?probe=11edcb4e82) | Apr 03, 2022 |
| PCSTICK       | Unknown                     | [6f9f24b262](https://bsd-hardware.info/?probe=6f9f24b262) | Mar 29, 2022 |
| Dell          | Latitude E6540              | [41e5f63a69](https://bsd-hardware.info/?probe=41e5f63a69) | Mar 26, 2022 |
| ASUSTek       | UX31E                       | [93655cdd83](https://bsd-hardware.info/?probe=93655cdd83) | Mar 21, 2022 |
| HP            | EliteBook 850 G3            | [1ae8321767](https://bsd-hardware.info/?probe=1ae8321767) | Mar 20, 2022 |
| Gateway       | NE56R                       | [87d177b9da](https://bsd-hardware.info/?probe=87d177b9da) | Mar 20, 2022 |
| HUAWEI        | BOD-WXX9                    | [65454bcc92](https://bsd-hardware.info/?probe=65454bcc92) | Mar 06, 2022 |
| Acer          | V5-131                      | [076ca78b3f](https://bsd-hardware.info/?probe=076ca78b3f) | Feb 25, 2022 |
| Dell          | Latitude 7480               | [8a0388b49d](https://bsd-hardware.info/?probe=8a0388b49d) | Feb 23, 2022 |
| PCSTICK       | Unknown                     | [b76b5c9670](https://bsd-hardware.info/?probe=b76b5c9670) | Feb 21, 2022 |
| ASUSTek       | 1001PX                      | [d171d1ec99](https://bsd-hardware.info/?probe=d171d1ec99) | Feb 17, 2022 |
| Lenovo        | Legion 5 15ARH05 82B5       | [1a13b7bfd1](https://bsd-hardware.info/?probe=1a13b7bfd1) | Feb 16, 2022 |
| Acer          | Aspire 5750G                | [bd22fc8a49](https://bsd-hardware.info/?probe=bd22fc8a49) | Feb 15, 2022 |
| Timi          | RedmiBook Pro 15            | [7716f59380](https://bsd-hardware.info/?probe=7716f59380) | Feb 14, 2022 |
| Timi          | RedmiBook Pro 15            | [fdd0ab95ed](https://bsd-hardware.info/?probe=fdd0ab95ed) | Feb 14, 2022 |
| Apple         | MacBook5,2                  | [29756c2371](https://bsd-hardware.info/?probe=29756c2371) | Feb 13, 2022 |
| Sony          | VPCEB1J1E                   | [9151a22f13](https://bsd-hardware.info/?probe=9151a22f13) | Jan 30, 2022 |
| Lenovo        | ThinkPad T440 20B7A0B7MS    | [be30041f4e](https://bsd-hardware.info/?probe=be30041f4e) | Jan 10, 2022 |
| Lenovo        | G480 20149                  | [adc6b44cc8](https://bsd-hardware.info/?probe=adc6b44cc8) | Jan 09, 2022 |
| HP            | EliteBook 820 G1            | [362940acbb](https://bsd-hardware.info/?probe=362940acbb) | Jan 03, 2022 |

System
------

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart_bsd/os_arch.svg)


| Name  | Notebooks | Percent |
|-------|-----------|---------|
| amd64 | 85        | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart_bsd/os_de.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| helloDesktop | 80        | 94.12%  |
| GNOME        | 2         | 2.35%   |
| Window Maker | 1         | 1.18%   |
| IceWM        | 1         | 1.18%   |
| Cinnamon     | 1         | 1.18%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart_bsd/os_display_server.svg)


| Name | Notebooks | Percent |
|------|-----------|---------|
| X11  | 85        | 100%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart_bsd/os_display_manager.svg)


| Name | Notebooks | Percent |
|------|-----------|---------|
| SLiM | 84        | 98.82%  |
| GDM  | 1         | 1.18%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart_bsd/os_lang.svg)


| Lang  | Notebooks | Percent |
|-------|-----------|---------|
| en_US | 49        | 57.65%  |
| en    | 18        | 21.18%  |
| ru    | 6         | 7.06%   |
| de    | 4         | 4.71%   |
| es_ES | 2         | 2.35%   |
| es    | 2         | 2.35%   |
| zh_CN | 1         | 1.18%   |
| ru_RU | 1         | 1.18%   |
| pt    | 1         | 1.18%   |
| fr    | 1         | 1.18%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart_bsd/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 85        | 100%    |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart_bsd/os_filesystem.svg)


| Type   | Notebooks | Percent |
|--------|-----------|---------|
| Cd9660 | 56        | 65.88%  |
| Zfs    | 28        | 32.94%  |
| Ufs    | 1         | 1.18%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart_bsd/os_part_scheme.svg)


| Type | Notebooks | Percent |
|------|-----------|---------|
| GPT  | 85        | 100%    |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart_bsd/node_vendor.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Lenovo              | 16        | 18.82%  |
| Dell                | 16        | 18.82%  |
| Hewlett-Packard     | 12        | 14.12%  |
| Apple               | 6         | 7.06%   |
| ASUSTek Computer    | 5         | 5.88%   |
| Acer                | 5         | 5.88%   |
| Toshiba             | 3         | 3.53%   |
| Timi                | 3         | 3.53%   |
| MSI                 | 3         | 3.53%   |
| TUXEDO              | 2         | 2.35%   |
| Sony                | 2         | 2.35%   |
| Packard Bell        | 2         | 2.35%   |
| Google              | 2         | 2.35%   |
| Star Labs           | 1         | 1.18%   |
| Samsung Electronics | 1         | 1.18%   |
| PCSTICK             | 1         | 1.18%   |
| Panasonic           | 1         | 1.18%   |
| Kraftway            | 1         | 1.18%   |
| HUAWEI              | 1         | 1.18%   |
| Gateway             | 1         | 1.18%   |
| Fujitsu             | 1         | 1.18%   |

Model
-----

Motherboard model

![Model](./images/pie_chart_bsd/node_model.svg)


| Name                                         | Notebooks | Percent |
|----------------------------------------------|-----------|---------|
| MSI PS63 Modern 8M                           | 2         | 2.35%   |
| HP 250 G6 Notebook PC                        | 2         | 2.35%   |
| Apple MacBookAir5,1                          | 2         | 2.35%   |
| Apple MacBook5,2                             | 2         | 2.35%   |
| Unknown                                      | 2         | 2.35%   |
| TUXEDO Pulse 14 Gen1                         | 1         | 1.18%   |
| TUXEDO Aura 15 Gen1                          | 1         | 1.18%   |
| Toshiba TECRA Z40-C-12Z                      | 1         | 1.18%   |
| Toshiba Satellite S55t-B                     | 1         | 1.18%   |
| Toshiba PORTEGE Z930                         | 1         | 1.18%   |
| Timi TM1701                                  | 1         | 1.18%   |
| Timi TM1607                                  | 1         | 1.18%   |
| Timi RedmiBook Pro 15                        | 1         | 1.18%   |
| Star Labs StarBook                           | 1         | 1.18%   |
| Sony VPCEB1J1E                               | 1         | 1.18%   |
| Sony VGN-AW21S_B                             | 1         | 1.18%   |
| Samsung 340XAA/350XAA/550XAA                 | 1         | 1.18%   |
| Panasonic CF-C1BWFAZ1M                       | 1         | 1.18%   |
| Packard Bell EasyNote_MX52-B-071             | 1         | 1.18%   |
| Packard Bell DOT S                           | 1         | 1.18%   |
| MSI Modern 15 A5M                            | 1         | 1.18%   |
| Lenovo ThinkPad X270 W10DG 20K5S0BB00        | 1         | 1.18%   |
| Lenovo ThinkPad X250 20CLS23500              | 1         | 1.18%   |
| Lenovo ThinkPad X250 20CLS1WP01              | 1         | 1.18%   |
| Lenovo ThinkPad X1 Extreme Gen 4i 20Y5001DMX | 1         | 1.18%   |
| Lenovo ThinkPad X1 Carbon 3448AWU            | 1         | 1.18%   |
| Lenovo ThinkPad W541 20EF000NUS              | 1         | 1.18%   |
| Lenovo ThinkPad T440 20B7A0B7MS              | 1         | 1.18%   |
| Lenovo ThinkPad T420 4178A72                 | 1         | 1.18%   |
| Lenovo ThinkPad P51 20HH001RMX               | 1         | 1.18%   |
| Lenovo ThinkPad P50 20EN0041MX               | 1         | 1.18%   |
| Lenovo ThinkPad P15v Gen 2i 21AAS28T00       | 1         | 1.18%   |
| Lenovo ThinkPad E585 20KV0010US              | 1         | 1.18%   |
| Lenovo Legion 5 15ARH05 82B5                 | 1         | 1.18%   |
| Lenovo IdeaPad 3 15IGL05 82BU                | 1         | 1.18%   |
| Lenovo G500 20236                            | 1         | 1.18%   |
| Lenovo G480 20149                            | 1         | 1.18%   |
| Kraftway KW10T                               | 1         | 1.18%   |
| HUAWEI BOD-WXX9                              | 1         | 1.18%   |
| HP ZBook 15 G4                               | 1         | 1.18%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart_bsd/node_model_family.svg)


| Name                   | Notebooks | Percent |
|------------------------|-----------|---------|
| Lenovo ThinkPad        | 12        | 14.12%  |
| Dell Latitude          | 9         | 10.59%  |
| Dell Inspiron          | 5         | 5.88%   |
| Acer Aspire            | 5         | 5.88%   |
| HP EliteBook           | 4         | 4.71%   |
| MSI PS63               | 2         | 2.35%   |
| HP 250                 | 2         | 2.35%   |
| Apple MacBookAir5      | 2         | 2.35%   |
| Apple MacBook5         | 2         | 2.35%   |
| Unknown                | 2         | 2.35%   |
| TUXEDO Pulse           | 1         | 1.18%   |
| TUXEDO Aura            | 1         | 1.18%   |
| Toshiba TECRA          | 1         | 1.18%   |
| Toshiba Satellite      | 1         | 1.18%   |
| Toshiba PORTEGE        | 1         | 1.18%   |
| Timi TM1701            | 1         | 1.18%   |
| Timi TM1607            | 1         | 1.18%   |
| Timi RedmiBook         | 1         | 1.18%   |
| Star Labs StarBook     | 1         | 1.18%   |
| Sony VPCEB1J1E         | 1         | 1.18%   |
| Sony VGN-AW21S         | 1         | 1.18%   |
| Samsung 340XAA         | 1         | 1.18%   |
| Panasonic CF-C1BWFAZ1M | 1         | 1.18%   |
| Packard Bell EasyNote  | 1         | 1.18%   |
| Packard Bell DOT       | 1         | 1.18%   |
| MSI Modern             | 1         | 1.18%   |
| Lenovo Legion          | 1         | 1.18%   |
| Lenovo IdeaPad         | 1         | 1.18%   |
| Lenovo G500            | 1         | 1.18%   |
| Lenovo G480            | 1         | 1.18%   |
| Kraftway KW10T         | 1         | 1.18%   |
| HUAWEI BOD-WXX9        | 1         | 1.18%   |
| HP ZBook               | 1         | 1.18%   |
| HP Pavilion            | 1         | 1.18%   |
| HP OMEN                | 1         | 1.18%   |
| HP Laptop              | 1         | 1.18%   |
| HP ENVY                | 1         | 1.18%   |
| Google Edgar           | 1         | 1.18%   |
| Google Cave            | 1         | 1.18%   |
| Gateway NE56R          | 1         | 1.18%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart_bsd/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2020 | 11        | 12.94%  |
| 2019 | 11        | 12.94%  |
| 2014 | 7         | 8.24%   |
| 2022 | 6         | 7.06%   |
| 2017 | 6         | 7.06%   |
| 2015 | 6         | 7.06%   |
| 2012 | 6         | 7.06%   |
| 2018 | 5         | 5.88%   |
| 2013 | 5         | 5.88%   |
| 2021 | 4         | 4.71%   |
| 2016 | 4         | 4.71%   |
| 2011 | 4         | 4.71%   |
| 2009 | 4         | 4.71%   |
| 2010 | 3         | 3.53%   |
| 2023 | 1         | 1.18%   |
| 2008 | 1         | 1.18%   |
| 2007 | 1         | 1.18%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart_bsd/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 85        | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart_bsd/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 82        | 96.47%  |
| Yes  | 3         | 3.53%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart_bsd/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 29        | 34.12%  |
| 8.01-16.0   | 27        | 31.76%  |
| 16.01-24.0  | 17        | 20%     |
| 32.01-64.0  | 6         | 7.06%   |
| 2.01-3.0    | 3         | 3.53%   |
| 3.01-4.0    | 1         | 1.18%   |
| 24.01-32.0  | 1         | 1.18%   |
| 64.01-256.0 | 1         | 1.18%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart_bsd/node_ram_used.svg)


| Used GB  | Notebooks | Percent |
|----------|-----------|---------|
| 0.01-0.5 | 53        | 62.35%  |
| 0.51-1.0 | 19        | 22.35%  |
| 1.01-2.0 | 11        | 12.94%  |
| 2.01-3.0 | 2         | 2.35%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart_bsd/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 60        | 70.59%  |
| 2      | 17        | 20%     |
| 0      | 6         | 7.06%   |
| 3      | 2         | 2.35%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart_bsd/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 64        | 75.29%  |
| Yes       | 21        | 24.71%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart_bsd/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 66        | 77.65%  |
| No        | 19        | 22.35%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart_bsd/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 83        | 97.65%  |
| No        | 2         | 2.35%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart_bsd/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 62        | 72.94%  |
| No        | 23        | 27.06%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart_bsd/node_location.svg)


| Country                | Notebooks | Percent |
|------------------------|-----------|---------|
| USA                    | 13        | 15.29%  |
| Russia                 | 10        | 11.76%  |
| Germany                | 9         | 10.59%  |
| China                  | 4         | 4.71%   |
| Brazil                 | 4         | 4.71%   |
| Ukraine                | 3         | 3.53%   |
| Spain                  | 3         | 3.53%   |
| France                 | 3         | 3.53%   |
| UK                     | 2         | 2.35%   |
| Sweden                 | 2         | 2.35%   |
| Mexico                 | 2         | 2.35%   |
| Italy                  | 2         | 2.35%   |
| Ireland                | 2         | 2.35%   |
| Hungary                | 2         | 2.35%   |
| Canada                 | 2         | 2.35%   |
| Argentina              | 2         | 2.35%   |
| Venezuela              | 1         | 1.18%   |
| Uruguay                | 1         | 1.18%   |
| UAE                    | 1         | 1.18%   |
| Taiwan                 | 1         | 1.18%   |
| Slovenia               | 1         | 1.18%   |
| Slovakia               | 1         | 1.18%   |
| Romania                | 1         | 1.18%   |
| Portugal               | 1         | 1.18%   |
| Poland                 | 1         | 1.18%   |
| Peru                   | 1         | 1.18%   |
| Panama                 | 1         | 1.18%   |
| Norway                 | 1         | 1.18%   |
| Netherlands            | 1         | 1.18%   |
| Kenya                  | 1         | 1.18%   |
| Georgia                | 1         | 1.18%   |
| Czechia                | 1         | 1.18%   |
| Costa Rica             | 1         | 1.18%   |
| Bosnia and Herzegovina | 1         | 1.18%   |
| Belarus                | 1         | 1.18%   |
| Albania                | 1         | 1.18%   |

City
----

Geographic location (city)

![City](./images/pie_chart_bsd/node_city.svg)


| City                 | Notebooks | Percent |
|----------------------|-----------|---------|
| Moscow               | 4         | 4.71%   |
| Perm                 | 2         | 2.35%   |
| Dublin               | 2         | 2.35%   |
| Dover                | 2         | 2.35%   |
| Blomberg             | 2         | 2.35%   |
| Berlin               | 2         | 2.35%   |
| Yunlin               | 1         | 1.18%   |
| Weifang              | 1         | 1.18%   |
| Warendorf            | 1         | 1.18%   |
| Vladivostok          | 1         | 1.18%   |
| Villemomble          | 1         | 1.18%   |
| Vidnoye              | 1         | 1.18%   |
| Vancouver            | 1         | 1.18%   |
| Valencia             | 1         | 1.18%   |
| Utrecht              | 1         | 1.18%   |
| Ufa                  | 1         | 1.18%   |
| Szeged               | 1         | 1.18%   |
| Shenzhen             | 1         | 1.18%   |
| Sayago               | 1         | 1.18%   |
| Sarajevo             | 1         | 1.18%   |
| Sao Paulo            | 1         | 1.18%   |
| San José            | 1         | 1.18%   |
| San Carlos del Zulia | 1         | 1.18%   |
| Roscommon            | 1         | 1.18%   |
| Rio das Ostras       | 1         | 1.18%   |
| Rho                  | 1         | 1.18%   |
| Redondela            | 1         | 1.18%   |
| Queensbury           | 1         | 1.18%   |
| Porto                | 1         | 1.18%   |
| Pilsen               | 1         | 1.18%   |
| Panama City          | 1         | 1.18%   |
| Ottawa               | 1         | 1.18%   |
| Ostrołęka          | 1         | 1.18%   |
| Orizaba              | 1         | 1.18%   |
| Odessa               | 1         | 1.18%   |
| Oakdale              | 1         | 1.18%   |
| Nesttun              | 1         | 1.18%   |
| Nanticoke            | 1         | 1.18%   |
| Nairobi              | 1         | 1.18%   |
| Muskego              | 1         | 1.18%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart_bsd/drive_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 15        | 15     | 15%     |
| Samsung Electronics | 13        | 15     | 13%     |
| WDC                 | 10        | 10     | 10%     |
| Kingston            | 10        | 10     | 10%     |
| Toshiba             | 8         | 8      | 8%      |
| Intel               | 6         | 6      | 6%      |
| SK hynix            | 4         | 4      | 4%      |
| SanDisk             | 4         | 4      | 4%      |
| Hitachi             | 4         | 4      | 4%      |
| A-DATA Technology   | 3         | 3      | 3%      |
| PNY                 | 2         | 2      | 2%      |
| Patriot             | 2         | 2      | 2%      |
| KIOXIA              | 2         | 2      | 2%      |
| Fujitsu             | 2         | 2      | 2%      |
| Crucial             | 2         | 2      | 2%      |
| Apple               | 2         | 2      | 2%      |
| Verbatim            | 1         | 1      | 1%      |
| Transcend           | 1         | 1      | 1%      |
| Star Drive          | 1         | 1      | 1%      |
| SSSTC               | 1         | 1      | 1%      |
| OWC                 | 1         | 1      | 1%      |
| OCZ                 | 1         | 1      | 1%      |
| Lenovo              | 1         | 1      | 1%      |
| KingSpec            | 1         | 1      | 1%      |
| GOODRAM             | 1         | 1      | 1%      |
| FORESEE             | 1         | 1      | 1%      |
| Dogfish             | 1         | 1      | 1%      |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart_bsd/drive_model.svg)


| Model                                     | Notebooks | Percent |
|-------------------------------------------|-----------|---------|
| Seagate ST1000LM035-1RK172 1TB            | 4         | 3.92%   |
| Seagate ST1000LM024 HN-M101MBB 1TB        | 3         | 2.94%   |
| Toshiba MQ01ABF050 500GB                  | 2         | 1.96%   |
| Samsung MZNTY128HDHP-00000 128GB          | 2         | 1.96%   |
| PNY CS900 240GB SSD                       | 2         | 1.96%   |
| Patriot Burst 120GB                       | 2         | 1.96%   |
| Kingston SA400S37120G 120GB               | 2         | 1.96%   |
| Apple SSD TS128E 121GB                    | 2         | 1.96%   |
| A-DATA SX6000LNP 512GB                    | 2         | 1.96%   |
| WDC WDS240G2G0B-00EPW0 240GB              | 1         | 0.98%   |
| WDC WDS100T2B0A-00SM50 1TB                | 1         | 0.98%   |
| WDC WDBNCE5000PNC 500GB                   | 1         | 0.98%   |
| WDC WD5000LPCX-60VHAT0 500GB              | 1         | 0.98%   |
| WDC WD5000BPVT-22A1YT0 500GB              | 1         | 0.98%   |
| WDC WD2500BEVT-35A23T0 250GB              | 1         | 0.98%   |
| WDC WD10SPZX-35Z10T0 1TB                  | 1         | 0.98%   |
| WDC WD10JPVX-75JC3T0 1TB                  | 1         | 0.98%   |
| WDC WD10JPVX-22JC3T0 1TB                  | 1         | 0.98%   |
| WDC PC SN530 SDBPNPZ-512G-1027 512GB      | 1         | 0.98%   |
| Verbatim Vi550 S3 SSD 512GB               | 1         | 0.98%   |
| Transcend TS120GMTS420S 120GB             | 1         | 0.98%   |
| Toshiba THNSNF128GMCS 128GB               | 1         | 0.98%   |
| Toshiba MQ01ABD100 1TB                    | 1         | 0.98%   |
| Toshiba MK8034GSX 80GB                    | 1         | 0.98%   |
| Toshiba MK3261GSYN 320GB                  | 1         | 0.98%   |
| Toshiba KXG60ZNV256G NVMe 256GB           | 1         | 0.98%   |
| Toshiba KSG60ZMV256G 256GB                | 1         | 0.98%   |
| Star Drive PCIe SSD 1TB                   | 1         | 0.98%   |
| SSSTC CL1-4D128 128GB                     | 1         | 0.98%   |
| SK hynix SKHynix_HFM512GDHTNI-87A0B 512GB | 1         | 0.98%   |
| SK hynix SC311 SATA 256GB                 | 1         | 0.98%   |
| SK hynix PC601 NVMe 512GB                 | 1         | 0.98%   |
| SK hynix BC711 NVMe 512GB                 | 1         | 0.98%   |
| Seagate ST9500420AS 500GB                 | 1         | 0.98%   |
| Seagate ST9160821AS 160GB                 | 1         | 0.98%   |
| Seagate ST500LT012-9WS142 500GB           | 1         | 0.98%   |
| Seagate ST500LT012-1DG142 500GB           | 1         | 0.98%   |
| Seagate ST500LM034-2GH17A 500GB           | 1         | 0.98%   |
| Seagate ST500LM000-1EJ162 500GB           | 1         | 0.98%   |
| Seagate ST320LT014-9YK142 320GB           | 1         | 0.98%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart_bsd/drive_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 15        | 15     | 48.39%  |
| WDC     | 6         | 6      | 19.35%  |
| Toshiba | 5         | 5      | 16.13%  |
| Hitachi | 4         | 4      | 12.9%   |
| Fujitsu | 1         | 1      | 3.23%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart_bsd/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 9         | 9      | 18%     |
| Kingston            | 8         | 8      | 16%     |
| Intel               | 5         | 5      | 10%     |
| SanDisk             | 4         | 4      | 8%      |
| WDC                 | 3         | 3      | 6%      |
| Toshiba             | 2         | 2      | 4%      |
| PNY                 | 2         | 2      | 4%      |
| Patriot             | 2         | 2      | 4%      |
| Crucial             | 2         | 2      | 4%      |
| Apple               | 2         | 2      | 4%      |
| Verbatim            | 1         | 1      | 2%      |
| Transcend           | 1         | 1      | 2%      |
| SK hynix            | 1         | 1      | 2%      |
| OWC                 | 1         | 1      | 2%      |
| OCZ                 | 1         | 1      | 2%      |
| KingSpec            | 1         | 1      | 2%      |
| GOODRAM             | 1         | 1      | 2%      |
| Fujitsu             | 1         | 1      | 2%      |
| FORESEE             | 1         | 1      | 2%      |
| Dogfish             | 1         | 1      | 2%      |
| A-DATA Technology   | 1         | 1      | 2%      |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart_bsd/drive_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SSD  | 42        | 50     | 46.67%  |
| HDD  | 27        | 31     | 30%     |
| NVMe | 21        | 21     | 23.33%  |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart_bsd/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 66        | 81     | 75.86%  |
| NVMe | 21        | 21     | 24.14%  |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart_bsd/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 54        | 66     | 79.41%  |
| 0.51-1.0   | 13        | 14     | 19.12%  |
| 1.01-2.0   | 1         | 1      | 1.47%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart_bsd/drive_space_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 1-20       | 49        | 57.65%  |
| 101-250    | 15        | 17.65%  |
| 251-500    | 10        | 11.76%  |
| 501-1000   | 6         | 7.06%   |
| 21-50      | 3         | 3.53%   |
| 51-100     | 1         | 1.18%   |
| Unknown    | 1         | 1.18%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart_bsd/drive_space_used.svg)


| Used GB | Notebooks | Percent |
|---------|-----------|---------|
| 1-20    | 81        | 95.29%  |
| 21-50   | 1         | 1.18%   |
| 101-250 | 1         | 1.18%   |
| 51-100  | 1         | 1.18%   |
| Unknown | 1         | 1.18%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart_bsd/drive_malfunc.svg)


| Model                                        | Notebooks | Drives | Percent |
|----------------------------------------------|-----------|--------|---------|
| WDC WD5000LPCX-60VHAT0 500GB                 | 1         | 1      | 5.56%   |
| WDC WD2500BEVT-35A23T0 250GB                 | 1         | 1      | 5.56%   |
| Toshiba MQ01ABF050 500GB                     | 1         | 1      | 5.56%   |
| Toshiba MQ01ABD100 1TB                       | 1         | 1      | 5.56%   |
| Toshiba MK8034GSX 80GB                       | 1         | 1      | 5.56%   |
| Toshiba MK3261GSYN 320GB                     | 1         | 1      | 5.56%   |
| Seagate ST9160821AS 160GB                    | 1         | 1      | 5.56%   |
| Seagate ST500LT012-9WS142 500GB              | 1         | 1      | 5.56%   |
| Seagate ST500LM000-1EJ162 500GB              | 1         | 1      | 5.56%   |
| Seagate ST320LT014-9YK142 320GB              | 1         | 1      | 5.56%   |
| Seagate ST320LT012-9WS14C 320GB              | 1         | 1      | 5.56%   |
| Seagate ST1000LM024 HN-M101MBB 1TB           | 1         | 1      | 5.56%   |
| SanDisk SSD PLUS 240GB                       | 1         | 1      | 5.56%   |
| Samsung Electronics MZMPA128HMFU-000H1 128GB | 1         | 1      | 5.56%   |
| Hitachi HTS727550A9E364 500GB                | 1         | 1      | 5.56%   |
| Hitachi HTS545025B9SA02 250GB                | 1         | 1      | 5.56%   |
| Hitachi HTS541612J9SA00 120GB                | 1         | 1      | 5.56%   |
| Fujitsu MHZ2160BH FFS G1 160GB               | 1         | 1      | 5.56%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart_bsd/drive_malfunc_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 6         | 6      | 33.33%  |
| Toshiba             | 4         | 4      | 22.22%  |
| Hitachi             | 3         | 3      | 16.67%  |
| WDC                 | 2         | 2      | 11.11%  |
| SanDisk             | 1         | 1      | 5.56%   |
| Samsung Electronics | 1         | 1      | 5.56%   |
| Fujitsu             | 1         | 1      | 5.56%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart_bsd/drive_malfunc_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 6         | 6      | 37.5%   |
| Toshiba | 4         | 4      | 25%     |
| Hitachi | 3         | 3      | 18.75%  |
| WDC     | 2         | 2      | 12.5%   |
| Fujitsu | 1         | 1      | 6.25%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart_bsd/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 14        | 16     | 87.5%   |
| SSD  | 2         | 2      | 12.5%   |

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


| Status  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Works   | 66        | 84     | 81.48%  |
| Malfunc | 15        | 18     | 18.52%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart_bsd/storage_vendor.svg)


| Vendor                         | Notebooks | Percent |
|--------------------------------|-----------|---------|
| Intel                          | 62        | 65.26%  |
| AMD                            | 7         | 7.37%   |
| Samsung Electronics            | 6         | 6.32%   |
| Nvidia                         | 4         | 4.21%   |
| SK hynix                       | 3         | 3.16%   |
| SanDisk                        | 2         | 2.11%   |
| Realtek Semiconductor          | 2         | 2.11%   |
| KIOXIA                         | 2         | 2.11%   |
| Kingston Technology Company    | 2         | 2.11%   |
| Toshiba                        | 1         | 1.05%   |
| Solid State Storage Technology | 1         | 1.05%   |
| Phison Electronics             | 1         | 1.05%   |
| Lenovo                         | 1         | 1.05%   |
| JMicron Technology             | 1         | 1.05%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart_bsd/storage_model.svg)


| Model                                                                            | Notebooks | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 11        | 11.22%  |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 9         | 9.18%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 6         | 6.12%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 6         | 6.12%   |
| AMD FCH SATA Controller [AHCI mode]                                              | 5         | 5.1%    |
| Unknown                                                                          | 5         | 5.1%    |
| Nvidia MCP79 AHCI Controller                                                     | 4         | 4.08%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 4         | 4.08%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 3         | 3.06%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]    | 3         | 3.06%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                | 3         | 3.06%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                    | 2         | 2.04%   |
| Intel SATA Controller [RAID mode]                                                | 2         | 2.04%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                               | 2         | 2.04%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                           | 2         | 2.04%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]            | 2         | 2.04%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 2         | 2.04%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 2         | 2.04%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                   | 2         | 2.04%   |
| Toshiba XG6 NVMe SSD Controller                                                  | 1         | 1.02%   |
| SK hynix hynix unknown                                                           | 1         | 1.02%   |
| SK hynix Gold P31/PC711 NVMe Solid State Drive                                   | 1         | 1.02%   |
| SK hynix BC511                                                                   | 1         | 1.02%   |
| SanDisk WD PC SN810 / Black SN850 NVMe SSD                                       | 1         | 1.02%   |
| SanDisk WD Blue SN550 NVMe SSD                                                   | 1         | 1.02%   |
| Samsung NVMe SSD Controller 980                                                  | 1         | 1.02%   |
| Phison E18 PCIe4 NVMe Controller                                                 | 1         | 1.02%   |
| Lenovo unknown                                                                   | 1         | 1.02%   |
| KIOXIA NVMe SSD Controller BG4                                                   | 1         | 1.02%   |
| Kingston Company OM3PDP3 NVMe SSD                                                | 1         | 1.02%   |
| JMicron JMB368 IDE controller                                                    | 1         | 1.02%   |
| Intel SSD 660P Series                                                            | 1         | 1.02%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                            | 1         | 1.02%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller         | 1         | 1.02%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                | 1         | 1.02%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 1         | 1.02%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                           | 1         | 1.02%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                   | 1         | 1.02%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                | 1         | 1.02%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                             | 1         | 1.02%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart_bsd/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 68        | 70.83%  |
| NVMe | 21        | 21.88%  |
| RAID | 4         | 4.17%   |
| IDE  | 3         | 3.13%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart_bsd/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 76        | 89.41%  |
| AMD    | 9         | 10.59%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart_bsd/cpu_model.svg)


| Model                                       | Notebooks | Percent |
|---------------------------------------------|-----------|---------|
| Intel Core i5-5300U CPU @ 2.30GHz           | 3         | 3.53%   |
| Intel Core i5-2520M CPU @ 2.50GHz           | 3         | 3.53%   |
| Intel Core i7-8565U CPU @ 1.80GHz           | 2         | 2.35%   |
| Intel Core i7-7820HQ CPU @ 2.90GHz          | 2         | 2.35%   |
| Intel Core i7-6600U CPU @ 2.60GHz           | 2         | 2.35%   |
| Intel Core i7-4810MQ CPU @ 2.80GHz          | 2         | 2.35%   |
| Intel Core i5-7200U CPU @ 2.50GHz           | 2         | 2.35%   |
| Intel Core i5-6440HQ CPU @ 2.60GHz          | 2         | 2.35%   |
| Intel Core i5-6200U CPU @ 2.30GHz           | 2         | 2.35%   |
| Intel Core i5-5200U CPU @ 2.20GHz           | 2         | 2.35%   |
| Intel Core i5-4210U CPU @ 1.70GHz           | 2         | 2.35%   |
| Intel Core i5-3317U CPU @ 1.70GHz           | 2         | 2.35%   |
| Intel Core 2 Duo CPU P7450 @ 2.13GHz        | 2         | 2.35%   |
| AMD Ryzen 7 4800H with Radeon Graphics      | 2         | 2.35%   |
| Intel Xeon CPU E3-1505M v5 @ 2.80GHz        | 1         | 1.18%   |
| Intel Pentium Silver N5000 CPU @ 1.10GHz    | 1         | 1.18%   |
| Intel Pentium Dual-Core CPU T4200 @ 2.00GHz | 1         | 1.18%   |
| Intel Pentium CPU N4200 @ 1.10GHz           | 1         | 1.18%   |
| Intel Pentium CPU N3700 @ 1.60GHz           | 1         | 1.18%   |
| Intel Pentium CPU 4417U @ 2.30GHz           | 1         | 1.18%   |
| Intel CPU Version                           | 1         | 1.18%   |
| Intel Core m3-7Y30 CPU @ 1.00GHz            | 1         | 1.18%   |
| Intel Core m3-6Y30 CPU @ 0.90GHz            | 1         | 1.18%   |
| Intel Core i7-9850H CPU @ 2.60GHz           | 1         | 1.18%   |
| Intel Core i7-8650U CPU @ 1.90GHz           | 1         | 1.18%   |
| Intel Core i7-8550U CPU @ 1.80GHz           | 1         | 1.18%   |
| Intel Core i7-6500U CPU @ 2.50GHz           | 1         | 1.18%   |
| Intel Core i7-5500U CPU @ 2.40GHz           | 1         | 1.18%   |
| Intel Core i7-3667U CPU @ 2.00GHz           | 1         | 1.18%   |
| Intel Core i7-2677M CPU @ 1.80GHz           | 1         | 1.18%   |
| Intel Core i7-2620M CPU @ 2.70GHz           | 1         | 1.18%   |
| Intel Core i5-8365U CPU @ 1.60GHz           | 1         | 1.18%   |
| Intel Core i5-8250U CPU @ 1.60GHz           | 1         | 1.18%   |
| Intel Core i5-6300U CPU @ 2.40GHz           | 1         | 1.18%   |
| Intel Core i5-6300HQ CPU @ 2.30GHz          | 1         | 1.18%   |
| Intel Core i5-4310U CPU @ 2.00GHz           | 1         | 1.18%   |
| Intel Core i5-4300U CPU @ 1.90GHz           | 1         | 1.18%   |
| Intel Core i5-3437U CPU @ 1.90GHz           | 1         | 1.18%   |
| Intel Core i5-3210M CPU @ 2.50GHz           | 1         | 1.18%   |
| Intel Core i5-2540M CPU @ 2.60GHz           | 1         | 1.18%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart_bsd/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 28        | 32.94%  |
| Intel Core i7           | 16        | 18.82%  |
| Other                   | 6         | 7.06%   |
| Intel Core i3           | 5         | 5.88%   |
| Intel Core 2 Duo        | 5         | 5.88%   |
| Intel Celeron           | 4         | 4.71%   |
| Intel Atom              | 4         | 4.71%   |
| Intel Pentium           | 3         | 3.53%   |
| AMD Ryzen 7             | 3         | 3.53%   |
| Intel Core m3           | 2         | 2.35%   |
| Intel Xeon              | 1         | 1.18%   |
| Intel Pentium Silver    | 1         | 1.18%   |
| Intel Pentium Dual-Core | 1         | 1.18%   |
| AMD V120                | 1         | 1.18%   |
| AMD Ryzen 5             | 1         | 1.18%   |
| AMD Ryzen 3             | 1         | 1.18%   |
| AMD Athlon 64 X2        | 1         | 1.18%   |
| AMD A8                  | 1         | 1.18%   |
| AMD A10                 | 1         | 1.18%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart_bsd/cpu_cores.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 46        | 54.12%  |
| 4       | 25        | 29.41%  |
| Unknown | 4         | 4.71%   |
| 16      | 3         | 3.53%   |
| 8       | 3         | 3.53%   |
| 1       | 2         | 2.35%   |
| 12      | 1         | 1.18%   |
| 6       | 1         | 1.18%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart_bsd/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 82        | 96.47%  |
| 2      | 3         | 3.53%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart_bsd/cpu_threads.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 57        | 67.06%  |
| 1       | 24        | 28.24%  |
| Unknown | 4         | 4.71%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart_bsd/cpu_microarch.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| KabyLake      | 14        | 16.47%  |
| Skylake       | 11        | 12.94%  |
| SandyBridge   | 8         | 9.41%   |
| IvyBridge     | 7         | 8.24%   |
| Broadwell     | 7         | 8.24%   |
| Penryn        | 6         | 7.06%   |
| Haswell       | 6         | 7.06%   |
| Silvermont    | 4         | 4.71%   |
| Unknown       | 4         | 4.71%   |
| Zen 2         | 3         | 3.53%   |
| Westmere      | 2         | 2.35%   |
| TigerLake     | 2         | 2.35%   |
| Piledriver    | 2         | 2.35%   |
| Goldmont plus | 2         | 2.35%   |
| Bonnell       | 2         | 2.35%   |
| Zen           | 1         | 1.18%   |
| Nehalem       | 1         | 1.18%   |
| K8 Hammer     | 1         | 1.18%   |
| K10           | 1         | 1.18%   |
| Goldmont      | 1         | 1.18%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart_bsd/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 69        | 65.09%  |
| Nvidia | 22        | 20.75%  |
| AMD    | 15        | 14.15%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart_bsd/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 8         | 7.55%   |
| Intel HD Graphics 5500                                                                   | 7         | 6.6%    |
| Intel 3rd Gen Core processor Graphics Controller                                         | 7         | 6.6%    |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 6         | 5.66%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 4         | 3.77%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 3         | 2.83%   |
| Intel UHD Graphics 620                                                                   | 3         | 2.83%   |
| Intel HD Graphics 620                                                                    | 3         | 2.83%   |
| Intel HD Graphics 530                                                                    | 3         | 2.83%   |
| AMD Renoir                                                                               | 3         | 2.83%   |
| Nvidia GM206GLM [Quadro M2200 Mobile]                                                    | 2         | 1.89%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 2         | 1.89%   |
| Nvidia C79 [GeForce 9400M G]                                                             | 2         | 1.89%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 2         | 1.89%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                                     | 2         | 1.89%   |
| Intel HD Graphics 630                                                                    | 2         | 1.89%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 2         | 1.89%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 2         | 1.89%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 2         | 1.89%   |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile]            | 2         | 1.89%   |
| Nvidia TU117M [GeForce MX450]                                                            | 1         | 0.94%   |
| Nvidia TU117M                                                                            | 1         | 0.94%   |
| Nvidia TU117GLM [Quadro T1000 Mobile]                                                    | 1         | 0.94%   |
| Nvidia GT218M [NVS 3100M]                                                                | 1         | 0.94%   |
| Nvidia GP108M [GeForce MX150]                                                            | 1         | 0.94%   |
| Nvidia GM108M [GeForce MX110]                                                            | 1         | 0.94%   |
| Nvidia GM107M [GeForce GTX 950M]                                                         | 1         | 0.94%   |
| Nvidia GM107GLM [Quadro M2000M]                                                          | 1         | 0.94%   |
| Nvidia GK107GLM [Quadro K1100M]                                                          | 1         | 0.94%   |
| Nvidia GF119M [Quadro NVS 4200M]                                                         | 1         | 0.94%   |
| Nvidia GF108M [GeForce 610M]                                                             | 1         | 0.94%   |
| Nvidia GA107M [GeForce RTX 3050 Ti Mobile]                                               | 1         | 0.94%   |
| Nvidia GA107GLM [RTX A2000 Mobile]                                                       | 1         | 0.94%   |
| Nvidia G96CM [GeForce 9600M GT]                                                          | 1         | 0.94%   |
| Nvidia C79 [GeForce G102M]                                                               | 1         | 0.94%   |
| Nvidia C79 [GeForce 9400M]                                                               | 1         | 0.94%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 1         | 0.94%   |
| Intel HD Graphics P530                                                                   | 1         | 0.94%   |
| Intel HD Graphics 615                                                                    | 1         | 0.94%   |
| Intel HD Graphics 610                                                                    | 1         | 0.94%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart_bsd/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 47        | 55.29%  |
| Intel + Nvidia | 15        | 17.65%  |
| 1 x AMD        | 9         | 10.59%  |
| 1 x Nvidia     | 6         | 7.06%   |
| Intel + AMD    | 5         | 5.88%   |
| 2 x Intel      | 2         | 2.35%   |
| AMD + Nvidia   | 1         | 1.18%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart_bsd/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 75        | 88.24%  |
| Proprietary | 5         | 5.88%   |
| Unknown     | 5         | 5.88%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart_bsd/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 75        | 88.24%  |
| 0.01-0.5   | 8         | 9.41%   |
| 1.01-2.0   | 1         | 1.18%   |
| 0.51-1.0   | 1         | 1.18%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart_bsd/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| LG Display              | 16        | 20.25%  |
| AU Optronics            | 15        | 18.99%  |
| BOE                     | 11        | 13.92%  |
| Chimei Innolux          | 10        | 12.66%  |
| Apple                   | 7         | 8.86%   |
| Samsung Electronics     | 4         | 5.06%   |
| Sharp                   | 3         | 3.8%    |
| Chi Mei Optoelectronics | 2         | 2.53%   |
| TMX                     | 1         | 1.27%   |
| Nvidia                  | 1         | 1.27%   |
| LG Philips              | 1         | 1.27%   |
| Hewlett-Packard         | 1         | 1.27%   |
| HannStar                | 1         | 1.27%   |
| Fujitsu Siemens         | 1         | 1.27%   |
| Dell                    | 1         | 1.27%   |
| CPT                     | 1         | 1.27%   |
| BenQ                    | 1         | 1.27%   |
| AOC                     | 1         | 1.27%   |
| Ancor Communications    | 1         | 1.27%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart_bsd/mon_model.svg)


| Model                                                                 | Notebooks | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| Samsung Electronics LCD Monitor SEC4149 1366x768 280x170mm 12.9-inch  | 2         | 2.53%   |
| LG Display LCD Monitor LGD0484 1366x768 340x190mm 15.3-inch           | 2         | 2.53%   |
| Chimei Innolux LCD Monitor CMN15E8 1920x1080 340x190mm 15.3-inch      | 2         | 2.53%   |
| Chimei Innolux LCD Monitor CMN15E6 1366x768 340x190mm 15.3-inch       | 2         | 2.53%   |
| AU Optronics LCD Monitor AUO71EC 1366x768 340x190mm 15.3-inch         | 2         | 2.53%   |
| AU Optronics LCD Monitor AUO226D 1920x1080 280x160mm 12.7-inch        | 2         | 2.53%   |
| Apple Color LCD APP9CF3 1366x768 260x140mm 11.6-inch                  | 2         | 2.53%   |
| Apple Color LCD APP9C5C 1280x800 290x180mm 13.4-inch                  | 2         | 2.53%   |
| TMX LCD Monitor TMX1560 3200x2000 340x210mm 15.7-inch                 | 1         | 1.27%   |
| Sharp LQ133M1JW01 SHP141B 1920x1080 290x170mm 13.2-inch               | 1         | 1.27%   |
| Sharp LCD Monitor SHP14B9 3840x2160 340x190mm 15.3-inch               | 1         | 1.27%   |
| Sharp LCD Monitor SHP143A 3840x2160 350x190mm 15.7-inch               | 1         | 1.27%   |
| Samsung Electronics LCD Monitor SDC4C48 1920x1080 340x190mm 15.3-inch | 1         | 1.27%   |
| Samsung Electronics LCD Monitor SDC4C46 3840x2160 340x190mm 15.3-inch | 1         | 1.27%   |
| Nvidia LCD Monitor NVD0200 1920x1080 320x180mm 14.5-inch              | 1         | 1.27%   |
| LG Philips LCD Monitor LPLE300 1280x800 330x210mm 15.4-inch           | 1         | 1.27%   |
| LG Display LCD Monitor LGD06AA 3840x2400 340x210mm 15.7-inch          | 1         | 1.27%   |
| LG Display LCD Monitor LGD057E 1920x1080 340x190mm 15.3-inch          | 1         | 1.27%   |
| LG Display LCD Monitor LGD0569 1920x1080 310x170mm 13.9-inch          | 1         | 1.27%   |
| LG Display LCD Monitor LGD0546 1920x1080 340x190mm 15.3-inch          | 1         | 1.27%   |
| LG Display LCD Monitor LGD0532 1920x1080 340x190mm 15.3-inch          | 1         | 1.27%   |
| LG Display LCD Monitor LGD0470 1920x1080 350x190mm 15.7-inch          | 1         | 1.27%   |
| LG Display LCD Monitor LGD046F 1920x1080 340x190mm 15.3-inch          | 1         | 1.27%   |
| LG Display LCD Monitor LGD0435 1600x900 310x170mm 13.9-inch           | 1         | 1.27%   |
| LG Display LCD Monitor LGD03EE 1366x768 280x160mm 12.7-inch           | 1         | 1.27%   |
| LG Display LCD Monitor LGD03B7 1366x768 310x170mm 13.9-inch           | 1         | 1.27%   |
| LG Display LCD Monitor LGD0384 1366x768 340x190mm 15.3-inch           | 1         | 1.27%   |
| LG Display LCD Monitor LGD0382 1600x900 310x170mm 13.9-inch           | 1         | 1.27%   |
| LG Display LCD Monitor LGD02DC 1366x768 340x190mm 15.3-inch           | 1         | 1.27%   |
| LG Display LCD Monitor LGD021D 1600x900 380x210mm 17.1-inch           | 1         | 1.27%   |
| Hewlett-Packard LCD Monitor HWP26A4 1440x900 410x260mm 19.1-inch      | 1         | 1.27%   |
| HannStar LCD Monitor HSD03E9 1024x600 220x130mm 10.1-inch             | 1         | 1.27%   |
| Fujitsu Siemens XE17-4 FUS0674 1280x1024 340x270mm 17.1-inch          | 1         | 1.27%   |
| Dell P2412H DELA07D 1920x1080 530x300mm 24.0-inch                     | 1         | 1.27%   |
| CPT LCD Monitor COR17DB 1600x900 290x160mm 13.0-inch                  | 1         | 1.27%   |
| Chimei Innolux LCD Monitor CMN15E3 1920x1080 340x190mm 15.3-inch      | 1         | 1.27%   |
| Chimei Innolux LCD Monitor CMN15D7 1920x1080 340x190mm 15.3-inch      | 1         | 1.27%   |
| Chimei Innolux LCD Monitor CMN152A 2560x1440 340x190mm 15.3-inch      | 1         | 1.27%   |
| Chimei Innolux LCD Monitor CMN14E9 1920x1080 310x170mm 13.9-inch      | 1         | 1.27%   |
| Chimei Innolux LCD Monitor CMN14D5 1920x1080 310x170mm 13.9-inch      | 1         | 1.27%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart_bsd/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 29        | 37.18%  |
| 1366x768 (WXGA)    | 26        | 33.33%  |
| 1280x800 (WXGA)    | 6         | 7.69%   |
| 1600x900 (HD+)     | 5         | 6.41%   |
| 3840x2160 (4K)     | 3         | 3.85%   |
| 1024x600           | 2         | 2.56%   |
| 3840x2400          | 1         | 1.28%   |
| 3200x2000          | 1         | 1.28%   |
| 2560x1440 (QHD)    | 1         | 1.28%   |
| 1920x1200 (WUXGA)  | 1         | 1.28%   |
| 1680x1050 (WSXGA+) | 1         | 1.28%   |
| 1440x900 (WXGA+)   | 1         | 1.28%   |
| 1280x1024 (SXGA)   | 1         | 1.28%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart_bsd/mon_diagonal.svg)


| Inches | Notebooks | Percent |
|--------|-----------|---------|
| 15     | 40        | 50.63%  |
| 13     | 19        | 24.05%  |
| 12     | 8         | 10.13%  |
| 17     | 2         | 2.53%   |
| 11     | 2         | 2.53%   |
| 10     | 2         | 2.53%   |
| 26     | 1         | 1.27%   |
| 24     | 1         | 1.27%   |
| 20     | 1         | 1.27%   |
| 19     | 1         | 1.27%   |
| 14     | 1         | 1.27%   |
| 9      | 1         | 1.27%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart_bsd/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 53        | 67.09%  |
| 201-300     | 21        | 26.58%  |
| 501-600     | 2         | 2.53%   |
| 401-500     | 2         | 2.53%   |
| 351-400     | 1         | 1.27%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart_bsd/mon_ratio.svg)


| Ratio | Notebooks | Percent |
|-------|-----------|---------|
| 16/9  | 63        | 81.82%  |
| 16/10 | 13        | 16.88%  |
| 5/4   | 1         | 1.3%    |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart_bsd/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 91-100         | 33        | 41.77%  |
| 81-90          | 17        | 21.52%  |
| 61-70          | 6         | 7.59%   |
| 71-80          | 5         | 6.33%   |
| 101-110        | 5         | 6.33%   |
| 41-50          | 3         | 3.8%    |
| 51-60          | 2         | 2.53%   |
| 151-200        | 2         | 2.53%   |
| 111-120        | 2         | 2.53%   |
| 301-350        | 1         | 1.27%   |
| 201-250        | 1         | 1.27%   |
| 141-150        | 1         | 1.27%   |
| 121-130        | 1         | 1.27%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart_bsd/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 34        | 43.04%  |
| 101-120       | 26        | 32.91%  |
| 161-240       | 8         | 10.13%  |
| 51-100        | 7         | 8.86%   |
| More than 240 | 4         | 5.06%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart_bsd/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 77        | 90.59%  |
| 0     | 5         | 5.88%   |
| 2     | 3         | 3.53%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart_bsd/net_vendor.svg)


| Vendor                   | Notebooks | Percent |
|--------------------------|-----------|---------|
| Intel                    | 57        | 44.19%  |
| Realtek Semiconductor    | 28        | 21.71%  |
| Qualcomm Atheros         | 17        | 13.18%  |
| Broadcom                 | 11        | 8.53%   |
| Nvidia                   | 3         | 2.33%   |
| Google                   | 3         | 2.33%   |
| Samsung Electronics      | 2         | 1.55%   |
| Ralink                   | 2         | 1.55%   |
| Marvell Technology Group | 2         | 1.55%   |
| Sierra Wireless          | 1         | 0.78%   |
| Ralink Technology        | 1         | 0.78%   |
| Huawei Technologies      | 1         | 0.78%   |
| D-Link System            | 1         | 0.78%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart_bsd/net_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 17        | 10.9%   |
| Intel Wireless 7265                                               | 9         | 5.77%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 8         | 5.13%   |
| Intel Wireless 8265 / 8275                                        | 8         | 5.13%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 6         | 3.85%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 5         | 3.21%   |
| Intel Wireless 8260                                               | 4         | 2.56%   |
| Intel Wi-Fi 6 AX200                                               | 4         | 2.56%   |
| Intel Ethernet Connection (3) I218-LM                             | 4         | 2.56%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 4         | 2.56%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 3         | 1.92%   |
| Nvidia MCP79 Ethernet                                             | 3         | 1.92%   |
| Intel Wireless 3165                                               | 3         | 1.92%   |
| Intel Ethernet Connection (2) I219-LM                             | 3         | 1.92%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 3         | 1.92%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 3         | 1.92%   |
| Broadcom BCM43224 802.11a/b/g/n                                   | 3         | 1.92%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)       | 2         | 1.28%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 2         | 1.28%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 2         | 1.28%   |
| Intel Wireless 7260                                               | 2         | 1.28%   |
| Intel Wireless 3160                                               | 2         | 1.28%   |
| Intel WiFi Link 5100                                              | 2         | 1.28%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 2         | 1.28%   |
| Intel Wi-Fi 6 AX201                                               | 2         | 1.28%   |
| Intel Ethernet Connection I219-LM                                 | 2         | 1.28%   |
| Intel Ethernet Connection I218-LM                                 | 2         | 1.28%   |
| Intel Ethernet Connection I217-LM                                 | 2         | 1.28%   |
| Intel Ethernet Connection (5) I219-LM                             | 2         | 1.28%   |
| Intel Ethernet Connection (4) I219-LM                             | 2         | 1.28%   |
| Google Nexus/Pixel Device (tether)                                | 2         | 1.28%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 2         | 1.28%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller            | 2         | 1.28%   |
| Sierra Wireless EM7455                                            | 1         | 0.64%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 1         | 0.64%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter               | 1         | 0.64%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                           | 1         | 0.64%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                        | 1         | 0.64%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 1         | 0.64%   |
| Ralink RT2870/RT3070 Wireless Adapter                             | 1         | 0.64%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart_bsd/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 54        | 61.36%  |
| Qualcomm Atheros      | 17        | 19.32%  |
| Broadcom              | 8         | 9.09%   |
| Realtek Semiconductor | 4         | 4.55%   |
| Ralink                | 2         | 2.27%   |
| Sierra Wireless       | 1         | 1.14%   |
| Ralink Technology     | 1         | 1.14%   |
| D-Link System         | 1         | 1.14%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart_bsd/net_wireless_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Intel Wireless 7265                                                     | 9         | 10.23%  |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 8         | 9.09%   |
| Intel Wireless 8265 / 8275                                              | 8         | 9.09%   |
| Intel Wireless 8260                                                     | 4         | 4.55%   |
| Intel Wi-Fi 6 AX200                                                     | 4         | 4.55%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 4         | 4.55%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 3         | 3.41%   |
| Intel Wireless 3165                                                     | 3         | 3.41%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 3         | 3.41%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 3         | 3.41%   |
| Broadcom BCM43224 802.11a/b/g/n                                         | 3         | 3.41%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 2         | 2.27%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 2         | 2.27%   |
| Intel Wireless 7260                                                     | 2         | 2.27%   |
| Intel Wireless 3160                                                     | 2         | 2.27%   |
| Intel WiFi Link 5100                                                    | 2         | 2.27%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                  | 2         | 2.27%   |
| Intel Wi-Fi 6 AX201                                                     | 2         | 2.27%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller                  | 2         | 2.27%   |
| Sierra Wireless EM7455                                                  | 1         | 1.14%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 1         | 1.14%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 1         | 1.14%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                                 | 1         | 1.14%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 1         | 1.14%   |
| Ralink RT2870/RT3070 Wireless Adapter                                   | 1         | 1.14%   |
| Ralink RT5390 Wireless 802.11n 1T/1R PCIe                               | 1         | 1.14%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                               | 1         | 1.14%   |
| Qualcomm Atheros AR5212 802.11abg NIC                                   | 1         | 1.14%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 1         | 1.14%   |
| Intel Wireless-AC 9260                                                  | 1         | 1.14%   |
| Intel Tiger Lake PCH CNVi WiFi                                          | 1         | 1.14%   |
| Intel Gemini Lake PCH CNVi WiFi                                         | 1         | 1.14%   |
| Intel Centrino Ultimate-N 6300                                          | 1         | 1.14%   |
| Intel Centrino Advanced-N 6235                                          | 1         | 1.14%   |
| Intel Centrino Advanced-N 6200                                          | 1         | 1.14%   |
| D-Link System DWA-125 Wireless N 150 Adapter(rev.A1) [Ralink RT3070]    | 1         | 1.14%   |
| Broadcom BCM4331 802.11a/b/g/n                                          | 1         | 1.14%   |
| Broadcom BCM43142 802.11b/g/n                                           | 1         | 1.14%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 1         | 1.14%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart_bsd/net_ethernet_vendor.svg)


| Vendor                   | Notebooks | Percent |
|--------------------------|-----------|---------|
| Intel                    | 26        | 39.39%  |
| Realtek Semiconductor    | 24        | 36.36%  |
| Broadcom                 | 4         | 6.06%   |
| Qualcomm Atheros         | 3         | 4.55%   |
| Nvidia                   | 3         | 4.55%   |
| Samsung Electronics      | 2         | 3.03%   |
| Marvell Technology Group | 2         | 3.03%   |
| Google                   | 2         | 3.03%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart_bsd/net_ethernet_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller              | 17        | 25.76%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                          | 6         | 9.09%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                          | 5         | 7.58%   |
| Intel Ethernet Connection (3) I218-LM                                          | 4         | 6.06%   |
| Nvidia MCP79 Ethernet                                                          | 3         | 4.55%   |
| Intel Ethernet Connection (2) I219-LM                                          | 3         | 4.55%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)                    | 2         | 3.03%   |
| Intel Ethernet Connection I219-LM                                              | 2         | 3.03%   |
| Intel Ethernet Connection I218-LM                                              | 2         | 3.03%   |
| Intel Ethernet Connection I217-LM                                              | 2         | 3.03%   |
| Intel Ethernet Connection (5) I219-LM                                          | 2         | 3.03%   |
| Intel Ethernet Connection (4) I219-LM                                          | 2         | 3.03%   |
| Google Nexus/Pixel Device (tether)                                             | 2         | 3.03%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                                | 2         | 3.03%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                          | 1         | 1.52%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                                         | 1         | 1.52%   |
| Qualcomm Atheros AR8162 Fast Ethernet                                          | 1         | 1.52%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                          | 1         | 1.52%   |
| Marvell Group Yukon Optima 88E8059 [PCIe Gigabit Ethernet Controller with AVB] | 1         | 1.52%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller                        | 1         | 1.52%   |
| Intel Ethernet Connection I219-V                                               | 1         | 1.52%   |
| Intel Ethernet Connection (6) I219-LM                                          | 1         | 1.52%   |
| Intel Ethernet Connection (14) I219-LM                                         | 1         | 1.52%   |
| Intel 82577LM Gigabit Network Connection                                       | 1         | 1.52%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                              | 1         | 1.52%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                                | 1         | 1.52%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart_bsd/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 83        | 54.97%  |
| Ethernet | 66        | 43.71%  |
| Modem    | 1         | 0.66%   |
| Unknown  | 1         | 0.66%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart_bsd/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 52        | 61.9%   |
| Ethernet | 32        | 38.1%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart_bsd/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 61        | 71.76%  |
| 1     | 23        | 27.06%  |
| 0     | 1         | 1.18%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart_bsd/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 78        | 91.76%  |
| Yes  | 7         | 8.24%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart_bsd/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 41        | 64.06%  |
| Apple                           | 6         | 9.38%   |
| Qualcomm Atheros Communications | 3         | 4.69%   |
| Broadcom                        | 3         | 4.69%   |
| Lite-On Technology              | 2         | 3.13%   |
| IMC Networks                    | 2         | 3.13%   |
| Hewlett-Packard                 | 2         | 3.13%   |
| Alps Electric                   | 2         | 3.13%   |
| Ralink                          | 1         | 1.56%   |
| Cambridge Silicon Radio         | 1         | 1.56%   |
| ASUSTek Computer                | 1         | 1.56%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart_bsd/bt_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 25        | 37.88%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 4         | 6.06%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                | 4         | 6.06%   |
| Intel Wireless-AC 3168 Bluetooth                    | 3         | 4.55%   |
| Intel AX201 Bluetooth                               | 3         | 4.55%   |
| Intel AX200 Bluetooth                               | 3         | 4.55%   |
| Intel AX210 Bluetooth                               | 2         | 3.03%   |
| HP Broadcom 2070 Bluetooth Combo                    | 2         | 3.03%   |
| Apple Built-in iSight (no firmware loaded)          | 2         | 3.03%   |
| Ralink RT3290 Bluetooth                             | 1         | 1.52%   |
| Qualcomm Atheros  QCA9377 Bluetooth 4.1             | 1         | 1.52%   |
| Qualcomm Atheros Dell Wireless 1703 Bluetooth       | 1         | 1.52%   |
| Qualcomm Atheros AR9462 Bluetooth                   | 1         | 1.52%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 1         | 1.52%   |
| Lite-On Atheros AR3012 Bluetooth                    | 1         | 1.52%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 1         | 1.52%   |
| IMC Networks Realtek Bluetooth Adapter              | 1         | 1.52%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter   | 1         | 1.52%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 1         | 1.52%   |
| Broadcom BCM43142 Bluetooth 4.0                     | 1         | 1.52%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 1         | 1.52%   |
| Broadcom BCM2045B (BDC-2.1)                         | 1         | 1.52%   |
| ASUS BT-253 Bluetooth Adapter                       | 1         | 1.52%   |
| Apple Bluetooth Host Controller                     | 1         | 1.52%   |
| Apple Apple Broadcom Built-in Bluetooth             | 1         | 1.52%   |
| Alps Electric UGTZ4 Bluetooth                       | 1         | 1.52%   |
| Alps Electric BCM2046 Bluetooth Device              | 1         | 1.52%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart_bsd/snd_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Intel               | 71        | 77.17%  |
| AMD                 | 10        | 10.87%  |
| Nvidia              | 7         | 7.61%   |
| XMOS                | 1         | 1.09%   |
| Kingston Technology | 1         | 1.09%   |
| GN Netcom           | 1         | 1.09%   |
| C-Media Electronics | 1         | 1.09%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart_bsd/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                                                   | 15        | 13.51%  |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 9         | 8.11%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 7         | 6.31%   |
| Intel Broadwell-U Audio Controller                                                                | 7         | 6.31%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 6         | 5.41%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 5         | 4.5%    |
| Nvidia MCP79 High Definition Audio                                                                | 4         | 3.6%    |
| Intel 8 Series HD Audio Controller                                                                | 4         | 3.6%    |
| Intel Haswell-ULT HD Audio Controller                                                             | 3         | 2.7%    |
| Intel CM238 HD Audio Controller                                                                   | 3         | 2.7%    |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 3         | 2.7%    |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 3         | 2.7%    |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 3         | 2.7%    |
| AMD Renoir Radeon High Definition Audio Controller                                                | 3         | 2.7%    |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 2         | 1.8%    |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 2         | 1.8%    |
| Intel Tiger Lake-H HD Audio Controller                                                            | 2         | 1.8%    |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 2         | 1.8%    |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 2         | 1.8%    |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 2         | 1.8%    |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 2         | 1.8%    |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 2         | 1.8%    |
| AMD Trinity HDMI Audio Controller                                                                 | 2         | 1.8%    |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 2         | 1.8%    |
| AMD FCH Azalia Controller                                                                         | 2         | 1.8%    |
| XMOS iFi (by AMR) HD USB Audio                                                                    | 1         | 0.9%    |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 1         | 0.9%    |
| Nvidia High Definition Audio Controller                                                           | 1         | 0.9%    |
| Kingston Technology HyperX 7.1 Audio                                                              | 1         | 0.9%    |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 1         | 0.9%    |
| Intel Cannon Lake PCH cAVS                                                                        | 1         | 0.9%    |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 1         | 0.9%    |
| Intel Alder Lake PCH-P High Definition Audio Controller                                           | 1         | 0.9%    |
| GN Netcom Jabra EVOLVE 20                                                                         | 1         | 0.9%    |
| C-Media Electronics Audio Adapter (Unitek Y-247A)                                                 | 1         | 0.9%    |
| AMD RV710/730 HDMI Audio [Radeon HD 4000 series]                                                  | 1         | 0.9%    |
| AMD RS880 HDMI Audio [Radeon HD 4200 Series]                                                      | 1         | 0.9%    |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 1         | 0.9%    |
| Unknown                                                                                           | 1         | 0.9%    |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart_bsd/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| SK hynix            | 25        | 24.51%  |
| Samsung Electronics | 24        | 23.53%  |
| Micron Technology   | 11        | 10.78%  |
| Unknown             | 8         | 7.84%   |
| Kingston            | 8         | 7.84%   |
| Smart               | 3         | 2.94%   |
| G.Skill             | 3         | 2.94%   |
| Elpida              | 3         | 2.94%   |
| A-DATA Technology   | 3         | 2.94%   |
| Nanya Technology    | 2         | 1.96%   |
| Crucial             | 2         | 1.96%   |
| Transcend           | 1         | 0.98%   |
| Teikon              | 1         | 0.98%   |
| Smart Brazil        | 1         | 0.98%   |
| SHARETRONIC         | 1         | 0.98%   |
| Sesame              | 1         | 0.98%   |
| Ramaxel Technology  | 1         | 0.98%   |
| PNY                 | 1         | 0.98%   |
| GSkill              | 1         | 0.98%   |
| GeIL                | 1         | 0.98%   |
| Unknown             | 1         | 0.98%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart_bsd/memory_model.svg)


| Model                                                           | Notebooks | Percent |
|-----------------------------------------------------------------|-----------|---------|
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s           | 4         | 3.81%   |
| SK hynix RAM Module 2GB SODIMM DDR3 1600MT/s                    | 3         | 2.86%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s          | 3         | 2.86%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2400MT/s          | 3         | 2.86%   |
| Micron RAM 16ATF2G64HZ-2G6E1 16GB SODIMM DDR4 2667MT/s          | 3         | 2.86%   |
| Unknown RAM Module 2GB SODIMM DDR3 1333MT/s                     | 2         | 1.9%    |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s          | 2         | 1.9%    |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s          | 2         | 1.9%    |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2400MT/s          | 2         | 1.9%    |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s          | 2         | 1.9%    |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s           | 2         | 1.9%    |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2400MT/s           | 2         | 1.9%    |
| Samsung RAM M471A1K43BB1-CRC 8GB SODIMM DDR4 2400MT/s           | 2         | 1.9%    |
| Unknown RAM Module 4GB DIMM DDR3 1067MT/s                       | 1         | 0.95%   |
| Unknown RAM Module 2GB SODIMM DDR3 1067MT/s                     | 1         | 0.95%   |
| Unknown RAM Module 2GB SODIMM DDR3                              | 1         | 0.95%   |
| Unknown RAM Module 2GB SODIMM DDR2 800MT/s                      | 1         | 0.95%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                      | 1         | 0.95%   |
| Unknown RAM Module 2GB SODIMM DDR2                              | 1         | 0.95%   |
| Unknown RAM Module 1GB SODIMM DDR2 800MT/s                      | 1         | 0.95%   |
| Transcend RAM TS4GSH64V2E3 32GB SODIMM DDR4 3200MT/s            | 1         | 0.95%   |
| Teikon RAM TML251S6EFR8A-PBHC 4GB SODIMM DDR3 1600MT/s          | 1         | 0.95%   |
| Smart RAM SH564568FH8NZPHSCR 2GB SODIMM DDR3 1334MT/s           | 1         | 0.95%   |
| Smart RAM SH564568FH8NWPHSFR 2GB SODIMM DDR3 1333MT/s           | 1         | 0.95%   |
| Smart RAM SH564128FJ8NWRNSQR 4GB SODIMM DDR3 1600MT/s           | 1         | 0.95%   |
| Smart RAM SF4641G8CK8IEGKSBG 8GB SODIMM DDR4 2400MT/s           | 1         | 0.95%   |
| Smart Brazil RAM Module 4GB Row Of Chips DDR4 2400MT/s          | 1         | 0.95%   |
| SK hynix RAM Module 4GB SODIMM DDR4 2400MT/s                    | 1         | 0.95%   |
| SK hynix RAM Module 16GB SODIMM DDR4 2133MT/s                   | 1         | 0.95%   |
| SK hynix RAM HYMP125S64CP8-S6 2GB SODIMM SDRAM 2048MT/s         | 1         | 0.95%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s          | 1         | 0.95%   |
| SK hynix RAM HMT351S6EFR8C-PB 4GB SODIMM DDR3 1600MT/s          | 1         | 0.95%   |
| SK hynix RAM HMT351S6EFR8A-PB 4GB SODIMM DDR3 1600MT/s          | 1         | 0.95%   |
| SK hynix RAM HMA851S6AFR6N-TF 4GB SODIMM DDR4 2133MT/s          | 1         | 0.95%   |
| SK hynix RAM H9CCNNN8JTBLAR-NUD 2GB LPDDR3 1600MT/s             | 1         | 0.95%   |
| SK hynix RAM 9CCNNNBKTMLBR-NUD 2GB Row Of Chips LPDDR3 1867MT/s | 1         | 0.95%   |
| SHARETRONIC RAM Module 2GB SODIMM DDR3 1600MT/s                 | 1         | 0.95%   |
| Sesame RAM Module 8GB SODIMM DDR3 1600MT/s                      | 1         | 0.95%   |
| Samsung RAM Module 8GB SODIMM DDR4 2133MT/s                     | 1         | 0.95%   |
| Samsung RAM M474A1G43EB1-CPB 8GB DIMM DDR4 2133MT/s             | 1         | 0.95%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart_bsd/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR3    | 42        | 50%     |
| DDR4    | 32        | 38.1%   |
| DDR2    | 6         | 7.14%   |
| LPDDR3  | 2         | 2.38%   |
| SDRAM   | 1         | 1.19%   |
| Unknown | 1         | 1.19%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart_bsd/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 75        | 88.24%  |
| Row Of Chips | 4         | 4.71%   |
| Unknown      | 3         | 3.53%   |
| DIMM         | 2         | 2.35%   |
| Chip         | 1         | 1.18%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart_bsd/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 4096  | 32        | 35.56%  |
| 2048  | 22        | 24.44%  |
| 8192  | 21        | 23.33%  |
| 16384 | 13        | 14.44%  |
| 32768 | 1         | 1.11%   |
| 1024  | 1         | 1.11%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart_bsd/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 1600    | 29        | 31.52%  |
| 2400    | 13        | 14.13%  |
| 1333    | 11        | 11.96%  |
| 2667    | 10        | 10.87%  |
| 3200    | 7         | 7.61%   |
| 2133    | 6         | 6.52%   |
| 1867    | 3         | 3.26%   |
| 1334    | 3         | 3.26%   |
| 1067    | 2         | 2.17%   |
| 800     | 2         | 2.17%   |
| 667     | 2         | 2.17%   |
| Unknown | 2         | 2.17%   |
| 2048    | 1         | 1.09%   |
| 333     | 1         | 1.09%   |

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
| Chicony Electronics                    | 20        | 29.85%  |
| Microdia                               | 11        | 16.42%  |
| IMC Networks                           | 7         | 10.45%  |
| Realtek Semiconductor                  | 6         | 8.96%   |
| Sunplus Innovation Technology          | 5         | 7.46%   |
| Acer                                   | 5         | 7.46%   |
| Apple                                  | 3         | 4.48%   |
| Syntek                                 | 2         | 2.99%   |
| Suyin                                  | 2         | 2.99%   |
| Z-Star Microelectronics                | 1         | 1.49%   |
| Silicon Motion                         | 1         | 1.49%   |
| Luxvisions Innotech Limited            | 1         | 1.49%   |
| Lite-On Technology                     | 1         | 1.49%   |
| Cheng Uei Precision Industry (Foxlink) | 1         | 1.49%   |
| Alcor Micro                            | 1         | 1.49%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart_bsd/camera_model.svg)


| Model                                                       | Notebooks | Percent |
|-------------------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                                   | 4         | 5.97%   |
| Sunplus Integrated_Webcam_HD                                | 3         | 4.48%   |
| Microdia Integrated_Webcam_HD                               | 3         | 4.48%   |
| Chicony HD Webcam                                           | 3         | 4.48%   |
| Acer Integrated Camera                                      | 3         | 4.48%   |
| Realtek Realtek USB2.0 PC Camera                            | 2         | 2.99%   |
| Microdia Dell Laptop Integrated Webcam HD                   | 2         | 2.99%   |
| IMC Networks USB2.0 UVC VGA WebCam                          | 2         | 2.99%   |
| Chicony XiaoMi USB 2.0 Webcam                               | 2         | 2.99%   |
| Chicony TOSHIBA Web Camera - HD                             | 2         | 2.99%   |
| Apple FaceTime HD Camera (Built-in)                         | 2         | 2.99%   |
| Z-Star DataMax USB2.0 Camera                                | 1         | 1.49%   |
| Syntek Syntek 0.3MPixel USB 2.0 UVC PC Camera               | 1         | 1.49%   |
| Syntek Integrated Camera                                    | 1         | 1.49%   |
| Suyin Integrated_Webcam_HD                                  | 1         | 1.49%   |
| Suyin 1.3M WebCam (notebook emachines E730, Acer sub-brand) | 1         | 1.49%   |
| Sunplus XiaoMi USB 2.0 Webcam                               | 1         | 1.49%   |
| Sunplus HP HD Webcam [Fixed]                                | 1         | 1.49%   |
| Silicon Motion Web Camera                                   | 1         | 1.49%   |
| Realtek Integrated_Webcam_HD                                | 1         | 1.49%   |
| Realtek HP HD Webcam [Fixed]                                | 1         | 1.49%   |
| Realtek HD WebCam                                           | 1         | 1.49%   |
| Realtek Acer 640 x 480 laptop camera                        | 1         | 1.49%   |
| Microdia Webcam                                             | 1         | 1.49%   |
| Microdia USB 2.0 Camera                                     | 1         | 1.49%   |
| Microdia Laptop_Integrated_Webcam_HD                        | 1         | 1.49%   |
| Microdia Laptop_Integrated_Webcam_2M                        | 1         | 1.49%   |
| Microdia Integrated Webcam HD                               | 1         | 1.49%   |
| Microdia Integrated Webcam                                  | 1         | 1.49%   |
| Luxvisions Innotech Limited Integrated Camera               | 1         | 1.49%   |
| Lite-On HP HD Webcam [Fixed]                                | 1         | 1.49%   |
| IMC Networks USB2.0 VGA UVC WebCam                          | 1         | 1.49%   |
| IMC Networks USB2.0 HD UVC WebCam                           | 1         | 1.49%   |
| IMC Networks Integrated RGB Camera                          | 1         | 1.49%   |
| IMC Networks Integrated Camera                              | 1         | 1.49%   |
| IMC Networks HD Camera                                      | 1         | 1.49%   |
| Chicony WebCam                                              | 1         | 1.49%   |
| Chicony VGA WebCam                                          | 1         | 1.49%   |
| Chicony TOSHIBA Web Camera - FHD                            | 1         | 1.49%   |
| Chicony Realtek DMFT - RGB                                  | 1         | 1.49%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart_bsd/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 9         | 56.25%  |
| Synaptics                  | 3         | 18.75%  |
| AuthenTec                  | 2         | 12.5%   |
| Shenzhen Goodix Technology | 1         | 6.25%   |
| Broadcom                   | 1         | 6.25%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart_bsd/fingerprint_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Validity Sensors VFS495 Fingerprint Reader                                   | 3         | 18.75%  |
| Validity Sensors Synaptics WBDI                                              | 2         | 12.5%   |
| Unknown                                                                      | 2         | 12.5%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                            | 1         | 6.25%   |
| Validity Sensors VFS471 Fingerprint Reader                                   | 1         | 6.25%   |
| Validity Sensors VFS Fingerprint sensor                                      | 1         | 6.25%   |
| Validity Sensors VFS 5011 fingerprint sensor                                 | 1         | 6.25%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader                            | 1         | 6.25%   |
| Shenzhen Goodix Fingerprint Reader                                           | 1         | 6.25%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 1         | 6.25%   |
| AuthenTec AuthenTec Inc. AES1660                                             | 1         | 6.25%   |
| AuthenTec AES1600                                                            | 1         | 6.25%   |

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
| 1     | 30        | 35.29%  |
| 2     | 24        | 28.24%  |
| 3     | 14        | 16.47%  |
| 0     | 13        | 15.29%  |
| 4     | 3         | 3.53%   |
| 5     | 1         | 1.18%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart_bsd/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Communication controller | 60        | 45.45%  |
| Bluetooth                | 26        | 19.7%   |
| Fingerprint reader       | 15        | 11.36%  |
| Card reader              | 15        | 11.36%  |
| Net/wireless             | 9         | 6.82%   |
| Sound                    | 4         | 3.03%   |
| Network                  | 2         | 1.52%   |
| Storage                  | 1         | 0.76%   |

