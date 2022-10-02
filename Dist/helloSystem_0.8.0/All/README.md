helloSystem 0.8.0 - Tested Hardware & Statistics
------------------------------------------------

A project to collect tested hardware configurations for helloSystem 0.8.0.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe/blob/master/INSTALL.BSD.md) tool:

    hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Dist/helloSystem_0.8.0/Desktop/README.md) and [notebooks](/Dist/helloSystem_0.8.0/Notebook/README.md).

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

Total: 81

| Vendor        | Model                       | Form-Factor | Probe                                                     | Date         |
|---------------|-----------------------------|-------------|-----------------------------------------------------------|--------------|
| Dell          | 0T10XW A01                  | Desktop     | [c2ff0bc0b9](https://bsd-hardware.info/?probe=c2ff0bc0b9) | Sep 30, 2022 |
| Kraftway      | KW10T                       | Notebook    | [db27da2e88](https://bsd-hardware.info/?probe=db27da2e88) | Sep 29, 2022 |
| Lenovo        | ThinkPad X250 20CLS1WP01    | Notebook    | [1b75ee6295](https://bsd-hardware.info/?probe=1b75ee6295) | Sep 19, 2022 |
| Apple         | MacBook5,2                  | Notebook    | [79503c0635](https://bsd-hardware.info/?probe=79503c0635) | Sep 10, 2022 |
| Apple         | MacBook5,2                  | Notebook    | [9c7a64970c](https://bsd-hardware.info/?probe=9c7a64970c) | Sep 10, 2022 |
| Dell          | Latitude E5550              | Notebook    | [867e56fb52](https://bsd-hardware.info/?probe=867e56fb52) | Sep 01, 2022 |
| ASRock        | ConRoeXFire-eSATA2          | Desktop     | [caf005ed95](https://bsd-hardware.info/?probe=caf005ed95) | Sep 01, 2022 |
| Lenovo        | ThinkPad T420 4178A72       | Notebook    | [18a105546b](https://bsd-hardware.info/?probe=18a105546b) | Aug 29, 2022 |
| Lenovo        | ThinkPad T420 4178A72       | Notebook    | [1433351032](https://bsd-hardware.info/?probe=1433351032) | Aug 29, 2022 |
| ASUSTek       | ROG STRIX B550-I GAMING     | Desktop     | [079adb24f8](https://bsd-hardware.info/?probe=079adb24f8) | Aug 28, 2022 |
| Toshiba       | Satellite S55t-B            | Notebook    | [df9971d3aa](https://bsd-hardware.info/?probe=df9971d3aa) | Aug 27, 2022 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [2c7586b0ed](https://bsd-hardware.info/?probe=2c7586b0ed) | Aug 25, 2022 |
| Intel         | NUC8BEB J72688-304          | Mini pc     | [3de3724488](https://bsd-hardware.info/?probe=3de3724488) | Aug 12, 2022 |
| TUXEDO        | Pulse 14 Gen1               | Notebook    | [5edf8a1bef](https://bsd-hardware.info/?probe=5edf8a1bef) | Aug 09, 2022 |
| ASUSTek       | F6A                         | Notebook    | [6626d18284](https://bsd-hardware.info/?probe=6626d18284) | Aug 08, 2022 |
| ASUSTek       | P5QL-ASUS-SE                | Desktop     | [50a0d392e7](https://bsd-hardware.info/?probe=50a0d392e7) | Aug 06, 2022 |
| ASUSTek       | K30AM-J                     | Desktop     | [470ced8f30](https://bsd-hardware.info/?probe=470ced8f30) | Aug 05, 2022 |
| HP            | 250 G6 Notebook PC          | Notebook    | [511d057c70](https://bsd-hardware.info/?probe=511d057c70) | Jul 27, 2022 |
| HP            | OMEN by Laptop              | Notebook    | [25e43be096](https://bsd-hardware.info/?probe=25e43be096) | Jul 17, 2022 |
| MSI           | MPG X570 GAMING PLUS        | Desktop     | [a80b1c4f3c](https://bsd-hardware.info/?probe=a80b1c4f3c) | Jul 17, 2022 |
| HP            | 1998                        | Desktop     | [e4fda48283](https://bsd-hardware.info/?probe=e4fda48283) | Jul 15, 2022 |
| Dell          | Latitude E5450              | Notebook    | [5f1183ab0b](https://bsd-hardware.info/?probe=5f1183ab0b) | Jul 14, 2022 |
| Dell          | Latitude E5450              | Notebook    | [1080ed5654](https://bsd-hardware.info/?probe=1080ed5654) | Jul 14, 2022 |
| Acer          | Aspire E5-571G              | Notebook    | [56fae2295e](https://bsd-hardware.info/?probe=56fae2295e) | Jul 08, 2022 |
| HP            | 250 G6 Notebook PC          | Notebook    | [bbe1d21883](https://bsd-hardware.info/?probe=bbe1d21883) | Jul 07, 2022 |
| Pegatron      | IPM41-D3                    | Desktop     | [8b2af1b843](https://bsd-hardware.info/?probe=8b2af1b843) | Jul 06, 2022 |
| Biostar       | G41D3C                      | Desktop     | [118bd083bf](https://bsd-hardware.info/?probe=118bd083bf) | Jul 01, 2022 |
| Dell          | Inspiron 15-3552            | Notebook    | [8cdc3bd7ab](https://bsd-hardware.info/?probe=8cdc3bd7ab) | Jul 01, 2022 |
| Apple         | MacBook6,1                  | Notebook    | [a6d3cf9a30](https://bsd-hardware.info/?probe=a6d3cf9a30) | Jun 20, 2022 |
| Acer          | Aspire A315-34              | Notebook    | [90927fa85a](https://bsd-hardware.info/?probe=90927fa85a) | Jun 20, 2022 |
| HP            | Unknown                     | Notebook    | [11ef8f9a92](https://bsd-hardware.info/?probe=11ef8f9a92) | Jun 19, 2022 |
| Lenovo        | ThinkPad X250 20CLS23500    | Notebook    | [6a8b44bc47](https://bsd-hardware.info/?probe=6a8b44bc47) | Jun 03, 2022 |
| Lenovo        | IdeaPad 3 15IGL05 82BU      | Notebook    | [6a6450f264](https://bsd-hardware.info/?probe=6a6450f264) | May 30, 2022 |
| Timi          | TM1701                      | Notebook    | [a28220d11f](https://bsd-hardware.info/?probe=a28220d11f) | May 22, 2022 |
| Dell          | Studio 1747                 | Notebook    | [7ae292b282](https://bsd-hardware.info/?probe=7ae292b282) | May 21, 2022 |
| TUXEDO        | Aura 15 Gen1                | Notebook    | [20814a930a](https://bsd-hardware.info/?probe=20814a930a) | May 18, 2022 |
| ASUSTek       | K30AM-J                     | Desktop     | [f4352f7897](https://bsd-hardware.info/?probe=f4352f7897) | May 16, 2022 |
| Packard Be... | EasyNote_MX52-B-071         | Notebook    | [277c9e0a0a](https://bsd-hardware.info/?probe=277c9e0a0a) | May 08, 2022 |
| Dell          | Inspiron 5559               | Notebook    | [a7111b84cb](https://bsd-hardware.info/?probe=a7111b84cb) | May 08, 2022 |
| Lenovo        | ThinkPad X270 W10DG 20K5... | Notebook    | [f02e4345ff](https://bsd-hardware.info/?probe=f02e4345ff) | Apr 30, 2022 |
| Apple         | MacBookPro5,5               | Notebook    | [4b5603b38b](https://bsd-hardware.info/?probe=4b5603b38b) | Apr 29, 2022 |
| ASUSTek       | 1001PX                      | Notebook    | [b47a498f2e](https://bsd-hardware.info/?probe=b47a498f2e) | Apr 08, 2022 |
| ASUSTek       | 1001PX                      | Notebook    | [289521c6cb](https://bsd-hardware.info/?probe=289521c6cb) | Apr 08, 2022 |
| Dell          | Latitude E5470              | Notebook    | [a7d087a428](https://bsd-hardware.info/?probe=a7d087a428) | Apr 05, 2022 |
| Sony          | VGN-AW21S_B                 | Notebook    | [11edcb4e82](https://bsd-hardware.info/?probe=11edcb4e82) | Apr 03, 2022 |
| Lenovo        | 30D9 SDK0J40705 WIN 3425... | Desktop     | [964ceb3616](https://bsd-hardware.info/?probe=964ceb3616) | Apr 03, 2022 |
| PCSTICK       | Unknown                     | Notebook    | [6f9f24b262](https://bsd-hardware.info/?probe=6f9f24b262) | Mar 29, 2022 |
| Dell          | Latitude E6540              | Notebook    | [41e5f63a69](https://bsd-hardware.info/?probe=41e5f63a69) | Mar 26, 2022 |
| ASUSTek       | UX31E                       | Notebook    | [93655cdd83](https://bsd-hardware.info/?probe=93655cdd83) | Mar 21, 2022 |
| HP            | EliteBook 850 G3            | Notebook    | [1ae8321767](https://bsd-hardware.info/?probe=1ae8321767) | Mar 20, 2022 |
| Gateway       | NE56R                       | Notebook    | [87d177b9da](https://bsd-hardware.info/?probe=87d177b9da) | Mar 20, 2022 |
| MSI           | B350M BAZOOKA               | Desktop     | [bac8d0bdb7](https://bsd-hardware.info/?probe=bac8d0bdb7) | Mar 11, 2022 |
| HUAWEI        | BOD-WXX9                    | Notebook    | [65454bcc92](https://bsd-hardware.info/?probe=65454bcc92) | Mar 06, 2022 |
| ASRock        | G41C-VS                     | Desktop     | [a9a1b1a493](https://bsd-hardware.info/?probe=a9a1b1a493) | Mar 03, 2022 |
| Intel         | DN2800MT AAG23738-600       | Desktop     | [8ecf2d023f](https://bsd-hardware.info/?probe=8ecf2d023f) | Mar 02, 2022 |
| Acer          | V5-131                      | Notebook    | [076ca78b3f](https://bsd-hardware.info/?probe=076ca78b3f) | Feb 25, 2022 |
| Dell          | Latitude 7480               | Notebook    | [8a0388b49d](https://bsd-hardware.info/?probe=8a0388b49d) | Feb 23, 2022 |
| PCSTICK       | Unknown                     | Notebook    | [b76b5c9670](https://bsd-hardware.info/?probe=b76b5c9670) | Feb 21, 2022 |
| ASUSTek       | 1001PX                      | Notebook    | [d171d1ec99](https://bsd-hardware.info/?probe=d171d1ec99) | Feb 17, 2022 |
| Lenovo        | Legion 5 15ARH05 82B5       | Notebook    | [1a13b7bfd1](https://bsd-hardware.info/?probe=1a13b7bfd1) | Feb 16, 2022 |
| ASUSTek       | TUF GAMING X570-PLUS        | Desktop     | [64999a24c1](https://bsd-hardware.info/?probe=64999a24c1) | Feb 16, 2022 |
| Acer          | Aspire 5750G                | Notebook    | [bd22fc8a49](https://bsd-hardware.info/?probe=bd22fc8a49) | Feb 15, 2022 |
| AMD           | X64                         | Desktop     | [e5a9ff1138](https://bsd-hardware.info/?probe=e5a9ff1138) | Feb 15, 2022 |
| Timi          | RedmiBook Pro 15            | Notebook    | [7716f59380](https://bsd-hardware.info/?probe=7716f59380) | Feb 14, 2022 |
| Timi          | RedmiBook Pro 15            | Notebook    | [fdd0ab95ed](https://bsd-hardware.info/?probe=fdd0ab95ed) | Feb 14, 2022 |
| Lenovo        | SHARKBAY SDK0E50510 WIN     | Desktop     | [eddeb5c246](https://bsd-hardware.info/?probe=eddeb5c246) | Feb 13, 2022 |
| Apple         | MacBook5,2                  | Notebook    | [29756c2371](https://bsd-hardware.info/?probe=29756c2371) | Feb 13, 2022 |
| MACHINIST     | X99-k9 V2.0                 | Desktop     | [0a36d71db1](https://bsd-hardware.info/?probe=0a36d71db1) | Feb 10, 2022 |
| Sony          | VPCEB1J1E                   | Notebook    | [9151a22f13](https://bsd-hardware.info/?probe=9151a22f13) | Jan 30, 2022 |
| Pegatron      | IPPPV-D3G                   | Desktop     | [d5e44ccf6b](https://bsd-hardware.info/?probe=d5e44ccf6b) | Jan 28, 2022 |
| Intel         | MAHOBAY                     | Desktop     | [2036093b68](https://bsd-hardware.info/?probe=2036093b68) | Jan 25, 2022 |
| HP            | 8648                        | Desktop     | [b0adf55067](https://bsd-hardware.info/?probe=b0adf55067) | Jan 23, 2022 |
| Dell          | 0593VH A00                  | Desktop     | [484d14dbef](https://bsd-hardware.info/?probe=484d14dbef) | Jan 22, 2022 |
| ASRock        | B365M Pro4                  | Desktop     | [8449bd20c1](https://bsd-hardware.info/?probe=8449bd20c1) | Jan 18, 2022 |
| Dell          | 0YF8P5 A00                  | Desktop     | [913b2a7483](https://bsd-hardware.info/?probe=913b2a7483) | Jan 18, 2022 |
| Dell          | 0X4N41 A01                  | Desktop     | [87000234dc](https://bsd-hardware.info/?probe=87000234dc) | Jan 11, 2022 |
| Lenovo        | ThinkPad T440 20B7A0B7MS    | Notebook    | [be30041f4e](https://bsd-hardware.info/?probe=be30041f4e) | Jan 10, 2022 |
| Apple         | Mac-F2218EA9                | All in one  | [5de4d8c93e](https://bsd-hardware.info/?probe=5de4d8c93e) | Jan 09, 2022 |
| Lenovo        | G480 20149                  | Notebook    | [adc6b44cc8](https://bsd-hardware.info/?probe=adc6b44cc8) | Jan 09, 2022 |
| Apple         | Mac-F2218EA9                | All in one  | [7c49bc84a7](https://bsd-hardware.info/?probe=7c49bc84a7) | Jan 08, 2022 |
| HP            | EliteBook 820 G1            | Notebook    | [362940acbb](https://bsd-hardware.info/?probe=362940acbb) | Jan 03, 2022 |

System
------

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart_bsd/os_arch.svg)


| Name  | Computers | Percent |
|-------|-----------|---------|
| amd64 | 69        | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart_bsd/os_de.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| helloDesktop | 66        | 95.65%  |
| GNOME        | 2         | 2.9%    |
| Cinnamon     | 1         | 1.45%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart_bsd/os_display_server.svg)


| Name | Computers | Percent |
|------|-----------|---------|
| X11  | 69        | 100%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart_bsd/os_display_manager.svg)


| Name | Computers | Percent |
|------|-----------|---------|
| SLiM | 68        | 98.55%  |
| GDM  | 1         | 1.45%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart_bsd/os_lang.svg)


| Lang  | Computers | Percent |
|-------|-----------|---------|
| en_US | 66        | 95.65%  |
| ru_RU | 1         | 1.45%   |
| es_ES | 1         | 1.45%   |
| de_DE | 1         | 1.45%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart_bsd/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 68        | 98.55%  |
| BIOS | 1         | 1.45%   |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart_bsd/os_filesystem.svg)


| Type   | Computers | Percent |
|--------|-----------|---------|
| Cd9660 | 44        | 62.86%  |
| Zfs    | 26        | 37.14%  |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart_bsd/os_part_scheme.svg)


| Type | Computers | Percent |
|------|-----------|---------|
| GPT  | 68        | 98.55%  |
| MBR  | 1         | 1.45%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart_bsd/node_vendor.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| Dell             | 12        | 17.39%  |
| Lenovo           | 10        | 14.49%  |
| Hewlett-Packard  | 8         | 11.59%  |
| ASUSTek Computer | 8         | 11.59%  |
| Apple            | 4         | 5.8%    |
| Intel            | 3         | 4.35%   |
| ASRock           | 3         | 4.35%   |
| Acer             | 3         | 4.35%   |
| Timi             | 2         | 2.9%    |
| Sony             | 2         | 2.9%    |
| Pegatron         | 2         | 2.9%    |
| MSI              | 2         | 2.9%    |
| TUXEDO           | 1         | 1.45%   |
| Toshiba          | 1         | 1.45%   |
| PCSTICK          | 1         | 1.45%   |
| Packard Bell     | 1         | 1.45%   |
| MACHINIST        | 1         | 1.45%   |
| Kraftway         | 1         | 1.45%   |
| HUAWEI           | 1         | 1.45%   |
| Gateway          | 1         | 1.45%   |
| Biostar          | 1         | 1.45%   |
| AMD              | 1         | 1.45%   |

Model
-----

Motherboard model

![Model](./images/pie_chart_bsd/node_model.svg)


| Name                                  | Computers | Percent |
|---------------------------------------|-----------|---------|
| HP 250 G6 Notebook PC                 | 2         | 2.9%    |
| Apple MacBook5,2                      | 2         | 2.9%    |
| Unknown                               | 2         | 2.9%    |
| TUXEDO Pulse 14 Gen1                  | 1         | 1.45%   |
| Toshiba Satellite S55t-B              | 1         | 1.45%   |
| Timi TM1701                           | 1         | 1.45%   |
| Timi RedmiBook Pro 15                 | 1         | 1.45%   |
| Sony VPCEB1J1E                        | 1         | 1.45%   |
| Sony VGN-AW21S_B                      | 1         | 1.45%   |
| Pegatron IPPPV-D3G                    | 1         | 1.45%   |
| Pegatron IPM41-D3                     | 1         | 1.45%   |
| Packard Bell EasyNote_MX52-B-071      | 1         | 1.45%   |
| MSI MS-7C37                           | 1         | 1.45%   |
| MSI MS-7A38                           | 1         | 1.45%   |
| MACHINIST X99-k9 V2.0                 | 1         | 1.45%   |
| Lenovo ThinkPad X270 W10DG 20K5S0BB00 | 1         | 1.45%   |
| Lenovo ThinkPad X250 20CLS23500       | 1         | 1.45%   |
| Lenovo ThinkPad X250 20CLS1WP01       | 1         | 1.45%   |
| Lenovo ThinkPad T440 20B7A0B7MS       | 1         | 1.45%   |
| Lenovo ThinkPad T420 4178A72          | 1         | 1.45%   |
| Lenovo ThinkCentre M93p 10AAA0WGUK    | 1         | 1.45%   |
| Lenovo ThinkCentre M700 10GS          | 1         | 1.45%   |
| Lenovo Legion 5 15ARH05 82B5          | 1         | 1.45%   |
| Lenovo IdeaPad 3 15IGL05 82BU         | 1         | 1.45%   |
| Lenovo G480 20149                     | 1         | 1.45%   |
| Kraftway KW10T                        | 1         | 1.45%   |
| Intel NUC8i7BEK                       | 1         | 1.45%   |
| Intel MAHOBAY                         | 1         | 1.45%   |
| Intel DN2800MT AAG23738-600           | 1         | 1.45%   |
| HUAWEI BOD-WXX9                       | 1         | 1.45%   |
| HP Slim Desktop S01-aF1xxx            | 1         | 1.45%   |
| HP OMEN by Laptop                     | 1         | 1.45%   |
| HP EliteDesk 800 G1 SFF               | 1         | 1.45%   |
| HP EliteBook 850 G3                   | 1         | 1.45%   |
| HP EliteBook 820 G1                   | 1         | 1.45%   |
| Gateway NE56R                         | 1         | 1.45%   |
| Dell Studio 1747                      | 1         | 1.45%   |
| Dell Precision 3440                   | 1         | 1.45%   |
| Dell OptiPlex 3010                    | 1         | 1.45%   |
| Dell Latitude E6540                   | 1         | 1.45%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart_bsd/node_model_family.svg)


| Name                  | Computers | Percent |
|-----------------------|-----------|---------|
| Lenovo ThinkPad       | 5         | 7.25%   |
| Dell Latitude         | 5         | 7.25%   |
| Dell Inspiron         | 4         | 5.8%    |
| Acer Aspire           | 3         | 4.35%   |
| Lenovo ThinkCentre    | 2         | 2.9%    |
| HP EliteBook          | 2         | 2.9%    |
| HP 250                | 2         | 2.9%    |
| Apple MacBook5        | 2         | 2.9%    |
| Unknown               | 2         | 2.9%    |
| TUXEDO Pulse          | 1         | 1.45%   |
| Toshiba Satellite     | 1         | 1.45%   |
| Timi TM1701           | 1         | 1.45%   |
| Timi RedmiBook        | 1         | 1.45%   |
| Sony VPCEB1J1E        | 1         | 1.45%   |
| Sony VGN-AW21S        | 1         | 1.45%   |
| Pegatron IPPPV-D3G    | 1         | 1.45%   |
| Pegatron IPM41-D3     | 1         | 1.45%   |
| Packard Bell EasyNote | 1         | 1.45%   |
| MSI MS-7C37           | 1         | 1.45%   |
| MSI MS-7A38           | 1         | 1.45%   |
| MACHINIST X99-k9      | 1         | 1.45%   |
| Lenovo Legion         | 1         | 1.45%   |
| Lenovo IdeaPad        | 1         | 1.45%   |
| Lenovo G480           | 1         | 1.45%   |
| Kraftway KW10T        | 1         | 1.45%   |
| Intel NUC8i7BEK       | 1         | 1.45%   |
| Intel MAHOBAY         | 1         | 1.45%   |
| Intel DN2800MT        | 1         | 1.45%   |
| HUAWEI BOD-WXX9       | 1         | 1.45%   |
| HP Slim               | 1         | 1.45%   |
| HP OMEN               | 1         | 1.45%   |
| HP EliteDesk          | 1         | 1.45%   |
| Gateway NE56R         | 1         | 1.45%   |
| Dell Studio           | 1         | 1.45%   |
| Dell Precision        | 1         | 1.45%   |
| Dell OptiPlex         | 1         | 1.45%   |
| Biostar G41D3C        | 1         | 1.45%   |
| ASUS VivoBook         | 1         | 1.45%   |
| ASUS UX31E            | 1         | 1.45%   |
| ASUS TUF              | 1         | 1.45%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart_bsd/node_year.svg)


| Year | Computers | Percent |
|------|-----------|---------|
| 2020 | 9         | 13.04%  |
| 2021 | 8         | 11.59%  |
| 2009 | 7         | 10.14%  |
| 2019 | 6         | 8.7%    |
| 2015 | 6         | 8.7%    |
| 2014 | 5         | 7.25%   |
| 2010 | 5         | 7.25%   |
| 2016 | 4         | 5.8%    |
| 2012 | 4         | 5.8%    |
| 2011 | 4         | 5.8%    |
| 2018 | 3         | 4.35%   |
| 2013 | 3         | 4.35%   |
| 2017 | 2         | 2.9%    |
| 2022 | 1         | 1.45%   |
| 2008 | 1         | 1.45%   |
| 2007 | 1         | 1.45%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart_bsd/node_formfactor.svg)


| Name       | Computers | Percent |
|------------|-----------|---------|
| Notebook   | 43        | 62.32%  |
| Desktop    | 24        | 34.78%  |
| Mini pc    | 1         | 1.45%   |
| All in one | 1         | 1.45%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart_bsd/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 69        | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart_bsd/node_ram_total.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| 4.01-8.0   | 23        | 33.33%  |
| 8.01-16.0  | 20        | 28.99%  |
| 16.01-24.0 | 17        | 24.64%  |
| 2.01-3.0   | 6         | 8.7%    |
| 32.01-64.0 | 2         | 2.9%    |
| 3.01-4.0   | 1         | 1.45%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart_bsd/node_ram_used.svg)


| Used GB  | Computers | Percent |
|----------|-----------|---------|
| 0.01-0.5 | 43        | 62.32%  |
| 0.51-1.0 | 17        | 24.64%  |
| 1.01-2.0 | 7         | 10.14%  |
| 4.01-8.0 | 1         | 1.45%   |
| 2.01-3.0 | 1         | 1.45%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart_bsd/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 46        | 65.71%  |
| 2      | 15        | 21.43%  |
| 3      | 3         | 4.29%   |
| 0      | 3         | 4.29%   |
| 6      | 1         | 1.43%   |
| 5      | 1         | 1.43%   |
| 4      | 1         | 1.43%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart_bsd/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 47        | 68.12%  |
| Yes       | 22        | 31.88%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart_bsd/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 60        | 86.96%  |
| No        | 9         | 13.04%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart_bsd/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 53        | 75.71%  |
| No        | 17        | 24.29%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart_bsd/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 39        | 56.52%  |
| No        | 30        | 43.48%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart_bsd/node_location.svg)


| Country      | Computers | Percent |
|--------------|-----------|---------|
| Russia       | 9         | 13.04%  |
| Germany      | 8         | 11.59%  |
| USA          | 7         | 10.14%  |
| Brazil       | 5         | 7.25%   |
| Spain        | 4         | 5.8%    |
| Ukraine      | 3         | 4.35%   |
| France       | 3         | 4.35%   |
| Canada       | 3         | 4.35%   |
| UK           | 2         | 2.9%    |
| Poland       | 2         | 2.9%    |
| Norway       | 2         | 2.9%    |
| Mexico       | 2         | 2.9%    |
| Hungary      | 2         | 2.9%    |
| China        | 2         | 2.9%    |
| Venezuela    | 1         | 1.45%   |
| UAE          | 1         | 1.45%   |
| Taiwan       | 1         | 1.45%   |
| South Africa | 1         | 1.45%   |
| Slovenia     | 1         | 1.45%   |
| Slovakia     | 1         | 1.45%   |
| Serbia       | 1         | 1.45%   |
| Romania      | 1         | 1.45%   |
| Peru         | 1         | 1.45%   |
| Italy        | 1         | 1.45%   |
| India        | 1         | 1.45%   |
| Georgia      | 1         | 1.45%   |
| Belarus      | 1         | 1.45%   |
| Argentina    | 1         | 1.45%   |
| Albania      | 1         | 1.45%   |

City
----

Geographic location (city)

![City](./images/pie_chart_bsd/node_city.svg)


| City                 | Computers | Percent |
|----------------------|-----------|---------|
| Volgograd            | 2         | 2.86%   |
| Munich               | 2         | 2.86%   |
| Moscow               | 2         | 2.86%   |
| LogroÃ±o           | 2         | 2.86%   |
| Yunlin               | 1         | 1.43%   |
| Warendorf            | 1         | 1.43%   |
| Voronezh             | 1         | 1.43%   |
| Vladivostok          | 1         | 1.43%   |
| Vancouver            | 1         | 1.43%   |
| Ufa                  | 1         | 1.43%   |
| Szeged               | 1         | 1.43%   |
| Surrey               | 1         | 1.43%   |
| Southminster         | 1         | 1.43%   |
| San Carlos del Zulia | 1         | 1.43%   |
| Salisbury            | 1         | 1.43%   |
| Rio das Ostras       | 1         | 1.43%   |
| Rho                  | 1         | 1.43%   |
| Reinsvoll            | 1         | 1.43%   |
| Redondela            | 1         | 1.43%   |
| Perm                 | 1         | 1.43%   |
| Ottawa               | 1         | 1.43%   |
| Odessa               | 1         | 1.43%   |
| Oakdale              | 1         | 1.43%   |
| Nesttun              | 1         | 1.43%   |
| Nanticoke            | 1         | 1.43%   |
| Monterrey            | 1         | 1.43%   |
| Mirepeix             | 1         | 1.43%   |
| Minsk                | 1         | 1.43%   |
| Mexico City          | 1         | 1.43%   |
| Mendoza              | 1         | 1.43%   |
| Medford              | 1         | 1.43%   |
| Maracanau            | 1         | 1.43%   |
| Linyi                | 1         | 1.43%   |
| Lima                 | 1         | 1.43%   |
| Lanzhou              | 1         | 1.43%   |
| Kyiv                 | 1         | 1.43%   |
| Kresnice             | 1         | 1.43%   |
| Kazincbarcika        | 1         | 1.43%   |
| Katowice             | 1         | 1.43%   |
| K'alak'i T'bilisi    | 1         | 1.43%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart_bsd/drive_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 17        | 20     | 18.48%  |
| Samsung Electronics | 11        | 13     | 11.96%  |
| WDC                 | 9         | 11     | 9.78%   |
| Kingston            | 9         | 9      | 9.78%   |
| Toshiba             | 8         | 8      | 8.7%    |
| Hitachi             | 8         | 8      | 8.7%    |
| Intel               | 5         | 5      | 5.43%   |
| SPCC                | 2         | 2      | 2.17%   |
| SK hynix            | 2         | 2      | 2.17%   |
| SanDisk             | 2         | 3      | 2.17%   |
| OCZ                 | 2         | 2      | 2.17%   |
| KingSpec            | 2         | 2      | 2.17%   |
| Fujitsu             | 2         | 2      | 2.17%   |
| Transcend           | 1         | 1      | 1.09%   |
| SSSTC               | 1         | 1      | 1.09%   |
| Patriot             | 1         | 1      | 1.09%   |
| Lexar               | 1         | 2      | 1.09%   |
| LDLC                | 1         | 1      | 1.09%   |
| KIOXIA              | 1         | 1      | 1.09%   |
| Intenso             | 1         | 1      | 1.09%   |
| GOODRAM             | 1         | 1      | 1.09%   |
| Gigabyte Technology | 1         | 1      | 1.09%   |
| FORESEE             | 1         | 1      | 1.09%   |
| Crucial             | 1         | 1      | 1.09%   |
| Corsair             | 1         | 1      | 1.09%   |
| A-DATA Technology   | 1         | 1      | 1.09%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart_bsd/drive_model.svg)


| Model                                     | Computers | Percent |
|-------------------------------------------|-----------|---------|
| Seagate ST1000LM035-1RK172 1TB            | 3         | 3%      |
| Toshiba MQ01ABF050 500GB                  | 2         | 2%      |
| Toshiba MQ01ABD050 500GB                  | 2         | 2%      |
| Samsung SSD 860 PRO 512GB                 | 2         | 2%      |
| Kingston SV300S37A120G 120GB              | 2         | 2%      |
| Kingston SA400S37120G 120GB               | 2         | 2%      |
| WDC WDS500G2X0C-00L350 500GB              | 1         | 1%      |
| WDC WDS500G2B0A 500GB                     | 1         | 1%      |
| WDC WDS240G2G0B-00EPW0 240GB              | 1         | 1%      |
| WDC WDBNCE5000PNC 500GB                   | 1         | 1%      |
| WDC WD5000LPCX-60VHAT0 500GB              | 1         | 1%      |
| WDC WD5000AVVS-63H0B1 500GB               | 1         | 1%      |
| WDC WD3003FZEX-00Z4SA0 3TB                | 1         | 1%      |
| WDC WD20EFRX-68EUZN0 2TB                  | 1         | 1%      |
| WDC WD10JPVX-75JC3T0 1TB                  | 1         | 1%      |
| WDC WD10JPVX-22JC3T0 1TB                  | 1         | 1%      |
| WDC PC SN530 SDBPNPZ-512G-1027 512GB      | 1         | 1%      |
| Transcend TS120GMTS420S 120GB             | 1         | 1%      |
| Toshiba TR200 480GB                       | 1         | 1%      |
| Toshiba MQ01ABD100 1TB                    | 1         | 1%      |
| Toshiba MK8034GSX 80GB                    | 1         | 1%      |
| Toshiba DT01ACA100 1TB                    | 1         | 1%      |
| SSSTC CL1-4D128 128GB                     | 1         | 1%      |
| SPCC Solid State Disk 56GB                | 1         | 1%      |
| SPCC Solid State Disk 512GB               | 1         | 1%      |
| SK hynix SKHynix_HFM512GDHTNI-87A0B 512GB | 1         | 1%      |
| SK hynix BC711 NVMe 256GB                 | 1         | 1%      |
| Seagate ST9500420AS 500GB                 | 1         | 1%      |
| Seagate ST9160821AS 160GB                 | 1         | 1%      |
| Seagate ST9120821AS 118GB                 | 1         | 1%      |
| Seagate ST500LT012-9WS142 500GB           | 1         | 1%      |
| Seagate ST500LT012-1DG142 500GB           | 1         | 1%      |
| Seagate ST4000DM004-2CV104 4TB            | 1         | 1%      |
| Seagate ST3250310AS 250GB                 | 1         | 1%      |
| Seagate ST320LT014-9YK142 320GB           | 1         | 1%      |
| Seagate ST3160811AS 160GB                 | 1         | 1%      |
| Seagate ST3000DM001-1CH166 3TB            | 1         | 1%      |
| Seagate ST250LT003-9YG14C 250GB           | 1         | 1%      |
| Seagate ST2000DM008-2FR102 2TB            | 1         | 1%      |
| Seagate ST2000DL003-9VT166 2TB            | 1         | 1%      |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart_bsd/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 17        | 20     | 41.46%  |
| Hitachi             | 8         | 8      | 19.51%  |
| Toshiba             | 7         | 7      | 17.07%  |
| WDC                 | 6         | 6      | 14.63%  |
| Samsung Electronics | 2         | 2      | 4.88%   |
| Fujitsu             | 1         | 1      | 2.44%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart_bsd/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 7         | 7      | 17.95%  |
| Kingston            | 7         | 7      | 17.95%  |
| Intel               | 4         | 4      | 10.26%  |
| WDC                 | 3         | 3      | 7.69%   |
| SPCC                | 2         | 2      | 5.13%   |
| SanDisk             | 2         | 3      | 5.13%   |
| OCZ                 | 2         | 2      | 5.13%   |
| KingSpec            | 2         | 2      | 5.13%   |
| Transcend           | 1         | 1      | 2.56%   |
| Toshiba             | 1         | 1      | 2.56%   |
| Patriot             | 1         | 1      | 2.56%   |
| Lexar               | 1         | 1      | 2.56%   |
| Intenso             | 1         | 1      | 2.56%   |
| GOODRAM             | 1         | 1      | 2.56%   |
| Gigabyte Technology | 1         | 1      | 2.56%   |
| Fujitsu             | 1         | 1      | 2.56%   |
| FORESEE             | 1         | 1      | 2.56%   |
| A-DATA Technology   | 1         | 1      | 2.56%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart_bsd/drive_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SSD  | 34        | 40     | 41.46%  |
| HDD  | 32        | 44     | 39.02%  |
| NVMe | 16        | 17     | 19.51%  |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart_bsd/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 59        | 84     | 78.67%  |
| NVMe | 16        | 17     | 21.33%  |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart_bsd/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 46        | 62     | 70.77%  |
| 0.51-1.0   | 13        | 15     | 20%     |
| 1.01-2.0   | 4         | 4      | 6.15%   |
| 3.01-4.0   | 1         | 1      | 1.54%   |
| 2.01-3.0   | 1         | 2      | 1.54%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart_bsd/drive_space_total.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| 1-20       | 40        | 57.97%  |
| 101-250    | 12        | 17.39%  |
| 251-500    | 9         | 13.04%  |
| 501-1000   | 4         | 5.8%    |
| 1001-2000  | 2         | 2.9%    |
| 21-50      | 1         | 1.45%   |
| 51-100     | 1         | 1.45%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart_bsd/drive_space_used.svg)


| Used GB  | Computers | Percent |
|----------|-----------|---------|
| 1-20     | 65        | 94.2%   |
| 101-250  | 2         | 2.9%    |
| 501-1000 | 1         | 1.45%   |
| 51-100   | 1         | 1.45%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart_bsd/drive_malfunc.svg)


| Model                             | Computers | Drives | Percent |
|-----------------------------------|-----------|--------|---------|
| WDC WD5000LPCX-60VHAT0 500GB      | 1         | 1      | 6.25%   |
| WDC WD5000AVVS-63H0B1 500GB       | 1         | 1      | 6.25%   |
| Toshiba MQ01ABF050 500GB          | 1         | 1      | 6.25%   |
| Toshiba MQ01ABD100 1TB            | 1         | 1      | 6.25%   |
| Toshiba MK8034GSX 80GB            | 1         | 1      | 6.25%   |
| Seagate ST9160821AS 160GB         | 1         | 1      | 6.25%   |
| Seagate ST500LT012-9WS142 500GB   | 1         | 1      | 6.25%   |
| Seagate ST320LT014-9YK142 320GB   | 1         | 1      | 6.25%   |
| Samsung Electronics HD501LJ 500GB | 1         | 1      | 6.25%   |
| OCZ VERTEX3 240GB                 | 1         | 1      | 6.25%   |
| Hitachi HTS727550A9E364 500GB     | 1         | 1      | 6.25%   |
| Hitachi HTS545050A7E380 500GB     | 1         | 1      | 6.25%   |
| Hitachi HTS545025B9SA02 250GB     | 1         | 1      | 6.25%   |
| Hitachi HTS541680J9SA00 80GB      | 1         | 1      | 6.25%   |
| Hitachi HTS541612J9SA00 120GB     | 1         | 1      | 6.25%   |
| Fujitsu MHZ2160BH FFS G1 160GB    | 1         | 1      | 6.25%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart_bsd/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Hitachi             | 5         | 5      | 31.25%  |
| Toshiba             | 3         | 3      | 18.75%  |
| Seagate             | 3         | 3      | 18.75%  |
| WDC                 | 2         | 2      | 12.5%   |
| Samsung Electronics | 1         | 1      | 6.25%   |
| OCZ                 | 1         | 1      | 6.25%   |
| Fujitsu             | 1         | 1      | 6.25%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart_bsd/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Hitachi             | 5         | 5      | 33.33%  |
| Toshiba             | 3         | 3      | 20%     |
| Seagate             | 3         | 3      | 20%     |
| WDC                 | 2         | 2      | 13.33%  |
| Samsung Electronics | 1         | 1      | 6.67%   |
| Fujitsu             | 1         | 1      | 6.67%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart_bsd/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 13        | 15     | 92.86%  |
| SSD  | 1         | 1      | 7.14%   |

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


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Works    | 55        | 80     | 78.57%  |
| Malfunc  | 13        | 16     | 18.57%  |
| Detected | 2         | 5      | 2.86%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart_bsd/storage_vendor.svg)


| Vendor                         | Computers | Percent |
|--------------------------------|-----------|---------|
| Intel                          | 51        | 60.71%  |
| AMD                            | 9         | 10.71%  |
| Samsung Electronics            | 4         | 4.76%   |
| Nvidia                         | 4         | 4.76%   |
| SK hynix                       | 2         | 2.38%   |
| SanDisk                        | 2         | 2.38%   |
| Kingston Technology Company    | 2         | 2.38%   |
| JMicron Technology             | 2         | 2.38%   |
| Solid State Storage Technology | 1         | 1.19%   |
| Silicon Motion                 | 1         | 1.19%   |
| Shenzhen Longsys Electronics   | 1         | 1.19%   |
| Phison Electronics             | 1         | 1.19%   |
| Micron/Crucial Technology      | 1         | 1.19%   |
| Marvell Technology Group       | 1         | 1.19%   |
| KIOXIA                         | 1         | 1.19%   |
| ASMedia Technology             | 1         | 1.19%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart_bsd/storage_model.svg)


| Model                                                                            | Computers | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                              | 6         | 6.59%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 5         | 5.49%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 5         | 5.49%   |
| Nvidia MCP79 AHCI Controller                                                     | 4         | 4.4%    |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                               | 4         | 4.4%    |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 4         | 4.4%    |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                | 3         | 3.3%    |
| Intel Celeron/Pentium Silver Processor SATA Controller                           | 3         | 3.3%    |
| Intel 82801G (ICH7 Family) IDE Controller                                        | 3         | 3.3%    |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 2         | 2.2%    |
| JMicron JMB368 IDE controller                                                    | 2         | 2.2%    |
| Intel Atom Processor E3800 Series SATA AHCI Controller                           | 2         | 2.2%    |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]            | 2         | 2.2%    |
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 2         | 2.2%    |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 2         | 2.2%    |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 2         | 2.2%    |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 2         | 2.2%    |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller    | 2         | 2.2%    |
| Unknown                                                                          | 2         | 2.2%    |
| SK hynix Gold P31 SSD                                                            | 1         | 1.1%    |
| SK hynix BC511                                                                   | 1         | 1.1%    |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                  | 1         | 1.1%    |
| Shenzhen Longsys SM2263EN/SM2263XT-based OEM SSD                                 | 1         | 1.1%    |
| SanDisk WD Blue SN550 NVMe SSD                                                   | 1         | 1.1%    |
| SanDisk WD Black 2018/SN750 / PC SN720 NVMe SSD                                  | 1         | 1.1%    |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                    | 1         | 1.1%    |
| Samsung NVMe SSD Controller 980                                                  | 1         | 1.1%    |
| Phison E12 NVMe Controller                                                       | 1         | 1.1%    |
| Micron/Crucial P2 NVMe PCIe SSD                                                  | 1         | 1.1%    |
| Marvell Group 88SE9235 PCIe 2.0 x2 4-port SATA 6 Gb/s Controller                 | 1         | 1.1%    |
| KIOXIA NVMe SSD Controller BG4                                                   | 1         | 1.1%    |
| Kingston Company A2000 NVMe SSD                                                  | 1         | 1.1%    |
| Intel SSD Pro 7600p/760p/E 6100p Series                                          | 1         | 1.1%    |
| Intel SATA Controller [RAID mode]                                                | 1         | 1.1%    |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]    | 1         | 1.1%    |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                            | 1         | 1.1%    |
| Intel Comet Lake SATA AHCI Controller                                            | 1         | 1.1%    |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                | 1         | 1.1%    |
| Intel C610/X99 series chipset sSATA Controller [AHCI mode]                       | 1         | 1.1%    |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 1         | 1.1%    |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart_bsd/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 55        | 65.48%  |
| NVMe | 16        | 19.05%  |
| IDE  | 10        | 11.9%   |
| RAID | 3         | 3.57%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart_bsd/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 60        | 86.96%  |
| AMD    | 9         | 13.04%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart_bsd/cpu_model.svg)


| Model                                       | Computers | Percent |
|---------------------------------------------|-----------|---------|
| Intel Core i7-6600U CPU @ 2.60GHz           | 2         | 2.9%    |
| Intel Core i5-5300U CPU @ 2.30GHz           | 2         | 2.9%    |
| Intel Core i5-5200U CPU @ 2.20GHz           | 2         | 2.9%    |
| Intel Core 2 Duo CPU P7450 @ 2.13GHz        | 2         | 2.9%    |
| AMD Ryzen 7 4800H with Radeon Graphics      | 2         | 2.9%    |
| Intel Xeon CPU E5-2630L v4 @ 1.80GHz        | 1         | 1.45%   |
| Intel Pentium Silver N5000 CPU @ 1.10GHz    | 1         | 1.45%   |
| Intel Pentium Silver J5040 CPU @ 2.00GHz    | 1         | 1.45%   |
| Intel Pentium Dual-Core CPU E6700 @ 3.20GHz | 1         | 1.45%   |
| Intel Pentium Dual-Core CPU E5700 @ 3.00GHz | 1         | 1.45%   |
| Intel Pentium Dual-Core CPU E5400 @ 2.70GHz | 1         | 1.45%   |
| Intel Pentium Dual-Core CPU E5200 @ 2.50GHz | 1         | 1.45%   |
| Intel Pentium CPU N3700 @ 1.60GHz           | 1         | 1.45%   |
| Intel Pentium CPU G4400 @ 3.30GHz           | 1         | 1.45%   |
| Intel Pentium CPU 4417U @ 2.30GHz           | 1         | 1.45%   |
| Intel CPU Version                           | 1         | 1.45%   |
| Intel Core i7-9700 CPU @ 3.00GHz            | 1         | 1.45%   |
| Intel Core i7-8559U CPU @ 2.70GHz           | 1         | 1.45%   |
| Intel Core i7-8550U CPU @ 1.80GHz           | 1         | 1.45%   |
| Intel Core i7-5500U CPU @ 2.40GHz           | 1         | 1.45%   |
| Intel Core i7-4810MQ CPU @ 2.80GHz          | 1         | 1.45%   |
| Intel Core i7-4790 CPU @ 3.60GHz            | 1         | 1.45%   |
| Intel Core i7-2677M CPU @ 1.80GHz           | 1         | 1.45%   |
| Intel Core i7-2620M CPU @ 2.70GHz           | 1         | 1.45%   |
| Intel Core i5-7200U CPU @ 2.50GHz           | 1         | 1.45%   |
| Intel Core i5-6440HQ CPU @ 2.60GHz          | 1         | 1.45%   |
| Intel Core i5-6300U CPU @ 2.40GHz           | 1         | 1.45%   |
| Intel Core i5-6300HQ CPU @ 2.30GHz          | 1         | 1.45%   |
| Intel Core i5-6200U CPU @ 2.30GHz           | 1         | 1.45%   |
| Intel Core i5-4570T CPU @ 2.90GHz           | 1         | 1.45%   |
| Intel Core i5-4310U CPU @ 2.00GHz           | 1         | 1.45%   |
| Intel Core i5-4300U CPU @ 1.90GHz           | 1         | 1.45%   |
| Intel Core i5-3470 CPU @ 3.20GHz            | 1         | 1.45%   |
| Intel Core i5-2540M CPU @ 2.60GHz           | 1         | 1.45%   |
| Intel Core i5-2520M CPU @ 2.50GHz           | 1         | 1.45%   |
| Intel Core i3-7020U CPU @ 2.30GHz           | 1         | 1.45%   |
| Intel Core i3-5010U CPU @ 2.10GHz           | 1         | 1.45%   |
| Intel Core i3-3220 CPU @ 3.30GHz            | 1         | 1.45%   |
| Intel Core i3-2350M CPU @ 2.30GHz           | 1         | 1.45%   |
| Intel Core i3-10100 CPU @ 3.60GHz           | 1         | 1.45%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart_bsd/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 15        | 21.74%  |
| Intel Core i7           | 10        | 14.49%  |
| Intel Core i3           | 6         | 8.7%    |
| Intel Core 2 Duo        | 6         | 8.7%    |
| Other                   | 5         | 7.25%   |
| Intel Atom              | 5         | 7.25%   |
| Intel Pentium Dual-Core | 4         | 5.8%    |
| Intel Pentium           | 3         | 4.35%   |
| Intel Celeron           | 3         | 4.35%   |
| AMD Ryzen 5             | 3         | 4.35%   |
| Intel Pentium Silver    | 2         | 2.9%    |
| AMD Ryzen 7             | 2         | 2.9%    |
| Intel Xeon              | 1         | 1.45%   |
| Intel Core 2 Quad       | 1         | 1.45%   |
| AMD Ryzen 9             | 1         | 1.45%   |
| AMD FX                  | 1         | 1.45%   |
| AMD Athlon 64 X2        | 1         | 1.45%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart_bsd/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 34        | 49.28%  |
| 4       | 17        | 24.64%  |
| Unknown | 6         | 8.7%    |
| 8       | 3         | 4.35%   |
| 16      | 2         | 2.9%    |
| 12      | 2         | 2.9%    |
| 1       | 2         | 2.9%    |
| 24      | 1         | 1.45%   |
| 10      | 1         | 1.45%   |
| 6       | 1         | 1.45%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart_bsd/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 65        | 94.2%   |
| 2      | 4         | 5.8%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart_bsd/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 35        | 50.72%  |
| 1       | 28        | 40.58%  |
| Unknown | 6         | 8.7%    |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart_bsd/cpu_microarch.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| Penryn        | 10        | 14.49%  |
| Skylake       | 7         | 10.14%  |
| Broadwell     | 7         | 10.14%  |
| SandyBridge   | 6         | 8.7%    |
| KabyLake      | 6         | 8.7%    |
| Haswell       | 5         | 7.25%   |
| Zen 2         | 4         | 5.8%    |
| Silvermont    | 4         | 5.8%    |
| Goldmont plus | 3         | 4.35%   |
| Bonnell       | 3         | 4.35%   |
| TigerLake     | 2         | 2.9%    |
| IvyBridge     | 2         | 2.9%    |
| Unknown       | 2         | 2.9%    |
| Zen 3         | 1         | 1.45%   |
| Zen           | 1         | 1.45%   |
| Westmere      | 1         | 1.45%   |
| Nehalem       | 1         | 1.45%   |
| K8 Hammer     | 1         | 1.45%   |
| Excavator     | 1         | 1.45%   |
| Core          | 1         | 1.45%   |
| CometLake     | 1         | 1.45%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart_bsd/gpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 48        | 58.54%  |
| Nvidia | 21        | 25.61%  |
| AMD    | 13        | 15.85%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart_bsd/gpu_model.svg)


| Model                                                                       | Computers | Percent |
|-----------------------------------------------------------------------------|-----------|---------|
| Intel HD Graphics 5500                                                      | 6         | 7.32%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 6         | 7.32%   |
| Intel Skylake GT2 [HD Graphics 520]                                         | 4         | 4.88%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                | 3         | 3.66%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]        | 2         | 2.44%   |
| Nvidia C79 [GeForce 9400M G]                                                | 2         | 2.44%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 2         | 2.44%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller            | 2         | 2.44%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                   | 2         | 2.44%   |
| Intel HD Graphics 620                                                       | 2         | 2.44%   |
| Intel HD Graphics 530                                                       | 2         | 2.44%   |
| Intel Haswell-ULT Integrated Graphics Controller                            | 2         | 2.44%   |
| Intel GeminiLake [UHD Graphics 605]                                         | 2         | 2.44%   |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller     | 2         | 2.44%   |
| AMD Renoir                                                                  | 2         | 2.44%   |
| Nvidia TU117M [GeForce MX450]                                               | 1         | 1.22%   |
| Nvidia TU117M                                                               | 1         | 1.22%   |
| Nvidia TU116 [GeForce GTX 1660]                                             | 1         | 1.22%   |
| Nvidia TU116 [GeForce GTX 1660 Ti]                                          | 1         | 1.22%   |
| Nvidia GT218 [GeForce 210]                                                  | 1         | 1.22%   |
| Nvidia GP108M [GeForce MX150]                                               | 1         | 1.22%   |
| Nvidia GM206 [GeForce GTX 950]                                              | 1         | 1.22%   |
| Nvidia GM108M [GeForce MX110]                                               | 1         | 1.22%   |
| Nvidia GM107M [GeForce GTX 950M]                                            | 1         | 1.22%   |
| Nvidia GK104 [GeForce GTX 760]                                              | 1         | 1.22%   |
| Nvidia GF119M [Quadro NVS 4200M]                                            | 1         | 1.22%   |
| Nvidia GF108M [GeForce 610M]                                                | 1         | 1.22%   |
| Nvidia G96CM [GeForce 9600M GT]                                             | 1         | 1.22%   |
| Nvidia G84 [GeForce 8600 GTS]                                               | 1         | 1.22%   |
| Nvidia G73 [GeForce 7600 GS]                                                | 1         | 1.22%   |
| Nvidia C79 [GeForce 9400]                                                   | 1         | 1.22%   |
| Nvidia C79 [GeForce 9400M]                                                  | 1         | 1.22%   |
| Intel UHD Graphics 620                                                      | 1         | 1.22%   |
| Intel RocketLake-S GT1 [UHD Graphics 730]                                   | 1         | 1.22%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                | 1         | 1.22%   |
| Intel Kaby Lake-U GT1 Integrated Graphics Controller                        | 1         | 1.22%   |
| Intel HD Graphics 510                                                       | 1         | 1.22%   |
| Intel GeminiLake [UHD Graphics 600]                                         | 1         | 1.22%   |
| Intel Core Processor Integrated Graphics Controller                         | 1         | 1.22%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                    | 1         | 1.22%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart_bsd/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 33        | 47.83%  |
| 1 x Nvidia     | 12        | 17.39%  |
| Intel + Nvidia | 8         | 11.59%  |
| 1 x AMD        | 8         | 11.59%  |
| Intel + AMD    | 4         | 5.8%    |
| 2 x Intel      | 3         | 4.35%   |
| AMD + Nvidia   | 1         | 1.45%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart_bsd/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 52        | 75.36%  |
| Proprietary | 11        | 15.94%  |
| Unknown     | 6         | 8.7%    |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart_bsd/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 54        | 78.26%  |
| 0.01-0.5   | 6         | 8.7%    |
| 1.01-2.0   | 3         | 4.35%   |
| 5.01-6.0   | 2         | 2.9%    |
| 3.01-4.0   | 2         | 2.9%    |
| 7.01-8.0   | 1         | 1.45%   |
| 0.51-1.0   | 1         | 1.45%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart_bsd/mon_vendor.svg)


| Vendor               | Computers | Percent |
|----------------------|-----------|---------|
| LG Display           | 9         | 14.52%  |
| AU Optronics         | 8         | 12.9%   |
| BOE                  | 5         | 8.06%   |
| Apple                | 5         | 8.06%   |
| Samsung Electronics  | 4         | 6.45%   |
| Dell                 | 4         | 6.45%   |
| Chimei Innolux       | 4         | 6.45%   |
| Goldstar             | 3         | 4.84%   |
| Hewlett-Packard      | 2         | 3.23%   |
| BenQ                 | 2         | 3.23%   |
| AOC                  | 2         | 3.23%   |
| Vizio                | 1         | 1.61%   |
| Toshiba              | 1         | 1.61%   |
| TMX                  | 1         | 1.61%   |
| Philips              | 1         | 1.61%   |
| Nvidia               | 1         | 1.61%   |
| MSI                  | 1         | 1.61%   |
| LG Philips           | 1         | 1.61%   |
| Insignia             | 1         | 1.61%   |
| Iiyama               | 1         | 1.61%   |
| HannStar             | 1         | 1.61%   |
| Fujitsu Siemens      | 1         | 1.61%   |
| CPT                  | 1         | 1.61%   |
| Ancor Communications | 1         | 1.61%   |
| Acer                 | 1         | 1.61%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart_bsd/mon_model.svg)


| Model                                                                 | Computers | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| LG Display LCD Monitor LGD0484 1366x768 340x190mm 15.3-inch           | 2         | 3.17%   |
| Apple Color LCD APP9C5C 1280x800 290x180mm 13.4-inch                  | 2         | 3.17%   |
| Vizio D43-D2 VIZ1004 1920x1080 930x520mm 41.9-inch                    | 1         | 1.59%   |
| Toshiba TV TSB0110 1920x1080 1110x620mm 50.1-inch                     | 1         | 1.59%   |
| TMX LCD Monitor TMX1560 3200x2000 340x210mm 15.7-inch                 | 1         | 1.59%   |
| Samsung Electronics SyncMaster SAM0601 1600x900                       | 1         | 1.59%   |
| Samsung Electronics SyncMaster SAM05FF 1600x900 440x250mm 19.9-inch   | 1         | 1.59%   |
| Samsung Electronics SMS23A550H SAM07C9 1920x1080 510x290mm 23.1-inch  | 1         | 1.59%   |
| Samsung Electronics LCD Monitor SEC4149 1366x768 280x170mm 12.9-inch  | 1         | 1.59%   |
| Samsung Electronics LCD Monitor SDC4C48 1920x1080 340x190mm 15.3-inch | 1         | 1.59%   |
| Philips PHL 223V5 PHLC0CF 1920x1080 480x270mm 21.7-inch               | 1         | 1.59%   |
| Nvidia LCD Monitor NVD0200 1920x1080 320x180mm 14.5-inch              | 1         | 1.59%   |
| MSI MAG342CQRV MSI3DB6 3440x1440 790x330mm 33.7-inch                  | 1         | 1.59%   |
| LG Philips LCD Monitor LPLE300 1280x800 330x210mm 15.4-inch           | 1         | 1.59%   |
| LG Display LCD Monitor LGD0532 1920x1080 340x190mm 15.3-inch          | 1         | 1.59%   |
| LG Display LCD Monitor LGD0470 1920x1080 350x190mm 15.7-inch          | 1         | 1.59%   |
| LG Display LCD Monitor LGD046F 1920x1080 340x190mm 15.3-inch          | 1         | 1.59%   |
| LG Display LCD Monitor LGD0435 1600x900 310x170mm 13.9-inch           | 1         | 1.59%   |
| LG Display LCD Monitor LGD03EE 1366x768 280x160mm 12.7-inch           | 1         | 1.59%   |
| LG Display LCD Monitor LGD02DC 1366x768 340x190mm 15.3-inch           | 1         | 1.59%   |
| LG Display LCD Monitor LGD021D 1600x900 380x210mm 17.1-inch           | 1         | 1.59%   |
| Insignia 32DR310NA17 BBY3253 1680x1050 700x390mm 31.5-inch            | 1         | 1.59%   |
| Iiyama PLE2407HDS IVM560D 1920x1080 520x300mm 23.6-inch               | 1         | 1.59%   |
| Hewlett-Packard LCD Monitor HWP26A4 1440x900 410x260mm 19.1-inch      | 1         | 1.59%   |
| Hewlett-Packard 27xi HWP3038 1920x1080 600x340mm 27.2-inch            | 1         | 1.59%   |
| HannStar LCD Monitor HSD03E9 1024x600 220x130mm 10.1-inch             | 1         | 1.59%   |
| Goldstar LG ULTRAWIDE GSM5AE2 3440x1440 800x340mm 34.2-inch           | 1         | 1.59%   |
| Goldstar L1918S GSM4B31 1280x1024 380x300mm 19.1-inch                 | 1         | 1.59%   |
| Goldstar 2D FHD LG TV GSM59C6 1920x1080 510x290mm 23.1-inch           | 1         | 1.59%   |
| Fujitsu Siemens XE17-4 FUS0674 1280x1024 340x270mm 17.1-inch          | 1         | 1.59%   |
| Dell S2316H DELD07E 1920x1080 510x290mm 23.1-inch                     | 1         | 1.59%   |
| Dell P2412H DELA07D 1920x1080 530x300mm 24.0-inch                     | 1         | 1.59%   |
| Dell E2216HV DELF06F 1920x1080 480x270mm 21.7-inch                    | 1         | 1.59%   |
| Dell D1918H DEL2005 1366x768 410x230mm 18.5-inch                      | 1         | 1.59%   |
| CPT LCD Monitor COR17DB 1600x900 290x160mm 13.0-inch                  | 1         | 1.59%   |
| Chimei Innolux LCD Monitor CMN15E6 1366x768 340x190mm 15.3-inch       | 1         | 1.59%   |
| Chimei Innolux LCD Monitor CMN15E3 1920x1080 340x190mm 15.3-inch      | 1         | 1.59%   |
| Chimei Innolux LCD Monitor CMN14D5 1920x1080 310x170mm 13.9-inch      | 1         | 1.59%   |
| Chimei Innolux LCD Monitor CMN1470 1366x768 300x170mm 13.6-inch       | 1         | 1.59%   |
| BOE LCD Monitor BOE0872 1920x1080 340x190mm 15.3-inch                 | 1         | 1.59%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart_bsd/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 23        | 37.7%   |
| 1366x768 (WXGA)    | 15        | 24.59%  |
| 1600x900 (HD+)     | 5         | 8.2%    |
| 1280x800 (WXGA)    | 5         | 8.2%    |
| 1680x1050 (WSXGA+) | 4         | 6.56%   |
| 3440x1440          | 2         | 3.28%   |
| 1280x1024 (SXGA)   | 2         | 3.28%   |
| 3200x2000          | 1         | 1.64%   |
| 2560x1440 (QHD)    | 1         | 1.64%   |
| 1920x1200 (WUXGA)  | 1         | 1.64%   |
| 1440x900 (WXGA+)   | 1         | 1.64%   |
| 1024x600           | 1         | 1.64%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart_bsd/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 18        | 28.57%  |
| 13      | 11        | 17.46%  |
| 12      | 5         | 7.94%   |
| 24      | 4         | 6.35%   |
| 23      | 4         | 6.35%   |
| 19      | 3         | 4.76%   |
| 21      | 2         | 3.17%   |
| 20      | 2         | 3.17%   |
| 17      | 2         | 3.17%   |
| 10      | 2         | 3.17%   |
| 50      | 1         | 1.59%   |
| 41      | 1         | 1.59%   |
| 34      | 1         | 1.59%   |
| 33      | 1         | 1.59%   |
| 31      | 1         | 1.59%   |
| 27      | 1         | 1.59%   |
| 22      | 1         | 1.59%   |
| 18      | 1         | 1.59%   |
| 14      | 1         | 1.59%   |
| Unknown | 1         | 1.59%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart_bsd/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 25        | 39.68%  |
| 201-300     | 13        | 20.63%  |
| 501-600     | 9         | 14.29%  |
| 401-500     | 8         | 12.7%   |
| 701-800     | 2         | 3.17%   |
| 351-400     | 2         | 3.17%   |
| 601-700     | 1         | 1.59%   |
| 1001-1500   | 1         | 1.59%   |
| 901-1000    | 1         | 1.59%   |
| Unknown     | 1         | 1.59%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart_bsd/mon_ratio.svg)


| Ratio | Computers | Percent |
|-------|-----------|---------|
| 16/9  | 45        | 73.77%  |
| 16/10 | 12        | 19.67%  |
| 5/4   | 2         | 3.28%   |
| 21/9  | 2         | 3.28%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart_bsd/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 91-100         | 14        | 22.22%  |
| 81-90          | 10        | 15.87%  |
| 201-250        | 10        | 15.87%  |
| 151-200        | 5         | 7.94%   |
| 61-70          | 4         | 6.35%   |
| 71-80          | 3         | 4.76%   |
| 351-500        | 3         | 4.76%   |
| 101-110        | 3         | 4.76%   |
| 41-50          | 2         | 3.17%   |
| 141-150        | 2         | 3.17%   |
| More than 1000 | 1         | 1.59%   |
| 301-350        | 1         | 1.59%   |
| 251-300        | 1         | 1.59%   |
| 121-130        | 1         | 1.59%   |
| 111-120        | 1         | 1.59%   |
| 501-1000       | 1         | 1.59%   |
| Unknown        | 1         | 1.59%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart_bsd/mon_density.svg)


| Density | Computers | Percent |
|---------|-----------|---------|
| 101-120 | 22        | 34.92%  |
| 51-100  | 19        | 30.16%  |
| 121-160 | 16        | 25.4%   |
| 161-240 | 4         | 6.35%   |
| 1-50    | 1         | 1.59%   |
| Unknown | 1         | 1.59%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart_bsd/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 59        | 85.51%  |
| 0     | 7         | 10.14%  |
| 2     | 3         | 4.35%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart_bsd/net_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Intel                    | 38        | 36.89%  |
| Realtek Semiconductor    | 30        | 29.13%  |
| Qualcomm Atheros         | 11        | 10.68%  |
| Broadcom                 | 8         | 7.77%   |
| Nvidia                   | 4         | 3.88%   |
| Ralink Technology        | 2         | 1.94%   |
| Marvell Technology Group | 2         | 1.94%   |
| Sierra Wireless          | 1         | 0.97%   |
| Samsung Electronics      | 1         | 0.97%   |
| Ralink                   | 1         | 0.97%   |
| IMC Networks             | 1         | 0.97%   |
| Huawei Technologies      | 1         | 0.97%   |
| Edimax Technology        | 1         | 0.97%   |
| D-Link System            | 1         | 0.97%   |
| ASUSTek Computer         | 1         | 0.97%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart_bsd/net_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller              | 25        | 21.01%  |
| Intel Wireless 7265                                                            | 6         | 5.04%   |
| Nvidia MCP79 Ethernet                                                          | 4         | 3.36%   |
| Intel Wireless 8265 / 8275                                                     | 4         | 3.36%   |
| Intel Wi-Fi 6 AX200                                                            | 4         | 3.36%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                               | 3         | 2.52%   |
| Intel Ethernet Connection I217-LM                                              | 3         | 2.52%   |
| Intel Ethernet Connection (3) I218-LM                                          | 3         | 2.52%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                          | 3         | 2.52%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller                         | 3         | 2.52%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                       | 2         | 1.68%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                                        | 2         | 1.68%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                 | 2         | 1.68%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                          | 2         | 1.68%   |
| Intel Wireless 8260                                                            | 2         | 1.68%   |
| Intel Wireless 3160                                                            | 2         | 1.68%   |
| Intel WiFi Link 5100                                                           | 2         | 1.68%   |
| Intel Wi-Fi 6 AX201                                                            | 2         | 1.68%   |
| Intel Ethernet Connection I219-LM                                              | 2         | 1.68%   |
| Intel Ethernet Connection I218-LM                                              | 2         | 1.68%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                               | 2         | 1.68%   |
| Intel 82574L Gigabit Network Connection                                        | 2         | 1.68%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                                | 2         | 1.68%   |
| Sierra Wireless EM7455                                                         | 1         | 0.84%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)                    | 1         | 0.84%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                                | 1         | 0.84%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                                     | 1         | 0.84%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                          | 1         | 0.84%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                          | 1         | 0.84%   |
| Ralink RT5370 Wireless Adapter                                                 | 1         | 0.84%   |
| Ralink RT2870/RT3070 Wireless Adapter                                          | 1         | 0.84%   |
| Ralink RT5390 Wireless 802.11n 1T/1R PCIe                                      | 1         | 0.84%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                     | 1         | 0.84%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                     | 1         | 0.84%   |
| Qualcomm Atheros AR8162 Fast Ethernet                                          | 1         | 0.84%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                                     | 1         | 0.84%   |
| Qualcomm Atheros AR5212 802.11abg NIC                                          | 1         | 0.84%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express)        | 1         | 0.84%   |
| Marvell Group Yukon Optima 88E8059 [PCIe Gigabit Ethernet Controller with AVB] | 1         | 0.84%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller                        | 1         | 0.84%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart_bsd/net_wireless_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Intel                 | 28        | 49.12%  |
| Qualcomm Atheros      | 9         | 15.79%  |
| Realtek Semiconductor | 6         | 10.53%  |
| Broadcom              | 6         | 10.53%  |
| Ralink Technology     | 2         | 3.51%   |
| Sierra Wireless       | 1         | 1.75%   |
| Ralink                | 1         | 1.75%   |
| IMC Networks          | 1         | 1.75%   |
| Edimax Technology     | 1         | 1.75%   |
| D-Link System         | 1         | 1.75%   |
| ASUSTek Computer      | 1         | 1.75%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart_bsd/net_wireless_model.svg)


| Model                                                                       | Computers | Percent |
|-----------------------------------------------------------------------------|-----------|---------|
| Intel Wireless 7265                                                         | 6         | 10.53%  |
| Intel Wireless 8265 / 8275                                                  | 4         | 7.02%   |
| Intel Wi-Fi 6 AX200                                                         | 4         | 7.02%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                            | 3         | 5.26%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller                      | 3         | 5.26%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                    | 2         | 3.51%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                                     | 2         | 3.51%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)              | 2         | 3.51%   |
| Intel Wireless 8260                                                         | 2         | 3.51%   |
| Intel Wireless 3160                                                         | 2         | 3.51%   |
| Intel WiFi Link 5100                                                        | 2         | 3.51%   |
| Intel Wi-Fi 6 AX201                                                         | 2         | 3.51%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                            | 2         | 3.51%   |
| Sierra Wireless EM7455                                                      | 1         | 1.75%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                             | 1         | 1.75%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                                  | 1         | 1.75%   |
| Ralink RT5370 Wireless Adapter                                              | 1         | 1.75%   |
| Ralink RT2870/RT3070 Wireless Adapter                                       | 1         | 1.75%   |
| Ralink RT5390 Wireless 802.11n 1T/1R PCIe                                   | 1         | 1.75%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                  | 1         | 1.75%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                  | 1         | 1.75%   |
| Qualcomm Atheros AR5212 802.11abg NIC                                       | 1         | 1.75%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express)     | 1         | 1.75%   |
| Intel Wireless 7260                                                         | 1         | 1.75%   |
| Intel Gemini Lake PCH CNVi WiFi                                             | 1         | 1.75%   |
| Intel Centrino Ultimate-N 6300                                              | 1         | 1.75%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                                | 1         | 1.75%   |
| IMC Networks Realtek RTL8191SU Wireless LAN 802.11n USB 2.0 Network Adapter | 1         | 1.75%   |
| Edimax EW-7612UAn V2 802.11n Wireless Adapter [Realtek RTL8192CU]           | 1         | 1.75%   |
| D-Link System DWA-125 Wireless N 150 Adapter(rev.A1) [Ralink RT3070]        | 1         | 1.75%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                          | 1         | 1.75%   |
| Broadcom BCM43224 802.11a/b/g/n                                             | 1         | 1.75%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                         | 1         | 1.75%   |
| ASUS N10 Nano 802.11n Network Adapter [Realtek RTL8192CU]                   | 1         | 1.75%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart_bsd/net_ethernet_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 27        | 45%     |
| Intel                    | 20        | 33.33%  |
| Qualcomm Atheros         | 4         | 6.67%   |
| Nvidia                   | 4         | 6.67%   |
| Marvell Technology Group | 2         | 3.33%   |
| Broadcom                 | 2         | 3.33%   |
| Samsung Electronics      | 1         | 1.67%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart_bsd/net_ethernet_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller              | 25        | 40.98%  |
| Nvidia MCP79 Ethernet                                                          | 4         | 6.56%   |
| Intel Ethernet Connection I217-LM                                              | 3         | 4.92%   |
| Intel Ethernet Connection (3) I218-LM                                          | 3         | 4.92%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                          | 3         | 4.92%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                          | 2         | 3.28%   |
| Intel Ethernet Connection I219-LM                                              | 2         | 3.28%   |
| Intel Ethernet Connection I218-LM                                              | 2         | 3.28%   |
| Intel 82574L Gigabit Network Connection                                        | 2         | 3.28%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                                | 2         | 3.28%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)                    | 1         | 1.64%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                          | 1         | 1.64%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                          | 1         | 1.64%   |
| Qualcomm Atheros AR8162 Fast Ethernet                                          | 1         | 1.64%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                                     | 1         | 1.64%   |
| Marvell Group Yukon Optima 88E8059 [PCIe Gigabit Ethernet Controller with AVB] | 1         | 1.64%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller                        | 1         | 1.64%   |
| Intel Ethernet Controller I225-V                                               | 1         | 1.64%   |
| Intel Ethernet Connection (6) I219-V                                           | 1         | 1.64%   |
| Intel Ethernet Connection (4) I219-LM                                          | 1         | 1.64%   |
| Intel Ethernet Connection (2) I219-V                                           | 1         | 1.64%   |
| Intel Ethernet Connection (2) I219-LM                                          | 1         | 1.64%   |
| Intel Ethernet Connection (11) I219-LM                                         | 1         | 1.64%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart_bsd/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 60        | 53.1%   |
| WiFi     | 52        | 46.02%  |
| Modem    | 1         | 0.88%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart_bsd/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 43        | 58.11%  |
| WiFi     | 31        | 41.89%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart_bsd/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 40        | 57.97%  |
| 1     | 28        | 40.58%  |
| 0     | 1         | 1.45%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart_bsd/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 63        | 91.3%   |
| Yes  | 6         | 8.7%    |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart_bsd/bt_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Intel                   | 22        | 55%     |
| Apple                   | 5         | 12.5%   |
| Realtek Semiconductor   | 2         | 5%      |
| Lite-On Technology      | 2         | 5%      |
| IMC Networks            | 2         | 5%      |
| Cambridge Silicon Radio | 2         | 5%      |
| Hewlett-Packard         | 1         | 2.5%    |
| Broadcom                | 1         | 2.5%    |
| Bluetooth Device        | 1         | 2.5%    |
| ASUSTek Computer        | 1         | 2.5%    |
| Alps Electric           | 1         | 2.5%    |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart_bsd/bt_model.svg)


| Model                                                    | Computers | Percent |
|----------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                       | 13        | 30.95%  |
| Intel AX200 Bluetooth                                    | 4         | 9.52%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                     | 3         | 7.14%   |
| Intel Wireless-AC 3168 Bluetooth                         | 2         | 4.76%   |
| Intel AX201 Bluetooth                                    | 2         | 4.76%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)      | 2         | 4.76%   |
| Apple Built-in iSight (no firmware loaded)               | 2         | 4.76%   |
| Realtek  Bluetooth 4.2 Adapter                           | 1         | 2.38%   |
| Realtek Dell Wireless 1801 Bluetooth 4.0 LE              | 1         | 2.38%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth               | 1         | 2.38%   |
| Lite-On Atheros AR3012 Bluetooth                         | 1         | 2.38%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)           | 1         | 2.38%   |
| IMC Networks Realtek Bluetooth Adapter                   | 1         | 2.38%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter        | 1         | 2.38%   |
| HP Broadcom 2070 Bluetooth Combo                         | 1         | 2.38%   |
| Broadcom BCM2045B (BDC-2.1)                              | 1         | 2.38%   |
| Bluetooth Device Silicon Wave Bluetooth Wireless Adapter | 1         | 2.38%   |
| ASUS BT-253 Bluetooth Adapter                            | 1         | 2.38%   |
| Apple Bluetooth Host Controller                          | 1         | 2.38%   |
| Apple Apple Broadcom Built-in Bluetooth                  | 1         | 2.38%   |
| Alps Electric BCM2046 Bluetooth Device                   | 1         | 2.38%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart_bsd/snd_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Intel               | 54        | 65.06%  |
| AMD                 | 12        | 14.46%  |
| Nvidia              | 10        | 12.05%  |
| C-Media Electronics | 3         | 3.61%   |
| Yamaha              | 1         | 1.2%    |
| XMOS                | 1         | 1.2%    |
| GN Netcom           | 1         | 1.2%    |
| Creative Technology | 1         | 1.2%    |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart_bsd/snd_model.svg)


| Model                                                                                             | Computers | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                                                   | 8         | 8.08%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 7         | 7.07%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 6         | 6.06%   |
| Intel Broadwell-U Audio Controller                                                                | 6         | 6.06%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 6         | 6.06%   |
| Nvidia MCP79 High Definition Audio                                                                | 4         | 4.04%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 4         | 4.04%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 3         | 3.03%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 3         | 3.03%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 3         | 3.03%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 3         | 3.03%   |
| Nvidia TU116 High Definition Audio Controller                                                     | 2         | 2.02%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 2         | 2.02%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 2         | 2.02%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 2         | 2.02%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 2         | 2.02%   |
| Intel 8 Series HD Audio Controller                                                                | 2         | 2.02%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 2         | 2.02%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 2         | 2.02%   |
| AMD Starship/Matisse HD Audio Controller                                                          | 2         | 2.02%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 2         | 2.02%   |
| Yamaha Steinberg UR22mkII                                                                         | 1         | 1.01%   |
| XMOS iFi (by AMR) HD USB Audio                                                                    | 1         | 1.01%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 1         | 1.01%   |
| Nvidia High Definition Audio Controller                                                           | 1         | 1.01%   |
| Nvidia GM206 High Definition Audio Controller                                                     | 1         | 1.01%   |
| Nvidia GK104 HDMI Audio Controller                                                                | 1         | 1.01%   |
| Intel Tiger Lake-H HD Audio Controller                                                            | 1         | 1.01%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 1         | 1.01%   |
| Intel C610/X99 series chipset HD Audio Controller                                                 | 1         | 1.01%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 1         | 1.01%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                                  | 1         | 1.01%   |
| Intel 200 Series PCH HD Audio                                                                     | 1         | 1.01%   |
| GN Netcom Jabra EVOLVE 20                                                                         | 1         | 1.01%   |
| Creative Technology Sound BlasterX G1                                                             | 1         | 1.01%   |
| C-Media Electronics CMI8788 [Oxygen HD Audio]                                                     | 1         | 1.01%   |
| C-Media Electronics Cmedia Audio                                                                  | 1         | 1.01%   |
| C-Media Electronics Audio Adapter (Unitek Y-247A)                                                 | 1         | 1.01%   |
| AMD Tobago HDMI Audio [Radeon R7 360 / R9 360 OEM]                                                | 1         | 1.01%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 1         | 1.01%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart_bsd/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| SK hynix            | 17        | 20.48%  |
| Unknown             | 14        | 16.87%  |
| Samsung Electronics | 12        | 14.46%  |
| Kingston            | 11        | 13.25%  |
| Micron Technology   | 8         | 9.64%   |
| Crucial             | 5         | 6.02%   |
| Unknown             | 3         | 3.61%   |
| Smart               | 2         | 2.41%   |
| Ramaxel Technology  | 2         | 2.41%   |
| Nanya Technology    | 2         | 2.41%   |
| Transcend           | 1         | 1.2%    |
| Smart Brazil        | 1         | 1.2%    |
| Patriot             | 1         | 1.2%    |
| GeIL                | 1         | 1.2%    |
| G.Skill             | 1         | 1.2%    |
| Elpida              | 1         | 1.2%    |
| Corsair             | 1         | 1.2%    |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart_bsd/memory_model.svg)


| Model                                                  | Computers | Percent |
|--------------------------------------------------------|-----------|---------|
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s | 3         | 3.37%   |
| Unknown                                                | 3         | 3.37%   |
| Unknown RAM Module 1GB DIMM SDRAM                      | 2         | 2.25%   |
| SK hynix RAM HMT41GU6BFR8A-PB 8GB DIMM DDR3 1600MT/s   | 2         | 2.25%   |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2400MT/s | 2         | 2.25%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s  | 2         | 2.25%   |
| Unknown RAM Module 4GB SODIMM DDR3 1333MT/s            | 1         | 1.12%   |
| Unknown RAM Module 4GB DIMM SDRAM                      | 1         | 1.12%   |
| Unknown RAM Module 4GB DIMM DDR3 1067MT/s              | 1         | 1.12%   |
| Unknown RAM Module 2GB SODIMM DDR3 1333MT/s            | 1         | 1.12%   |
| Unknown RAM Module 2GB SODIMM DDR3 1067MT/s            | 1         | 1.12%   |
| Unknown RAM Module 2GB SODIMM DDR3                     | 1         | 1.12%   |
| Unknown RAM Module 2GB SODIMM DDR2 800MT/s             | 1         | 1.12%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s             | 1         | 1.12%   |
| Unknown RAM Module 2GB SODIMM DDR2                     | 1         | 1.12%   |
| Unknown RAM Module 2GB DIMM SDRAM                      | 1         | 1.12%   |
| Unknown RAM Module 2GB DIMM DDR3 1066MT/s              | 1         | 1.12%   |
| Unknown RAM Module 2GB DIMM DDR2 800MT/s               | 1         | 1.12%   |
| Unknown RAM Module 2GB DIMM DDR2                       | 1         | 1.12%   |
| Unknown RAM Module 1GB SODIMM DDR2 800MT/s             | 1         | 1.12%   |
| Transcend RAM TS256MSK64V3N 2GB SODIMM DDR3 1333MT/s   | 1         | 1.12%   |
| Smart RAM SH564568FH8NZPHSCR 2GB SODIMM DDR3 1334MT/s  | 1         | 1.12%   |
| Smart RAM SH564568FH8NWPHSFR 2GB SODIMM DDR3 1333MT/s  | 1         | 1.12%   |
| Smart RAM SH564128FJ8NWRNSQR 4GB SODIMM DDR3 1600MT/s  | 1         | 1.12%   |
| Smart Brazil RAM Module 4GB Row Of Chips DDR4 2400MT/s | 1         | 1.12%   |
| SK hynix RAM Module 4GB SODIMM DDR4 2400MT/s           | 1         | 1.12%   |
| SK hynix RAM Module 2GB SODIMM DDR3 1067MT/s           | 1         | 1.12%   |
| SK hynix RAM HMT451U6AFR8C-PB 4GB DIMM DDR3 1600MT/s   | 1         | 1.12%   |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s | 1         | 1.12%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s | 1         | 1.12%   |
| SK hynix RAM HMT351S6EFR8C-PB 4GB SODIMM DDR3 1600MT/s | 1         | 1.12%   |
| SK hynix RAM HMT351S6EFR8A-PB 4GB SODIMM DDR3 1600MT/s | 1         | 1.12%   |
| SK hynix RAM HMAA1GU6CJR6N-XN 8GB DIMM DDR4 3200MT/s   | 1         | 1.12%   |
| SK hynix RAM HMA851S6AFR6N-TF 4GB SODIMM DDR4 2133MT/s | 1         | 1.12%   |
| SK hynix RAM HMA81GU6DJR8N-XN 8GB DIMM DDR4 3200MT/s   | 1         | 1.12%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2400MT/s | 1         | 1.12%   |
| Samsung RAM Module 8GB SODIMM DDR4 2400MT/s            | 1         | 1.12%   |
| Samsung RAM Module 8GB SODIMM DDR4 2133MT/s            | 1         | 1.12%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s  | 1         | 1.12%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s  | 1         | 1.12%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart_bsd/memory_kind.svg)


| Kind  | Computers | Percent |
|-------|-----------|---------|
| DDR3  | 32        | 46.38%  |
| DDR4  | 26        | 37.68%  |
| DDR2  | 8         | 11.59%  |
| SDRAM | 3         | 4.35%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart_bsd/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 44        | 63.77%  |
| DIMM         | 22        | 31.88%  |
| Row Of Chips | 3         | 4.35%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart_bsd/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 4096  | 31        | 39.74%  |
| 2048  | 19        | 24.36%  |
| 8192  | 18        | 23.08%  |
| 16384 | 7         | 8.97%   |
| 1024  | 3         | 3.85%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart_bsd/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 19        | 25.33%  |
| 2400    | 10        | 13.33%  |
| 3200    | 7         | 9.33%   |
| 2667    | 7         | 9.33%   |
| 1333    | 7         | 9.33%   |
| Unknown | 6         | 8%      |
| 2133    | 5         | 6.67%   |
| 800     | 4         | 5.33%   |
| 1067    | 3         | 4%      |
| 1334    | 2         | 2.67%   |
| 667     | 2         | 2.67%   |
| 2666    | 1         | 1.33%   |
| 1066    | 1         | 1.33%   |
| 333     | 1         | 1.33%   |

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


| Vendor                        | Computers | Percent |
|-------------------------------|-----------|---------|
| Chicony Electronics           | 10        | 27.78%  |
| Microdia                      | 5         | 13.89%  |
| Sunplus Innovation Technology | 4         | 11.11%  |
| IMC Networks                  | 4         | 11.11%  |
| Realtek Semiconductor         | 3         | 8.33%   |
| Syntek                        | 2         | 5.56%   |
| Z-Star Microelectronics       | 1         | 2.78%   |
| Suyin                         | 1         | 2.78%   |
| Luxvisions Innotech Limited   | 1         | 2.78%   |
| Logitech                      | 1         | 2.78%   |
| Lite-On Technology            | 1         | 2.78%   |
| Arkmicro Technologies         | 1         | 2.78%   |
| Alcor Micro                   | 1         | 2.78%   |
| Acer                          | 1         | 2.78%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart_bsd/camera_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Chicony HD Webcam                             | 3         | 8.33%   |
| Sunplus Integrated_Webcam_HD                  | 2         | 5.56%   |
| Realtek Realtek USB2.0 PC Camera              | 2         | 5.56%   |
| IMC Networks USB2.0 UVC VGA WebCam            | 2         | 5.56%   |
| Chicony integrated camera                     | 2         | 5.56%   |
| Z-Star Venus USB2.0 Camera                    | 1         | 2.78%   |
| Syntek Syntek 0.3MPixel USB 2.0 UVC PC Camera | 1         | 2.78%   |
| Syntek Integrated Camera                      | 1         | 2.78%   |
| Suyin Integrated_Webcam_HD                    | 1         | 2.78%   |
| Sunplus XiaoMi USB 2.0 Webcam                 | 1         | 2.78%   |
| Sunplus HP HD Webcam [Fixed]                  | 1         | 2.78%   |
| Realtek Integrated_Webcam_HD                  | 1         | 2.78%   |
| Microdia Webcam                               | 1         | 2.78%   |
| Microdia Laptop_Integrated_Webcam_HD          | 1         | 2.78%   |
| Microdia Laptop_Integrated_Webcam_2M          | 1         | 2.78%   |
| Microdia Integrated_Webcam_HD                 | 1         | 2.78%   |
| Microdia Integrated Webcam HD                 | 1         | 2.78%   |
| Luxvisions Innotech Limited Integrated Camera | 1         | 2.78%   |
| Logitech HD Pro Webcam C920                   | 1         | 2.78%   |
| Lite-On HP HD Webcam [Fixed]                  | 1         | 2.78%   |
| IMC Networks USB2.0 VGA UVC WebCam            | 1         | 2.78%   |
| IMC Networks HD Camera                        | 1         | 2.78%   |
| Chicony XiaoMi USB 2.0 Webcam                 | 1         | 2.78%   |
| Chicony VGA WebCam                            | 1         | 2.78%   |
| Chicony TOSHIBA Web Camera - HD               | 1         | 2.78%   |
| Chicony Lenovo EasyCamera                     | 1         | 2.78%   |
| Chicony 1.3M UVC Webcam                       | 1         | 2.78%   |
| Arkmicro Webcam Carrefour                     | 1         | 2.78%   |
| Alcor Micro Acer Integrated Webcam            | 1         | 2.78%   |
| Acer Integrated Camera                        | 1         | 2.78%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart_bsd/fingerprint_vendor.svg)


| Vendor           | Computers | Percent |
|------------------|-----------|---------|
| Validity Sensors | 3         | 60%     |
| Broadcom         | 1         | 20%     |
| AuthenTec        | 1         | 20%     |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart_bsd/fingerprint_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Validity Sensors VFS495 Fingerprint Reader                                   | 2         | 40%     |
| Validity Sensors Synaptics WBDI                                              | 1         | 20%     |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 1         | 20%     |
| AuthenTec AES1600                                                            | 1         | 20%     |

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


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 26        | 37.68%  |
| 0     | 17        | 24.64%  |
| 2     | 16        | 23.19%  |
| 3     | 8         | 11.59%  |
| 5     | 1         | 1.45%   |
| 4     | 1         | 1.45%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart_bsd/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Communication controller | 39        | 44.32%  |
| Bluetooth                | 22        | 25%     |
| Net/wireless             | 11        | 12.5%   |
| Card reader              | 7         | 7.95%   |
| Fingerprint reader       | 5         | 5.68%   |
| Network                  | 2         | 2.27%   |
| Storage                  | 1         | 1.14%   |
| Sound                    | 1         | 1.14%   |

