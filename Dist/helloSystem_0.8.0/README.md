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

Total: 91

| Vendor        | Model                       | Form-Factor | Probe                                                     | Date         |
|---------------|-----------------------------|-------------|-----------------------------------------------------------|--------------|
| HP            | Pavilion g6                 | Notebook    | [c4e84b8104](https://bsd-hardware.info/?probe=c4e84b8104) | Oct 30, 2022 |
| Lenovo        | 3106 SDK0J40705 WIN 3425... | Desktop     | [d20bfb6d64](https://bsd-hardware.info/?probe=d20bfb6d64) | Oct 30, 2022 |
| HP            | 843B                        | Desktop     | [d7d572f9ad](https://bsd-hardware.info/?probe=d7d572f9ad) | Oct 29, 2022 |
| Intel         | NUC8BEB J72688-306          | Mini pc     | [17f444775b](https://bsd-hardware.info/?probe=17f444775b) | Oct 28, 2022 |
| HP            | 843B                        | Desktop     | [9ea2590610](https://bsd-hardware.info/?probe=9ea2590610) | Oct 23, 2022 |
| Google        | Edgar                       | Notebook    | [318a750368](https://bsd-hardware.info/?probe=318a750368) | Oct 22, 2022 |
| MSI           | B450M PRO-VDH PLUS          | Desktop     | [54e4202bc7](https://bsd-hardware.info/?probe=54e4202bc7) | Oct 21, 2022 |
| MSI           | PS63 Modern 8M              | Notebook    | [949e472db5](https://bsd-hardware.info/?probe=949e472db5) | Oct 19, 2022 |
| HP            | 86FC MVB                    | Desktop     | [56453b00c8](https://bsd-hardware.info/?probe=56453b00c8) | Oct 08, 2022 |
| HP            | 86FC MVB                    | Desktop     | [c542b16d75](https://bsd-hardware.info/?probe=c542b16d75) | Oct 08, 2022 |
| TUXEDO        | Aura 15 Gen1                | Notebook    | [a49ac2701d](https://bsd-hardware.info/?probe=a49ac2701d) | Oct 02, 2022 |
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

![Arch](./All/images/pie_chart_bsd/os_arch.svg)


| Name  | Computers | Percent |
|-------|-----------|---------|
| amd64 | 78        | 100%    |

DE
--

Desktop Environment

![DE](./All/images/pie_chart_bsd/os_de.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| helloDesktop | 75        | 96.15%  |
| GNOME        | 2         | 2.56%   |
| Cinnamon     | 1         | 1.28%   |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart_bsd/os_display_server.svg)


| Name | Computers | Percent |
|------|-----------|---------|
| X11  | 78        | 100%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart_bsd/os_display_manager.svg)


| Name | Computers | Percent |
|------|-----------|---------|
| SLiM | 77        | 98.72%  |
| GDM  | 1         | 1.28%   |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart_bsd/os_lang.svg)


| Lang  | Computers | Percent |
|-------|-----------|---------|
| en_US | 75        | 96.15%  |
| ru_RU | 1         | 1.28%   |
| es_ES | 1         | 1.28%   |
| de_DE | 1         | 1.28%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart_bsd/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 77        | 98.72%  |
| BIOS | 1         | 1.28%   |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart_bsd/os_filesystem.svg)


| Type   | Computers | Percent |
|--------|-----------|---------|
| Cd9660 | 51        | 64.56%  |
| Zfs    | 28        | 35.44%  |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart_bsd/os_part_scheme.svg)


| Type | Computers | Percent |
|------|-----------|---------|
| GPT  | 77        | 98.72%  |
| MBR  | 1         | 1.28%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart_bsd/node_vendor.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| Dell             | 12        | 15.38%  |
| Lenovo           | 11        | 14.1%   |
| Hewlett-Packard  | 11        | 14.1%   |
| ASUSTek Computer | 8         | 10.26%  |
| MSI              | 4         | 5.13%   |
| Intel            | 4         | 5.13%   |
| Apple            | 4         | 5.13%   |
| ASRock           | 3         | 3.85%   |
| Acer             | 3         | 3.85%   |
| TUXEDO           | 2         | 2.56%   |
| Timi             | 2         | 2.56%   |
| Sony             | 2         | 2.56%   |
| Pegatron         | 2         | 2.56%   |
| Toshiba          | 1         | 1.28%   |
| PCSTICK          | 1         | 1.28%   |
| Packard Bell     | 1         | 1.28%   |
| MACHINIST        | 1         | 1.28%   |
| Kraftway         | 1         | 1.28%   |
| HUAWEI           | 1         | 1.28%   |
| Google           | 1         | 1.28%   |
| Gateway          | 1         | 1.28%   |
| Biostar          | 1         | 1.28%   |
| AMD              | 1         | 1.28%   |

Model
-----

Motherboard model

![Model](./All/images/pie_chart_bsd/node_model.svg)


| Name                                  | Computers | Percent |
|---------------------------------------|-----------|---------|
| MSI MS-7A38                           | 2         | 2.56%   |
| HP 250 G6 Notebook PC                 | 2         | 2.56%   |
| Apple MacBook5,2                      | 2         | 2.56%   |
| Unknown                               | 2         | 2.56%   |
| TUXEDO Pulse 14 Gen1                  | 1         | 1.28%   |
| TUXEDO Aura 15 Gen1                   | 1         | 1.28%   |
| Toshiba Satellite S55t-B              | 1         | 1.28%   |
| Timi TM1701                           | 1         | 1.28%   |
| Timi RedmiBook Pro 15                 | 1         | 1.28%   |
| Sony VPCEB1J1E                        | 1         | 1.28%   |
| Sony VGN-AW21S_B                      | 1         | 1.28%   |
| Pegatron IPPPV-D3G                    | 1         | 1.28%   |
| Pegatron IPM41-D3                     | 1         | 1.28%   |
| Packard Bell EasyNote_MX52-B-071      | 1         | 1.28%   |
| MSI PS63 Modern 8M                    | 1         | 1.28%   |
| MSI MS-7C37                           | 1         | 1.28%   |
| MACHINIST X99-k9 V2.0                 | 1         | 1.28%   |
| Lenovo ThinkPad X270 W10DG 20K5S0BB00 | 1         | 1.28%   |
| Lenovo ThinkPad X250 20CLS23500       | 1         | 1.28%   |
| Lenovo ThinkPad X250 20CLS1WP01       | 1         | 1.28%   |
| Lenovo ThinkPad T440 20B7A0B7MS       | 1         | 1.28%   |
| Lenovo ThinkPad T420 4178A72          | 1         | 1.28%   |
| Lenovo ThinkCentre M93p 10AAA0WGUK    | 1         | 1.28%   |
| Lenovo ThinkCentre M910s 10MK0039US   | 1         | 1.28%   |
| Lenovo ThinkCentre M700 10GS          | 1         | 1.28%   |
| Lenovo Legion 5 15ARH05 82B5          | 1         | 1.28%   |
| Lenovo IdeaPad 3 15IGL05 82BU         | 1         | 1.28%   |
| Lenovo G480 20149                     | 1         | 1.28%   |
| Kraftway KW10T                        | 1         | 1.28%   |
| Intel NUC8i7BEK                       | 1         | 1.28%   |
| Intel NUC8i7BEH                       | 1         | 1.28%   |
| Intel MAHOBAY                         | 1         | 1.28%   |
| Intel DN2800MT AAG23738-600           | 1         | 1.28%   |
| HUAWEI BOD-WXX9                       | 1         | 1.28%   |
| HP Slim Desktop S01-aF1xxx            | 1         | 1.28%   |
| HP Pavilion g6                        | 1         | 1.28%   |
| HP Pavilion Desktop 590-p0xxx         | 1         | 1.28%   |
| HP OMEN by Laptop                     | 1         | 1.28%   |
| HP EliteDesk 800 G1 SFF               | 1         | 1.28%   |
| HP EliteBook 850 G3                   | 1         | 1.28%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart_bsd/node_model_family.svg)


| Name                  | Computers | Percent |
|-----------------------|-----------|---------|
| Lenovo ThinkPad       | 5         | 6.41%   |
| Dell Latitude         | 5         | 6.41%   |
| Dell Inspiron         | 4         | 5.13%   |
| Lenovo ThinkCentre    | 3         | 3.85%   |
| Acer Aspire           | 3         | 3.85%   |
| MSI MS-7A38           | 2         | 2.56%   |
| HP Pavilion           | 2         | 2.56%   |
| HP EliteBook          | 2         | 2.56%   |
| HP 250                | 2         | 2.56%   |
| Apple MacBook5        | 2         | 2.56%   |
| Unknown               | 2         | 2.56%   |
| TUXEDO Pulse          | 1         | 1.28%   |
| TUXEDO Aura           | 1         | 1.28%   |
| Toshiba Satellite     | 1         | 1.28%   |
| Timi TM1701           | 1         | 1.28%   |
| Timi RedmiBook        | 1         | 1.28%   |
| Sony VPCEB1J1E        | 1         | 1.28%   |
| Sony VGN-AW21S        | 1         | 1.28%   |
| Pegatron IPPPV-D3G    | 1         | 1.28%   |
| Pegatron IPM41-D3     | 1         | 1.28%   |
| Packard Bell EasyNote | 1         | 1.28%   |
| MSI PS63              | 1         | 1.28%   |
| MSI MS-7C37           | 1         | 1.28%   |
| MACHINIST X99-k9      | 1         | 1.28%   |
| Lenovo Legion         | 1         | 1.28%   |
| Lenovo IdeaPad        | 1         | 1.28%   |
| Lenovo G480           | 1         | 1.28%   |
| Kraftway KW10T        | 1         | 1.28%   |
| Intel NUC8i7BEK       | 1         | 1.28%   |
| Intel NUC8i7BEH       | 1         | 1.28%   |
| Intel MAHOBAY         | 1         | 1.28%   |
| Intel DN2800MT        | 1         | 1.28%   |
| HUAWEI BOD-WXX9       | 1         | 1.28%   |
| HP Slim               | 1         | 1.28%   |
| HP OMEN               | 1         | 1.28%   |
| HP EliteDesk          | 1         | 1.28%   |
| HP Desktop            | 1         | 1.28%   |
| Google Edgar          | 1         | 1.28%   |
| Gateway NE56R         | 1         | 1.28%   |
| Dell Studio           | 1         | 1.28%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart_bsd/node_year.svg)


| Year | Computers | Percent |
|------|-----------|---------|
| 2020 | 10        | 12.82%  |
| 2021 | 8         | 10.26%  |
| 2019 | 8         | 10.26%  |
| 2009 | 7         | 8.97%   |
| 2015 | 6         | 7.69%   |
| 2018 | 5         | 6.41%   |
| 2014 | 5         | 6.41%   |
| 2012 | 5         | 6.41%   |
| 2010 | 5         | 6.41%   |
| 2022 | 4         | 5.13%   |
| 2016 | 4         | 5.13%   |
| 2011 | 4         | 5.13%   |
| 2013 | 3         | 3.85%   |
| 2017 | 2         | 2.56%   |
| 2008 | 1         | 1.28%   |
| 2007 | 1         | 1.28%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart_bsd/node_formfactor.svg)


| Name       | Computers | Percent |
|------------|-----------|---------|
| Notebook   | 47        | 60.26%  |
| Desktop    | 28        | 35.9%   |
| Mini pc    | 2         | 2.56%   |
| All in one | 1         | 1.28%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart_bsd/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 77        | 98.72%  |
| Yes  | 1         | 1.28%   |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart_bsd/node_ram_total.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| 4.01-8.0   | 24        | 30.77%  |
| 16.01-24.0 | 22        | 28.21%  |
| 8.01-16.0  | 22        | 28.21%  |
| 2.01-3.0   | 6         | 7.69%   |
| 32.01-64.0 | 3         | 3.85%   |
| 3.01-4.0   | 1         | 1.28%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart_bsd/node_ram_used.svg)


| Used GB  | Computers | Percent |
|----------|-----------|---------|
| 0.01-0.5 | 44        | 56.41%  |
| 0.51-1.0 | 23        | 29.49%  |
| 1.01-2.0 | 9         | 11.54%  |
| 4.01-8.0 | 1         | 1.28%   |
| 2.01-3.0 | 1         | 1.28%   |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart_bsd/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 51        | 64.56%  |
| 2      | 18        | 22.78%  |
| 0      | 4         | 5.06%   |
| 3      | 3         | 3.8%    |
| 6      | 1         | 1.27%   |
| 5      | 1         | 1.27%   |
| 4      | 1         | 1.27%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart_bsd/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 55        | 70.51%  |
| Yes       | 23        | 29.49%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart_bsd/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 67        | 85.9%   |
| No        | 11        | 14.1%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart_bsd/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 59        | 74.68%  |
| No        | 20        | 25.32%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart_bsd/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 43        | 55.13%  |
| No        | 35        | 44.87%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart_bsd/node_location.svg)


| Country      | Computers | Percent |
|--------------|-----------|---------|
| Russia       | 10        | 12.82%  |
| USA          | 9         | 11.54%  |
| Germany      | 8         | 10.26%  |
| Brazil       | 6         | 7.69%   |
| China        | 5         | 6.41%   |
| Spain        | 4         | 5.13%   |
| Ukraine      | 3         | 3.85%   |
| UK           | 3         | 3.85%   |
| Mexico       | 3         | 3.85%   |
| France       | 3         | 3.85%   |
| Canada       | 3         | 3.85%   |
| Poland       | 2         | 2.56%   |
| Norway       | 2         | 2.56%   |
| Hungary      | 2         | 2.56%   |
| Venezuela    | 1         | 1.28%   |
| UAE          | 1         | 1.28%   |
| Taiwan       | 1         | 1.28%   |
| South Africa | 1         | 1.28%   |
| Slovenia     | 1         | 1.28%   |
| Slovakia     | 1         | 1.28%   |
| Serbia       | 1         | 1.28%   |
| Romania      | 1         | 1.28%   |
| Peru         | 1         | 1.28%   |
| Italy        | 1         | 1.28%   |
| India        | 1         | 1.28%   |
| Georgia      | 1         | 1.28%   |
| Belarus      | 1         | 1.28%   |
| Argentina    | 1         | 1.28%   |
| Albania      | 1         | 1.28%   |

City
----

Geographic location (city)

![City](./All/images/pie_chart_bsd/node_city.svg)


| City                 | Computers | Percent |
|----------------------|-----------|---------|
| Moscow               | 3         | 3.8%    |
| Volgograd            | 2         | 2.53%   |
| Temple               | 2         | 2.53%   |
| Munich               | 2         | 2.53%   |
| LogroÃ±o           | 2         | 2.53%   |
| Zhengzhou            | 1         | 1.27%   |
| Yunlin               | 1         | 1.27%   |
| Weifang              | 1         | 1.27%   |
| Warendorf            | 1         | 1.27%   |
| Voronezh             | 1         | 1.27%   |
| Vladivostok          | 1         | 1.27%   |
| Vancouver            | 1         | 1.27%   |
| Ufa                  | 1         | 1.27%   |
| Szeged               | 1         | 1.27%   |
| Surrey               | 1         | 1.27%   |
| Southminster         | 1         | 1.27%   |
| San Carlos del Zulia | 1         | 1.27%   |
| Salisbury            | 1         | 1.27%   |
| Rio das Ostras       | 1         | 1.27%   |
| Rho                  | 1         | 1.27%   |
| Reinsvoll            | 1         | 1.27%   |
| Redondela            | 1         | 1.27%   |
| Perm                 | 1         | 1.27%   |
| Ottawa               | 1         | 1.27%   |
| Orizaba              | 1         | 1.27%   |
| Odessa               | 1         | 1.27%   |
| Oakdale              | 1         | 1.27%   |
| Nesttun              | 1         | 1.27%   |
| Nanticoke            | 1         | 1.27%   |
| Monterrey            | 1         | 1.27%   |
| Mirepeix             | 1         | 1.27%   |
| Minsk                | 1         | 1.27%   |
| Mexico City          | 1         | 1.27%   |
| Mendoza              | 1         | 1.27%   |
| Medford              | 1         | 1.27%   |
| Maracanau            | 1         | 1.27%   |
| Londrina             | 1         | 1.27%   |
| Linyi                | 1         | 1.27%   |
| Lima                 | 1         | 1.27%   |
| Lanzhou              | 1         | 1.27%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart_bsd/drive_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 18        | 21     | 17.48%  |
| Samsung Electronics | 15        | 17     | 14.56%  |
| WDC                 | 12        | 14     | 11.65%  |
| Kingston            | 9         | 9      | 8.74%   |
| Toshiba             | 8         | 8      | 7.77%   |
| Hitachi             | 8         | 8      | 7.77%   |
| Intel               | 5         | 5      | 4.85%   |
| SPCC                | 2         | 2      | 1.94%   |
| SK hynix            | 2         | 2      | 1.94%   |
| SanDisk             | 2         | 3      | 1.94%   |
| OCZ                 | 2         | 2      | 1.94%   |
| KingSpec            | 2         | 2      | 1.94%   |
| Fujitsu             | 2         | 2      | 1.94%   |
| A-DATA Technology   | 2         | 2      | 1.94%   |
| Transcend           | 1         | 1      | 0.97%   |
| SSSTC               | 1         | 1      | 0.97%   |
| PNY                 | 1         | 1      | 0.97%   |
| Patriot             | 1         | 1      | 0.97%   |
| Lexar               | 1         | 2      | 0.97%   |
| LDLC                | 1         | 1      | 0.97%   |
| KIOXIA              | 1         | 1      | 0.97%   |
| Intenso             | 1         | 1      | 0.97%   |
| Hewlett-Packard     | 1         | 1      | 0.97%   |
| GOODRAM             | 1         | 1      | 0.97%   |
| Gigabyte Technology | 1         | 1      | 0.97%   |
| FORESEE             | 1         | 1      | 0.97%   |
| Crucial             | 1         | 1      | 0.97%   |
| Corsair             | 1         | 1      | 0.97%   |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart_bsd/drive_model.svg)


| Model                                     | Computers | Percent |
|-------------------------------------------|-----------|---------|
| Seagate ST1000LM035-1RK172 1TB            | 3         | 2.7%    |
| Toshiba MQ01ABF050 500GB                  | 2         | 1.8%    |
| Toshiba MQ01ABD050 500GB                  | 2         | 1.8%    |
| Seagate ST1000LM024 HN-M101MBB 1TB        | 2         | 1.8%    |
| Samsung SSD 860 PRO 512GB                 | 2         | 1.8%    |
| Kingston SV300S37A120G 120GB              | 2         | 1.8%    |
| Kingston SA400S37120G 120GB               | 2         | 1.8%    |
| WDC WDS500G2X0C-00L350 500GB              | 1         | 0.9%    |
| WDC WDS500G2B0A 500GB                     | 1         | 0.9%    |
| WDC WDS500G1B0C-00S6U0 500GB              | 1         | 0.9%    |
| WDC WDS240G2G0B-00EPW0 240GB              | 1         | 0.9%    |
| WDC WDBNCE5000PNC 500GB                   | 1         | 0.9%    |
| WDC WD5000LPCX-60VHAT0 500GB              | 1         | 0.9%    |
| WDC WD5000AZLX-60K2TA1 500GB              | 1         | 0.9%    |
| WDC WD5000AVVS-63H0B1 500GB               | 1         | 0.9%    |
| WDC WD40NPZZ-00A9JT0 4TB                  | 1         | 0.9%    |
| WDC WD3003FZEX-00Z4SA0 3TB                | 1         | 0.9%    |
| WDC WD20EFRX-68EUZN0 2TB                  | 1         | 0.9%    |
| WDC WD10JPVX-75JC3T0 1TB                  | 1         | 0.9%    |
| WDC WD10JPVX-22JC3T0 1TB                  | 1         | 0.9%    |
| WDC PC SN530 SDBPNPZ-512G-1027 512GB      | 1         | 0.9%    |
| Transcend TS120GMTS420S 120GB             | 1         | 0.9%    |
| Toshiba TR200 480GB                       | 1         | 0.9%    |
| Toshiba MQ01ABD100 1TB                    | 1         | 0.9%    |
| Toshiba MK8034GSX 80GB                    | 1         | 0.9%    |
| Toshiba DT01ACA100 1TB                    | 1         | 0.9%    |
| SSSTC CL1-4D128 128GB                     | 1         | 0.9%    |
| SPCC Solid State Disk 56GB                | 1         | 0.9%    |
| SPCC Solid State Disk 512GB               | 1         | 0.9%    |
| SK hynix SKHynix_HFM512GDHTNI-87A0B 512GB | 1         | 0.9%    |
| SK hynix BC711 NVMe 256GB                 | 1         | 0.9%    |
| Seagate ST9500420AS 500GB                 | 1         | 0.9%    |
| Seagate ST9160821AS 160GB                 | 1         | 0.9%    |
| Seagate ST9120821AS 118GB                 | 1         | 0.9%    |
| Seagate ST500LT012-9WS142 500GB           | 1         | 0.9%    |
| Seagate ST500LT012-1DG142 500GB           | 1         | 0.9%    |
| Seagate ST4000DM004-2CV104 4TB            | 1         | 0.9%    |
| Seagate ST3250310AS 250GB                 | 1         | 0.9%    |
| Seagate ST320LT014-9YK142 320GB           | 1         | 0.9%    |
| Seagate ST3160811AS 160GB                 | 1         | 0.9%    |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart_bsd/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 18        | 21     | 40%     |
| WDC                 | 8         | 8      | 17.78%  |
| Hitachi             | 8         | 8      | 17.78%  |
| Toshiba             | 7         | 7      | 15.56%  |
| Samsung Electronics | 2         | 2      | 4.44%   |
| Hewlett-Packard     | 1         | 1      | 2.22%   |
| Fujitsu             | 1         | 1      | 2.22%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart_bsd/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 10        | 10     | 23.26%  |
| Kingston            | 7         | 7      | 16.28%  |
| Intel               | 4         | 4      | 9.3%    |
| WDC                 | 3         | 3      | 6.98%   |
| SPCC                | 2         | 2      | 4.65%   |
| SanDisk             | 2         | 3      | 4.65%   |
| OCZ                 | 2         | 2      | 4.65%   |
| KingSpec            | 2         | 2      | 4.65%   |
| Transcend           | 1         | 1      | 2.33%   |
| Toshiba             | 1         | 1      | 2.33%   |
| PNY                 | 1         | 1      | 2.33%   |
| Patriot             | 1         | 1      | 2.33%   |
| Lexar               | 1         | 1      | 2.33%   |
| Intenso             | 1         | 1      | 2.33%   |
| GOODRAM             | 1         | 1      | 2.33%   |
| Gigabyte Technology | 1         | 1      | 2.33%   |
| Fujitsu             | 1         | 1      | 2.33%   |
| FORESEE             | 1         | 1      | 2.33%   |
| A-DATA Technology   | 1         | 1      | 2.33%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart_bsd/drive_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SSD  | 38        | 44     | 40.86%  |
| HDD  | 36        | 48     | 38.71%  |
| NVMe | 19        | 20     | 20.43%  |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart_bsd/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 66        | 92     | 77.65%  |
| NVMe | 19        | 20     | 22.35%  |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart_bsd/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 52        | 68     | 71.23%  |
| 0.51-1.0   | 14        | 16     | 19.18%  |
| 1.01-2.0   | 4         | 4      | 5.48%   |
| 3.01-4.0   | 2         | 2      | 2.74%   |
| 2.01-3.0   | 1         | 2      | 1.37%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart_bsd/drive_space_total.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| 1-20       | 44        | 56.41%  |
| 101-250    | 13        | 16.67%  |
| 251-500    | 12        | 15.38%  |
| 501-1000   | 4         | 5.13%   |
| 1001-2000  | 2         | 2.56%   |
| 21-50      | 1         | 1.28%   |
| 51-100     | 1         | 1.28%   |
| Unknown    | 1         | 1.28%   |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart_bsd/drive_space_used.svg)


| Used GB  | Computers | Percent |
|----------|-----------|---------|
| 1-20     | 73        | 93.59%  |
| 101-250  | 2         | 2.56%   |
| 501-1000 | 1         | 1.28%   |
| 51-100   | 1         | 1.28%   |
| Unknown  | 1         | 1.28%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./All/images/pie_chart_bsd/drive_malfunc.svg)


| Model                                        | Computers | Drives | Percent |
|----------------------------------------------|-----------|--------|---------|
| WDC WD5000LPCX-60VHAT0 500GB                 | 1         | 1      | 5.56%   |
| WDC WD5000AVVS-63H0B1 500GB                  | 1         | 1      | 5.56%   |
| Toshiba MQ01ABF050 500GB                     | 1         | 1      | 5.56%   |
| Toshiba MQ01ABD100 1TB                       | 1         | 1      | 5.56%   |
| Toshiba MK8034GSX 80GB                       | 1         | 1      | 5.56%   |
| Seagate ST9160821AS 160GB                    | 1         | 1      | 5.56%   |
| Seagate ST500LT012-9WS142 500GB              | 1         | 1      | 5.56%   |
| Seagate ST320LT014-9YK142 320GB              | 1         | 1      | 5.56%   |
| Seagate ST1000LM024 HN-M101MBB 1TB           | 1         | 1      | 5.56%   |
| Samsung Electronics MZMPA128HMFU-000H1 128GB | 1         | 1      | 5.56%   |
| Samsung Electronics HD501LJ 500GB            | 1         | 1      | 5.56%   |
| OCZ VERTEX3 240GB                            | 1         | 1      | 5.56%   |
| Hitachi HTS727550A9E364 500GB                | 1         | 1      | 5.56%   |
| Hitachi HTS545050A7E380 500GB                | 1         | 1      | 5.56%   |
| Hitachi HTS545025B9SA02 250GB                | 1         | 1      | 5.56%   |
| Hitachi HTS541680J9SA00 80GB                 | 1         | 1      | 5.56%   |
| Hitachi HTS541612J9SA00 120GB                | 1         | 1      | 5.56%   |
| Fujitsu MHZ2160BH FFS G1 160GB               | 1         | 1      | 5.56%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./All/images/pie_chart_bsd/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Hitachi             | 5         | 5      | 27.78%  |
| Seagate             | 4         | 4      | 22.22%  |
| Toshiba             | 3         | 3      | 16.67%  |
| WDC                 | 2         | 2      | 11.11%  |
| Samsung Electronics | 2         | 2      | 11.11%  |
| OCZ                 | 1         | 1      | 5.56%   |
| Fujitsu             | 1         | 1      | 5.56%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./All/images/pie_chart_bsd/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Hitachi             | 5         | 5      | 31.25%  |
| Seagate             | 4         | 4      | 25%     |
| Toshiba             | 3         | 3      | 18.75%  |
| WDC                 | 2         | 2      | 12.5%   |
| Samsung Electronics | 1         | 1      | 6.25%   |
| Fujitsu             | 1         | 1      | 6.25%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./All/images/pie_chart_bsd/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
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

![Drive Status](./All/images/pie_chart_bsd/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Works    | 62        | 89     | 79.49%  |
| Malfunc  | 14        | 18     | 17.95%  |
| Detected | 2         | 5      | 2.56%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart_bsd/storage_vendor.svg)


| Vendor                         | Computers | Percent |
|--------------------------------|-----------|---------|
| Intel                          | 55        | 57.89%  |
| AMD                            | 12        | 12.63%  |
| Samsung Electronics            | 5         | 5.26%   |
| Nvidia                         | 4         | 4.21%   |
| SanDisk                        | 3         | 3.16%   |
| JMicron Technology             | 3         | 3.16%   |
| SK hynix                       | 2         | 2.11%   |
| Kingston Technology Company    | 2         | 2.11%   |
| Solid State Storage Technology | 1         | 1.05%   |
| Silicon Motion                 | 1         | 1.05%   |
| Shenzhen Longsys Electronics   | 1         | 1.05%   |
| Realtek Semiconductor          | 1         | 1.05%   |
| Phison Electronics             | 1         | 1.05%   |
| Micron/Crucial Technology      | 1         | 1.05%   |
| Marvell Technology Group       | 1         | 1.05%   |
| KIOXIA                         | 1         | 1.05%   |
| ASMedia Technology             | 1         | 1.05%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart_bsd/storage_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 9         | 8.74%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 5         | 4.85%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 5         | 4.85%   |
| Nvidia MCP79 AHCI Controller                                                   | 4         | 3.88%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                             | 4         | 3.88%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 4         | 3.88%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                              | 3         | 2.91%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 3         | 2.91%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                              | 3         | 2.91%   |
| Intel 82801G (ICH7 Family) IDE Controller                                      | 3         | 2.91%   |
| Unknown                                                                        | 3         | 2.91%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 2         | 1.94%   |
| Samsung NVMe SSD Controller 980                                                | 2         | 1.94%   |
| JMicron JMB368 IDE controller                                                  | 2         | 1.94%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                         | 2         | 1.94%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 2         | 1.94%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 2         | 1.94%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 2         | 1.94%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 2         | 1.94%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 2         | 1.94%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller  | 2         | 1.94%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                               | 2         | 1.94%   |
| SK hynix Gold P31 SSD                                                          | 1         | 0.97%   |
| SK hynix BC511                                                                 | 1         | 0.97%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                | 1         | 0.97%   |
| Shenzhen Longsys SM2263EN/SM2263XT-based OEM SSD                               | 1         | 0.97%   |
| SanDisk WD Blue SN550 NVMe SSD                                                 | 1         | 0.97%   |
| SanDisk WD Blue SN500 / PC SN520 NVMe SSD                                      | 1         | 0.97%   |
| SanDisk WD Black 2018/SN750 / PC SN720 NVMe SSD                                | 1         | 0.97%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 1         | 0.97%   |
| Phison E12 NVMe Controller                                                     | 1         | 0.97%   |
| Micron/Crucial P2 NVMe PCIe SSD                                                | 1         | 0.97%   |
| Marvell Group 88SE9235 PCIe 2.0 x2 4-port SATA 6 Gb/s Controller               | 1         | 0.97%   |
| KIOXIA NVMe SSD Controller BG4                                                 | 1         | 0.97%   |
| Kingston Company A2000 NVMe SSD                                                | 1         | 0.97%   |
| JMicron JMB363 SATA/IDE Controller                                             | 1         | 0.97%   |
| Intel SSD Pro 7600p/760p/E 6100p Series                                        | 1         | 0.97%   |
| Intel SATA Controller [RAID mode]                                              | 1         | 0.97%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 1         | 0.97%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 1         | 0.97%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart_bsd/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 62        | 65.96%  |
| NVMe | 19        | 20.21%  |
| IDE  | 10        | 10.64%  |
| RAID | 3         | 3.19%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart_bsd/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 65        | 83.33%  |
| AMD    | 13        | 16.67%  |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart_bsd/cpu_model.svg)


| Model                                       | Computers | Percent |
|---------------------------------------------|-----------|---------|
| Intel Core i7-8559U CPU @ 2.70GHz           | 2         | 2.56%   |
| Intel Core i7-6600U CPU @ 2.60GHz           | 2         | 2.56%   |
| Intel Core i5-5300U CPU @ 2.30GHz           | 2         | 2.56%   |
| Intel Core i5-5200U CPU @ 2.20GHz           | 2         | 2.56%   |
| Intel Core 2 Duo CPU P7450 @ 2.13GHz        | 2         | 2.56%   |
| AMD Ryzen 7 4800H with Radeon Graphics      | 2         | 2.56%   |
| Intel Xeon CPU E5-2630L v4 @ 1.80GHz        | 1         | 1.28%   |
| Intel Pentium Silver N5000 CPU @ 1.10GHz    | 1         | 1.28%   |
| Intel Pentium Silver J5040 CPU @ 2.00GHz    | 1         | 1.28%   |
| Intel Pentium Dual-Core CPU E6700 @ 3.20GHz | 1         | 1.28%   |
| Intel Pentium Dual-Core CPU E5700 @ 3.00GHz | 1         | 1.28%   |
| Intel Pentium Dual-Core CPU E5400 @ 2.70GHz | 1         | 1.28%   |
| Intel Pentium Dual-Core CPU E5200 @ 2.50GHz | 1         | 1.28%   |
| Intel Pentium CPU N3700 @ 1.60GHz           | 1         | 1.28%   |
| Intel Pentium CPU G4400 @ 3.30GHz           | 1         | 1.28%   |
| Intel Pentium CPU 4417U @ 2.30GHz           | 1         | 1.28%   |
| Intel CPU Version                           | 1         | 1.28%   |
| Intel Core i7-9700 CPU @ 3.00GHz            | 1         | 1.28%   |
| Intel Core i7-8565U CPU @ 1.80GHz           | 1         | 1.28%   |
| Intel Core i7-8550U CPU @ 1.80GHz           | 1         | 1.28%   |
| Intel Core i7-5500U CPU @ 2.40GHz           | 1         | 1.28%   |
| Intel Core i7-4810MQ CPU @ 2.80GHz          | 1         | 1.28%   |
| Intel Core i7-4790 CPU @ 3.60GHz            | 1         | 1.28%   |
| Intel Core i7-2677M CPU @ 1.80GHz           | 1         | 1.28%   |
| Intel Core i7-2620M CPU @ 2.70GHz           | 1         | 1.28%   |
| Intel Core i5-7200U CPU @ 2.50GHz           | 1         | 1.28%   |
| Intel Core i5-6500 CPU @ 3.20GHz            | 1         | 1.28%   |
| Intel Core i5-6440HQ CPU @ 2.60GHz          | 1         | 1.28%   |
| Intel Core i5-6300U CPU @ 2.40GHz           | 1         | 1.28%   |
| Intel Core i5-6300HQ CPU @ 2.30GHz          | 1         | 1.28%   |
| Intel Core i5-6200U CPU @ 2.30GHz           | 1         | 1.28%   |
| Intel Core i5-4570T CPU @ 2.90GHz           | 1         | 1.28%   |
| Intel Core i5-4310U CPU @ 2.00GHz           | 1         | 1.28%   |
| Intel Core i5-4300U CPU @ 1.90GHz           | 1         | 1.28%   |
| Intel Core i5-3470 CPU @ 3.20GHz            | 1         | 1.28%   |
| Intel Core i5-2540M CPU @ 2.60GHz           | 1         | 1.28%   |
| Intel Core i5-2520M CPU @ 2.50GHz           | 1         | 1.28%   |
| Intel Core i3-8100 CPU @ 3.60GHz            | 1         | 1.28%   |
| Intel Core i3-7020U CPU @ 2.30GHz           | 1         | 1.28%   |
| Intel Core i3-5010U CPU @ 2.10GHz           | 1         | 1.28%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart_bsd/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 16        | 20.51%  |
| Intel Core i7           | 12        | 15.38%  |
| Intel Core i3           | 7         | 8.97%   |
| Intel Core 2 Duo        | 6         | 7.69%   |
| Other                   | 5         | 6.41%   |
| Intel Atom              | 5         | 6.41%   |
| Intel Pentium Dual-Core | 4         | 5.13%   |
| Intel Celeron           | 4         | 5.13%   |
| AMD Ryzen 5             | 4         | 5.13%   |
| Intel Pentium           | 3         | 3.85%   |
| AMD Ryzen 7             | 3         | 3.85%   |
| Intel Pentium Silver    | 2         | 2.56%   |
| Intel Xeon              | 1         | 1.28%   |
| Intel Core 2 Quad       | 1         | 1.28%   |
| AMD Ryzen 9             | 1         | 1.28%   |
| AMD Ryzen 5 PRO         | 1         | 1.28%   |
| AMD FX                  | 1         | 1.28%   |
| AMD Athlon 64 X2        | 1         | 1.28%   |
| AMD A8                  | 1         | 1.28%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart_bsd/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 34        | 43.59%  |
| 4       | 23        | 29.49%  |
| Unknown | 6         | 7.69%   |
| 8       | 5         | 6.41%   |
| 12      | 3         | 3.85%   |
| 16      | 2         | 2.56%   |
| 1       | 2         | 2.56%   |
| 24      | 1         | 1.28%   |
| 10      | 1         | 1.28%   |
| 6       | 1         | 1.28%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart_bsd/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 74        | 94.87%  |
| 2      | 4         | 5.13%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart_bsd/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 37        | 47.44%  |
| 1       | 35        | 44.87%  |
| Unknown | 6         | 7.69%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart_bsd/cpu_microarch.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| Penryn        | 10        | 12.82%  |
| KabyLake      | 9         | 11.54%  |
| Skylake       | 8         | 10.26%  |
| Broadwell     | 7         | 8.97%   |
| SandyBridge   | 6         | 7.69%   |
| Zen 2         | 5         | 6.41%   |
| Silvermont    | 5         | 6.41%   |
| Haswell       | 5         | 6.41%   |
| Goldmont plus | 3         | 3.85%   |
| Bonnell       | 3         | 3.85%   |
| Zen+          | 2         | 2.56%   |
| TigerLake     | 2         | 2.56%   |
| IvyBridge     | 2         | 2.56%   |
| Unknown       | 2         | 2.56%   |
| Zen 3         | 1         | 1.28%   |
| Zen           | 1         | 1.28%   |
| Westmere      | 1         | 1.28%   |
| Piledriver    | 1         | 1.28%   |
| Nehalem       | 1         | 1.28%   |
| K8 Hammer     | 1         | 1.28%   |
| Excavator     | 1         | 1.28%   |
| Core          | 1         | 1.28%   |
| CometLake     | 1         | 1.28%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart_bsd/gpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 52        | 57.14%  |
| Nvidia | 23        | 25.27%  |
| AMD    | 16        | 17.58%  |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart_bsd/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel HD Graphics 5500                                                                   | 6         | 6.59%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 6         | 6.59%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 4         | 4.4%    |
| Intel HD Graphics 530                                                                    | 3         | 3.3%    |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 3         | 3.3%    |
| AMD Renoir                                                                               | 3         | 3.3%    |
| Nvidia TU116 [GeForce GTX 1660]                                                          | 2         | 2.2%    |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 2         | 2.2%    |
| Nvidia C79 [GeForce 9400M G]                                                             | 2         | 2.2%    |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 2         | 2.2%    |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 2         | 2.2%    |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 2         | 2.2%    |
| Intel HD Graphics 620                                                                    | 2         | 2.2%    |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 2         | 2.2%    |
| Intel GeminiLake [UHD Graphics 605]                                                      | 2         | 2.2%    |
| Intel CoffeeLake-U GT3e [Iris Plus Graphics 655]                                         | 2         | 2.2%    |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 2         | 2.2%    |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller                  | 2         | 2.2%    |
| Nvidia TU117M [GeForce MX450]                                                            | 1         | 1.1%    |
| Nvidia TU117M                                                                            | 1         | 1.1%    |
| Nvidia TU116 [GeForce GTX 1660 Ti]                                                       | 1         | 1.1%    |
| Nvidia GT218 [GeForce 210]                                                               | 1         | 1.1%    |
| Nvidia GP108M [GeForce MX150]                                                            | 1         | 1.1%    |
| Nvidia GP108 [GeForce GT 1030]                                                           | 1         | 1.1%    |
| Nvidia GM206 [GeForce GTX 950]                                                           | 1         | 1.1%    |
| Nvidia GM108M [GeForce MX110]                                                            | 1         | 1.1%    |
| Nvidia GM107M [GeForce GTX 950M]                                                         | 1         | 1.1%    |
| Nvidia GK104 [GeForce GTX 760]                                                           | 1         | 1.1%    |
| Nvidia GF119M [Quadro NVS 4200M]                                                         | 1         | 1.1%    |
| Nvidia GF108M [GeForce 610M]                                                             | 1         | 1.1%    |
| Nvidia G96CM [GeForce 9600M GT]                                                          | 1         | 1.1%    |
| Nvidia G84 [GeForce 8600 GTS]                                                            | 1         | 1.1%    |
| Nvidia G73 [GeForce 7600 GS]                                                             | 1         | 1.1%    |
| Nvidia C79 [GeForce 9400]                                                                | 1         | 1.1%    |
| Nvidia C79 [GeForce 9400M]                                                               | 1         | 1.1%    |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 1         | 1.1%    |
| Intel UHD Graphics 620                                                                   | 1         | 1.1%    |
| Intel RocketLake-S GT1 [UHD Graphics 730]                                                | 1         | 1.1%    |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 1         | 1.1%    |
| Intel Kaby Lake-U GT1 Integrated Graphics Controller                                     | 1         | 1.1%    |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart_bsd/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 37        | 47.44%  |
| 1 x Nvidia     | 14        | 17.95%  |
| 1 x AMD        | 11        | 14.1%   |
| Intel + Nvidia | 8         | 10.26%  |
| Intel + AMD    | 4         | 5.13%   |
| 2 x Intel      | 3         | 3.85%   |
| AMD + Nvidia   | 1         | 1.28%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart_bsd/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 59        | 75.64%  |
| Proprietary | 13        | 16.67%  |
| Unknown     | 6         | 7.69%   |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart_bsd/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 58        | 74.36%  |
| 0.01-0.5   | 8         | 10.26%  |
| 1.01-2.0   | 4         | 5.13%   |
| 5.01-6.0   | 3         | 3.85%   |
| 3.01-4.0   | 2         | 2.56%   |
| 0.51-1.0   | 2         | 2.56%   |
| 7.01-8.0   | 1         | 1.28%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart_bsd/mon_vendor.svg)


| Vendor               | Computers | Percent |
|----------------------|-----------|---------|
| LG Display           | 10        | 14.08%  |
| AU Optronics         | 9         | 12.68%  |
| Chimei Innolux       | 6         | 8.45%   |
| Dell                 | 5         | 7.04%   |
| BOE                  | 5         | 7.04%   |
| Apple                | 5         | 7.04%   |
| Samsung Electronics  | 4         | 5.63%   |
| Goldstar             | 4         | 5.63%   |
| MSI                  | 3         | 4.23%   |
| Philips              | 2         | 2.82%   |
| Hewlett-Packard      | 2         | 2.82%   |
| BenQ                 | 2         | 2.82%   |
| AOC                  | 2         | 2.82%   |
| Vizio                | 1         | 1.41%   |
| Toshiba              | 1         | 1.41%   |
| TMX                  | 1         | 1.41%   |
| Nvidia               | 1         | 1.41%   |
| LG Philips           | 1         | 1.41%   |
| Insignia             | 1         | 1.41%   |
| Iiyama               | 1         | 1.41%   |
| HannStar             | 1         | 1.41%   |
| Fujitsu Siemens      | 1         | 1.41%   |
| CPT                  | 1         | 1.41%   |
| Ancor Communications | 1         | 1.41%   |
| Acer                 | 1         | 1.41%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart_bsd/mon_model.svg)


| Model                                                                 | Computers | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| MSI G32C4 MSI3DA6 1920x1080 700x390mm 31.5-inch                       | 2         | 2.78%   |
| LG Display LCD Monitor LGD0484 1366x768 340x190mm 15.3-inch           | 2         | 2.78%   |
| Apple Color LCD APP9C5C 1280x800 290x180mm 13.4-inch                  | 2         | 2.78%   |
| Vizio D43-D2 VIZ1004 1920x1080 930x520mm 41.9-inch                    | 1         | 1.39%   |
| Toshiba TV TSB0110 1920x1080 1110x620mm 50.1-inch                     | 1         | 1.39%   |
| TMX LCD Monitor TMX1560 3200x2000 340x210mm 15.7-inch                 | 1         | 1.39%   |
| Samsung Electronics SyncMaster SAM0601 1600x900                       | 1         | 1.39%   |
| Samsung Electronics SyncMaster SAM05FF 1600x900 440x250mm 19.9-inch   | 1         | 1.39%   |
| Samsung Electronics SMS23A550H SAM07C9 1920x1080 510x290mm 23.1-inch  | 1         | 1.39%   |
| Samsung Electronics LCD Monitor SEC4149 1366x768 280x170mm 12.9-inch  | 1         | 1.39%   |
| Samsung Electronics LCD Monitor SDC4C48 1920x1080 340x190mm 15.3-inch | 1         | 1.39%   |
| Philips PHL 223V5 PHLC0CF 1920x1080 480x270mm 21.7-inch               | 1         | 1.39%   |
| Philips 237EQPH PHLC091 1920x1080 510x290mm 23.1-inch                 | 1         | 1.39%   |
| Nvidia LCD Monitor NVD0200 1920x1080 320x180mm 14.5-inch              | 1         | 1.39%   |
| MSI MAG342CQRV MSI3DB6 3440x1440 790x330mm 33.7-inch                  | 1         | 1.39%   |
| LG Philips LCD Monitor LPLE300 1280x800 330x210mm 15.4-inch           | 1         | 1.39%   |
| LG Display LCD Monitor LGD0532 1920x1080 340x190mm 15.3-inch          | 1         | 1.39%   |
| LG Display LCD Monitor LGD0470 1920x1080 350x190mm 15.7-inch          | 1         | 1.39%   |
| LG Display LCD Monitor LGD046F 1920x1080 340x190mm 15.3-inch          | 1         | 1.39%   |
| LG Display LCD Monitor LGD0435 1600x900 310x170mm 13.9-inch           | 1         | 1.39%   |
| LG Display LCD Monitor LGD03EE 1366x768 280x160mm 12.7-inch           | 1         | 1.39%   |
| LG Display LCD Monitor LGD0384 1366x768 340x190mm 15.3-inch           | 1         | 1.39%   |
| LG Display LCD Monitor LGD02DC 1366x768 340x190mm 15.3-inch           | 1         | 1.39%   |
| LG Display LCD Monitor LGD021D 1600x900 380x210mm 17.1-inch           | 1         | 1.39%   |
| Insignia 32DR310NA17 BBY3253 1680x1050 700x390mm 31.5-inch            | 1         | 1.39%   |
| Iiyama PLE2407HDS IVM560D 1920x1080 520x300mm 23.6-inch               | 1         | 1.39%   |
| Hewlett-Packard LCD Monitor HWP26A4 1440x900 410x260mm 19.1-inch      | 1         | 1.39%   |
| Hewlett-Packard 27xi HWP3038 1920x1080 600x340mm 27.2-inch            | 1         | 1.39%   |
| HannStar LCD Monitor HSD03E9 1024x600 220x130mm 10.1-inch             | 1         | 1.39%   |
| Goldstar LG ULTRAWIDE GSM5AE2 3440x1440 800x340mm 34.2-inch           | 1         | 1.39%   |
| Goldstar L1918S GSM4B31 1280x1024 380x300mm 19.1-inch                 | 1         | 1.39%   |
| Goldstar 2D FHD LG TV GSM59C6 1920x1080 510x290mm 23.1-inch           | 1         | 1.39%   |
| Goldstar 22MP55 GSM5A24 1920x1080 480x270mm 21.7-inch                 | 1         | 1.39%   |
| Fujitsu Siemens XE17-4 FUS0674 1280x1024 340x270mm 17.1-inch          | 1         | 1.39%   |
| Dell S2316H DELD07E 1920x1080 510x290mm 23.1-inch                     | 1         | 1.39%   |
| Dell P2412H DELA07D 1920x1080 530x300mm 24.0-inch                     | 1         | 1.39%   |
| Dell E228WFP DELD015 1680x1050 470x300mm 22.0-inch                    | 1         | 1.39%   |
| Dell E2216HV DELF06F 1920x1080 480x270mm 21.7-inch                    | 1         | 1.39%   |
| Dell D1918H DEL2005 1366x768 410x230mm 18.5-inch                      | 1         | 1.39%   |
| CPT LCD Monitor COR17DB 1600x900 290x160mm 13.0-inch                  | 1         | 1.39%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart_bsd/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 30        | 42.86%  |
| 1366x768 (WXGA)    | 16        | 22.86%  |
| 1680x1050 (WSXGA+) | 5         | 7.14%   |
| 1600x900 (HD+)     | 5         | 7.14%   |
| 1280x800 (WXGA)    | 5         | 7.14%   |
| 3440x1440          | 2         | 2.86%   |
| 1280x1024 (SXGA)   | 2         | 2.86%   |
| 3200x2000          | 1         | 1.43%   |
| 2560x1440 (QHD)    | 1         | 1.43%   |
| 1920x1200 (WUXGA)  | 1         | 1.43%   |
| 1440x900 (WXGA+)   | 1         | 1.43%   |
| 1024x600           | 1         | 1.43%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart_bsd/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 21        | 29.17%  |
| 13      | 12        | 16.67%  |
| 23      | 5         | 6.94%   |
| 12      | 5         | 6.94%   |
| 24      | 4         | 5.56%   |
| 31      | 3         | 4.17%   |
| 21      | 3         | 4.17%   |
| 19      | 3         | 4.17%   |
| 22      | 2         | 2.78%   |
| 20      | 2         | 2.78%   |
| 17      | 2         | 2.78%   |
| 10      | 2         | 2.78%   |
| 50      | 1         | 1.39%   |
| 41      | 1         | 1.39%   |
| 34      | 1         | 1.39%   |
| 33      | 1         | 1.39%   |
| 27      | 1         | 1.39%   |
| 18      | 1         | 1.39%   |
| 14      | 1         | 1.39%   |
| Unknown | 1         | 1.39%   |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart_bsd/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 29        | 40.28%  |
| 201-300     | 13        | 18.06%  |
| 501-600     | 10        | 13.89%  |
| 401-500     | 10        | 13.89%  |
| 601-700     | 3         | 4.17%   |
| 701-800     | 2         | 2.78%   |
| 351-400     | 2         | 2.78%   |
| 1001-1500   | 1         | 1.39%   |
| 901-1000    | 1         | 1.39%   |
| Unknown     | 1         | 1.39%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart_bsd/mon_ratio.svg)


| Ratio | Computers | Percent |
|-------|-----------|---------|
| 16/9  | 53        | 75.71%  |
| 16/10 | 13        | 18.57%  |
| 5/4   | 2         | 2.86%   |
| 21/9  | 2         | 2.86%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart_bsd/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 91-100         | 17        | 23.61%  |
| 201-250        | 13        | 18.06%  |
| 81-90          | 11        | 15.28%  |
| 351-500        | 5         | 6.94%   |
| 151-200        | 5         | 6.94%   |
| 61-70          | 4         | 5.56%   |
| 71-80          | 3         | 4.17%   |
| 101-110        | 3         | 4.17%   |
| 41-50          | 2         | 2.78%   |
| 141-150        | 2         | 2.78%   |
| More than 1000 | 1         | 1.39%   |
| 301-350        | 1         | 1.39%   |
| 251-300        | 1         | 1.39%   |
| 121-130        | 1         | 1.39%   |
| 111-120        | 1         | 1.39%   |
| 501-1000       | 1         | 1.39%   |
| Unknown        | 1         | 1.39%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart_bsd/mon_density.svg)


| Density | Computers | Percent |
|---------|-----------|---------|
| 101-120 | 24        | 33.33%  |
| 51-100  | 23        | 31.94%  |
| 121-160 | 19        | 26.39%  |
| 161-240 | 4         | 5.56%   |
| 1-50    | 1         | 1.39%   |
| Unknown | 1         | 1.39%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart_bsd/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 68        | 87.18%  |
| 0     | 7         | 8.97%   |
| 2     | 3         | 3.85%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart_bsd/net_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Intel                    | 43        | 37.72%  |
| Realtek Semiconductor    | 35        | 30.7%   |
| Qualcomm Atheros         | 12        | 10.53%  |
| Broadcom                 | 8         | 7.02%   |
| Nvidia                   | 4         | 3.51%   |
| Ralink Technology        | 2         | 1.75%   |
| Marvell Technology Group | 2         | 1.75%   |
| Sierra Wireless          | 1         | 0.88%   |
| Samsung Electronics      | 1         | 0.88%   |
| Ralink                   | 1         | 0.88%   |
| IMC Networks             | 1         | 0.88%   |
| Huawei Technologies      | 1         | 0.88%   |
| Edimax Technology        | 1         | 0.88%   |
| D-Link System            | 1         | 0.88%   |
| ASUSTek Computer         | 1         | 0.88%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart_bsd/net_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 29        | 21.97%  |
| Intel Wireless 7265                                               | 7         | 5.3%    |
| Intel Wi-Fi 6 AX200                                               | 5         | 3.79%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 4         | 3.03%   |
| Nvidia MCP79 Ethernet                                             | 4         | 3.03%   |
| Intel Wireless 8265 / 8275                                        | 4         | 3.03%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 3         | 2.27%   |
| Intel Ethernet Connection I217-LM                                 | 3         | 2.27%   |
| Intel Ethernet Connection (3) I218-LM                             | 3         | 2.27%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 3         | 2.27%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller            | 3         | 2.27%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                           | 2         | 1.52%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 2         | 1.52%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 2         | 1.52%   |
| Qualcomm Atheros AR8132 Fast Ethernet                             | 2         | 1.52%   |
| Intel Wireless 8260                                               | 2         | 1.52%   |
| Intel Wireless 3160                                               | 2         | 1.52%   |
| Intel WiFi Link 5100                                              | 2         | 1.52%   |
| Intel Wi-Fi 6 AX201                                               | 2         | 1.52%   |
| Intel Ethernet Connection I219-LM                                 | 2         | 1.52%   |
| Intel Ethernet Connection I218-LM                                 | 2         | 1.52%   |
| Intel Ethernet Connection (6) I219-V                              | 2         | 1.52%   |
| Intel Ethernet Connection (2) I219-LM                             | 2         | 1.52%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 2         | 1.52%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 2         | 1.52%   |
| Intel 82574L Gigabit Network Connection                           | 2         | 1.52%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 2         | 1.52%   |
| Sierra Wireless EM7455                                            | 1         | 0.76%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)       | 1         | 0.76%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 1         | 0.76%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                        | 1         | 0.76%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 1         | 0.76%   |
| Ralink RT5370 Wireless Adapter                                    | 1         | 0.76%   |
| Ralink RT2870/RT3070 Wireless Adapter                             | 1         | 0.76%   |
| Ralink RT5390 Wireless 802.11n 1T/1R PCIe                         | 1         | 0.76%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 1         | 0.76%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 1         | 0.76%   |
| Qualcomm Atheros AR8162 Fast Ethernet                             | 1         | 0.76%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 1         | 0.76%   |
| Qualcomm Atheros AR5212 802.11abg NIC                             | 1         | 0.76%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart_bsd/net_wireless_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Intel                 | 32        | 50.79%  |
| Qualcomm Atheros      | 10        | 15.87%  |
| Realtek Semiconductor | 7         | 11.11%  |
| Broadcom              | 6         | 9.52%   |
| Ralink Technology     | 2         | 3.17%   |
| Sierra Wireless       | 1         | 1.59%   |
| Ralink                | 1         | 1.59%   |
| IMC Networks          | 1         | 1.59%   |
| Edimax Technology     | 1         | 1.59%   |
| D-Link System         | 1         | 1.59%   |
| ASUSTek Computer      | 1         | 1.59%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart_bsd/net_wireless_model.svg)


| Model                                                                       | Computers | Percent |
|-----------------------------------------------------------------------------|-----------|---------|
| Intel Wireless 7265                                                         | 7         | 11.11%  |
| Intel Wi-Fi 6 AX200                                                         | 5         | 7.94%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                            | 4         | 6.35%   |
| Intel Wireless 8265 / 8275                                                  | 4         | 6.35%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                    | 3         | 4.76%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller                      | 3         | 4.76%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                                     | 2         | 3.17%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)              | 2         | 3.17%   |
| Intel Wireless 8260                                                         | 2         | 3.17%   |
| Intel Wireless 3160                                                         | 2         | 3.17%   |
| Intel WiFi Link 5100                                                        | 2         | 3.17%   |
| Intel Wi-Fi 6 AX201                                                         | 2         | 3.17%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                            | 2         | 3.17%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                    | 2         | 3.17%   |
| Sierra Wireless EM7455                                                      | 1         | 1.59%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                             | 1         | 1.59%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                                  | 1         | 1.59%   |
| Ralink RT5370 Wireless Adapter                                              | 1         | 1.59%   |
| Ralink RT2870/RT3070 Wireless Adapter                                       | 1         | 1.59%   |
| Ralink RT5390 Wireless 802.11n 1T/1R PCIe                                   | 1         | 1.59%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                  | 1         | 1.59%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                  | 1         | 1.59%   |
| Qualcomm Atheros AR5212 802.11abg NIC                                       | 1         | 1.59%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express)     | 1         | 1.59%   |
| Intel Wireless 7260                                                         | 1         | 1.59%   |
| Intel Gemini Lake PCH CNVi WiFi                                             | 1         | 1.59%   |
| Intel Centrino Ultimate-N 6300                                              | 1         | 1.59%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                                | 1         | 1.59%   |
| IMC Networks Realtek RTL8191SU Wireless LAN 802.11n USB 2.0 Network Adapter | 1         | 1.59%   |
| Edimax EW-7612UAn V2 802.11n Wireless Adapter [Realtek RTL8192CU]           | 1         | 1.59%   |
| D-Link System DWA-125 Wireless N 150 Adapter(rev.A1) [Ralink RT3070]        | 1         | 1.59%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                          | 1         | 1.59%   |
| Broadcom BCM43224 802.11a/b/g/n                                             | 1         | 1.59%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                         | 1         | 1.59%   |
| ASUS N10 Nano 802.11n Network Adapter [Realtek RTL8192CU]                   | 1         | 1.59%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart_bsd/net_ethernet_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 32        | 47.76%  |
| Intel                    | 22        | 32.84%  |
| Qualcomm Atheros         | 4         | 5.97%   |
| Nvidia                   | 4         | 5.97%   |
| Marvell Technology Group | 2         | 2.99%   |
| Broadcom                 | 2         | 2.99%   |
| Samsung Electronics      | 1         | 1.49%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart_bsd/net_ethernet_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller              | 29        | 42.65%  |
| Nvidia MCP79 Ethernet                                                          | 4         | 5.88%   |
| Intel Ethernet Connection I217-LM                                              | 3         | 4.41%   |
| Intel Ethernet Connection (3) I218-LM                                          | 3         | 4.41%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                          | 3         | 4.41%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                          | 2         | 2.94%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                          | 2         | 2.94%   |
| Intel Ethernet Connection I219-LM                                              | 2         | 2.94%   |
| Intel Ethernet Connection I218-LM                                              | 2         | 2.94%   |
| Intel Ethernet Connection (6) I219-V                                           | 2         | 2.94%   |
| Intel Ethernet Connection (2) I219-LM                                          | 2         | 2.94%   |
| Intel 82574L Gigabit Network Connection                                        | 2         | 2.94%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                                | 2         | 2.94%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)                    | 1         | 1.47%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                          | 1         | 1.47%   |
| Qualcomm Atheros AR8162 Fast Ethernet                                          | 1         | 1.47%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                                     | 1         | 1.47%   |
| Marvell Group Yukon Optima 88E8059 [PCIe Gigabit Ethernet Controller with AVB] | 1         | 1.47%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller                        | 1         | 1.47%   |
| Intel Ethernet Controller I225-V                                               | 1         | 1.47%   |
| Intel Ethernet Connection (4) I219-LM                                          | 1         | 1.47%   |
| Intel Ethernet Connection (2) I219-V                                           | 1         | 1.47%   |
| Intel Ethernet Connection (11) I219-LM                                         | 1         | 1.47%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart_bsd/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 67        | 53.17%  |
| WiFi     | 58        | 46.03%  |
| Modem    | 1         | 0.79%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart_bsd/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 49        | 59.04%  |
| WiFi     | 34        | 40.96%  |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart_bsd/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 44        | 56.41%  |
| 1     | 33        | 42.31%  |
| 0     | 1         | 1.28%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart_bsd/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 72        | 92.31%  |
| Yes  | 6         | 7.69%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart_bsd/bt_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Intel                   | 25        | 56.82%  |
| Apple                   | 5         | 11.36%  |
| Realtek Semiconductor   | 3         | 6.82%   |
| Lite-On Technology      | 2         | 4.55%   |
| IMC Networks            | 2         | 4.55%   |
| Cambridge Silicon Radio | 2         | 4.55%   |
| Hewlett-Packard         | 1         | 2.27%   |
| Broadcom                | 1         | 2.27%   |
| Bluetooth Device        | 1         | 2.27%   |
| ASUSTek Computer        | 1         | 2.27%   |
| Alps Electric           | 1         | 2.27%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart_bsd/bt_model.svg)


| Model                                                    | Computers | Percent |
|----------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                       | 14        | 30.43%  |
| Intel AX200 Bluetooth                                    | 4         | 8.7%    |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)           | 3         | 6.52%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                     | 3         | 6.52%   |
| Realtek  Bluetooth 4.2 Adapter                           | 2         | 4.35%   |
| Intel Wireless-AC 3168 Bluetooth                         | 2         | 4.35%   |
| Intel AX201 Bluetooth                                    | 2         | 4.35%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)      | 2         | 4.35%   |
| Apple Built-in iSight (no firmware loaded)               | 2         | 4.35%   |
| Realtek Dell Wireless 1801 Bluetooth 4.0 LE              | 1         | 2.17%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth               | 1         | 2.17%   |
| Lite-On Atheros AR3012 Bluetooth                         | 1         | 2.17%   |
| IMC Networks Realtek Bluetooth Adapter                   | 1         | 2.17%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter        | 1         | 2.17%   |
| HP Broadcom 2070 Bluetooth Combo                         | 1         | 2.17%   |
| Broadcom BCM2045B (BDC-2.1)                              | 1         | 2.17%   |
| Bluetooth Device Silicon Wave Bluetooth Wireless Adapter | 1         | 2.17%   |
| ASUS BT-253 Bluetooth Adapter                            | 1         | 2.17%   |
| Apple Bluetooth Host Controller                          | 1         | 2.17%   |
| Apple Apple Broadcom Built-in Bluetooth                  | 1         | 2.17%   |
| Alps Electric BCM2046 Bluetooth Device                   | 1         | 2.17%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart_bsd/snd_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Intel               | 59        | 60.82%  |
| AMD                 | 16        | 16.49%  |
| Nvidia              | 12        | 12.37%  |
| C-Media Electronics | 4         | 4.12%   |
| Google              | 2         | 2.06%   |
| Yamaha              | 1         | 1.03%   |
| XMOS                | 1         | 1.03%   |
| GN Netcom           | 1         | 1.03%   |
| Creative Technology | 1         | 1.03%   |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart_bsd/snd_model.svg)


| Model                                                                                             | Computers | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                                                   | 8         | 6.9%    |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 7         | 6.03%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 6         | 5.17%   |
| Intel Broadwell-U Audio Controller                                                                | 6         | 5.17%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 6         | 5.17%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 6         | 5.17%   |
| Nvidia MCP79 High Definition Audio                                                                | 4         | 3.45%   |
| Nvidia TU116 High Definition Audio Controller                                                     | 3         | 2.59%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 3         | 2.59%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 3         | 2.59%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 3         | 2.59%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 3         | 2.59%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 3         | 2.59%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 3         | 2.59%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 2         | 1.72%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 2         | 1.72%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 2         | 1.72%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 2         | 1.72%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 2         | 1.72%   |
| Intel 8 Series HD Audio Controller                                                                | 2         | 1.72%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 2         | 1.72%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 2         | 1.72%   |
| Intel 200 Series PCH HD Audio                                                                     | 2         | 1.72%   |
| Google Pixel earbuds                                                                              | 2         | 1.72%   |
| C-Media Electronics Audio Adapter (Unitek Y-247A)                                                 | 2         | 1.72%   |
| AMD Starship/Matisse HD Audio Controller                                                          | 2         | 1.72%   |
| AMD FCH Azalia Controller                                                                         | 2         | 1.72%   |
| Yamaha Steinberg UR22mkII                                                                         | 1         | 0.86%   |
| XMOS iFi (by AMR) HD USB Audio                                                                    | 1         | 0.86%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 1         | 0.86%   |
| Nvidia High Definition Audio Controller                                                           | 1         | 0.86%   |
| Nvidia GP108 High Definition Audio Controller                                                     | 1         | 0.86%   |
| Nvidia GM206 High Definition Audio Controller                                                     | 1         | 0.86%   |
| Nvidia GK104 HDMI Audio Controller                                                                | 1         | 0.86%   |
| Intel Tiger Lake-H HD Audio Controller                                                            | 1         | 0.86%   |
| Intel Cannon Lake PCH cAVS                                                                        | 1         | 0.86%   |
| Intel C610/X99 series chipset HD Audio Controller                                                 | 1         | 0.86%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                                  | 1         | 0.86%   |
| GN Netcom Jabra EVOLVE 20                                                                         | 1         | 0.86%   |
| Creative Technology Sound BlasterX G1                                                             | 1         | 0.86%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart_bsd/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| SK hynix            | 20        | 21.05%  |
| Samsung Electronics | 15        | 15.79%  |
| Unknown             | 14        | 14.74%  |
| Kingston            | 13        | 13.68%  |
| Micron Technology   | 9         | 9.47%   |
| Crucial             | 5         | 5.26%   |
| Unknown             | 3         | 3.16%   |
| Smart               | 2         | 2.11%   |
| Ramaxel Technology  | 2         | 2.11%   |
| Nanya Technology    | 2         | 2.11%   |
| A-DATA Technology   | 2         | 2.11%   |
| Transcend           | 1         | 1.05%   |
| Smart Brazil        | 1         | 1.05%   |
| Patriot             | 1         | 1.05%   |
| GLOWAY              | 1         | 1.05%   |
| GeIL                | 1         | 1.05%   |
| G.Skill             | 1         | 1.05%   |
| Elpida              | 1         | 1.05%   |
| Corsair             | 1         | 1.05%   |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart_bsd/memory_model.svg)


| Model                                                  | Computers | Percent |
|--------------------------------------------------------|-----------|---------|
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s | 3         | 2.97%   |
| Unknown                                                | 3         | 2.97%   |
| Unknown RAM Module 1GB DIMM SDRAM                      | 2         | 1.98%   |
| SK hynix RAM HMT41GU6BFR8A-PB 8GB DIMM DDR3 1600MT/s   | 2         | 1.98%   |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2400MT/s | 2         | 1.98%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s  | 2         | 1.98%   |
| Unknown RAM Module 4GB SODIMM DDR3 1333MT/s            | 1         | 0.99%   |
| Unknown RAM Module 4GB DIMM SDRAM                      | 1         | 0.99%   |
| Unknown RAM Module 4GB DIMM DDR3 1067MT/s              | 1         | 0.99%   |
| Unknown RAM Module 2GB SODIMM DDR3 1333MT/s            | 1         | 0.99%   |
| Unknown RAM Module 2GB SODIMM DDR3 1067MT/s            | 1         | 0.99%   |
| Unknown RAM Module 2GB SODIMM DDR3                     | 1         | 0.99%   |
| Unknown RAM Module 2GB SODIMM DDR2 800MT/s             | 1         | 0.99%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s             | 1         | 0.99%   |
| Unknown RAM Module 2GB SODIMM DDR2                     | 1         | 0.99%   |
| Unknown RAM Module 2GB DIMM SDRAM                      | 1         | 0.99%   |
| Unknown RAM Module 2GB DIMM DDR3 1066MT/s              | 1         | 0.99%   |
| Unknown RAM Module 2GB DIMM DDR2 800MT/s               | 1         | 0.99%   |
| Unknown RAM Module 2GB DIMM DDR2                       | 1         | 0.99%   |
| Unknown RAM Module 1GB SODIMM DDR2 800MT/s             | 1         | 0.99%   |
| Transcend RAM TS256MSK64V3N 2GB SODIMM DDR3 1333MT/s   | 1         | 0.99%   |
| Smart RAM SH564568FH8NZPHSCR 2GB SODIMM DDR3 1334MT/s  | 1         | 0.99%   |
| Smart RAM SH564568FH8NWPHSFR 2GB SODIMM DDR3 1333MT/s  | 1         | 0.99%   |
| Smart RAM SH564128FJ8NWRNSQR 4GB SODIMM DDR3 1600MT/s  | 1         | 0.99%   |
| Smart Brazil RAM Module 4GB Row Of Chips DDR4 2400MT/s | 1         | 0.99%   |
| SK hynix RAM Module 4GB SODIMM DDR4 2400MT/s           | 1         | 0.99%   |
| SK hynix RAM Module 2GB SODIMM DDR3 1067MT/s           | 1         | 0.99%   |
| SK hynix RAM HMT451U6AFR8C-PB 4GB DIMM DDR3 1600MT/s   | 1         | 0.99%   |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s | 1         | 0.99%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s | 1         | 0.99%   |
| SK hynix RAM HMT351S6EFR8C-PB 4GB SODIMM DDR3 1600MT/s | 1         | 0.99%   |
| SK hynix RAM HMT351S6EFR8A-PB 4GB SODIMM DDR3 1600MT/s | 1         | 0.99%   |
| SK hynix RAM HMAA1GU6CJR6N-XN 8GB DIMM DDR4 3200MT/s   | 1         | 0.99%   |
| SK hynix RAM HMA851S6AFR6N-TF 4GB SODIMM DDR4 2133MT/s | 1         | 0.99%   |
| SK hynix RAM HMA81GU6DJR8N-XN 8GB DIMM DDR4 3200MT/s   | 1         | 0.99%   |
| SK hynix RAM HMA81GU6AFR8N-UH 8GB DIMM DDR4 2400MT/s   | 1         | 0.99%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s | 1         | 0.99%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2400MT/s | 1         | 0.99%   |
| SK hynix RAM H9CCNNN8JTBLAR-NUD 2GB LPDDR3 1600MT/s    | 1         | 0.99%   |
| Samsung RAM Module 8GB SODIMM DDR4 2400MT/s            | 1         | 0.99%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart_bsd/memory_kind.svg)


| Kind   | Computers | Percent |
|--------|-----------|---------|
| DDR4   | 33        | 42.31%  |
| DDR3   | 33        | 42.31%  |
| DDR2   | 8         | 10.26%  |
| SDRAM  | 3         | 3.85%   |
| LPDDR3 | 1         | 1.28%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart_bsd/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 48        | 61.54%  |
| DIMM         | 26        | 33.33%  |
| Row Of Chips | 3         | 3.85%   |
| Unknown      | 1         | 1.28%   |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart_bsd/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 4096  | 35        | 38.89%  |
| 8192  | 22        | 24.44%  |
| 2048  | 20        | 22.22%  |
| 16384 | 10        | 11.11%  |
| 1024  | 3         | 3.33%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart_bsd/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 21        | 24.71%  |
| 2400    | 13        | 15.29%  |
| 2667    | 9         | 10.59%  |
| 3200    | 7         | 8.24%   |
| 1333    | 7         | 8.24%   |
| 2133    | 6         | 7.06%   |
| Unknown | 6         | 7.06%   |
| 800     | 4         | 4.71%   |
| 1067    | 3         | 3.53%   |
| 2666    | 2         | 2.35%   |
| 1334    | 2         | 2.35%   |
| 667     | 2         | 2.35%   |
| 2933    | 1         | 1.18%   |
| 1066    | 1         | 1.18%   |
| 333     | 1         | 1.18%   |

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

![Camera Vendor](./All/images/pie_chart_bsd/camera_vendor.svg)


| Vendor                        | Computers | Percent |
|-------------------------------|-----------|---------|
| Chicony Electronics           | 10        | 26.32%  |
| Microdia                      | 6         | 15.79%  |
| Sunplus Innovation Technology | 4         | 10.53%  |
| Realtek Semiconductor         | 4         | 10.53%  |
| IMC Networks                  | 4         | 10.53%  |
| Syntek                        | 2         | 5.26%   |
| Z-Star Microelectronics       | 1         | 2.63%   |
| Suyin                         | 1         | 2.63%   |
| Luxvisions Innotech Limited   | 1         | 2.63%   |
| Logitech                      | 1         | 2.63%   |
| Lite-On Technology            | 1         | 2.63%   |
| Arkmicro Technologies         | 1         | 2.63%   |
| Alcor Micro                   | 1         | 2.63%   |
| Acer                          | 1         | 2.63%   |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart_bsd/camera_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Chicony HD Webcam                             | 3         | 7.89%   |
| Sunplus Integrated_Webcam_HD                  | 2         | 5.26%   |
| Realtek Realtek USB2.0 PC Camera              | 2         | 5.26%   |
| IMC Networks USB2.0 UVC VGA WebCam            | 2         | 5.26%   |
| Chicony integrated camera                     | 2         | 5.26%   |
| Z-Star Venus USB2.0 Camera                    | 1         | 2.63%   |
| Syntek Syntek 0.3MPixel USB 2.0 UVC PC Camera | 1         | 2.63%   |
| Syntek Integrated Camera                      | 1         | 2.63%   |
| Suyin Integrated_Webcam_HD                    | 1         | 2.63%   |
| Sunplus XiaoMi USB 2.0 Webcam                 | 1         | 2.63%   |
| Sunplus HP HD Webcam [Fixed]                  | 1         | 2.63%   |
| Realtek Integrated_Webcam_HD                  | 1         | 2.63%   |
| Realtek HD WebCam                             | 1         | 2.63%   |
| Microdia Webcam                               | 1         | 2.63%   |
| Microdia Laptop_Integrated_Webcam_HD          | 1         | 2.63%   |
| Microdia Laptop_Integrated_Webcam_2M          | 1         | 2.63%   |
| Microdia Integrated_Webcam_HD                 | 1         | 2.63%   |
| Microdia Integrated Webcam HD                 | 1         | 2.63%   |
| Microdia Camera                               | 1         | 2.63%   |
| Luxvisions Innotech Limited Integrated Camera | 1         | 2.63%   |
| Logitech HD Pro Webcam C920                   | 1         | 2.63%   |
| Lite-On HP HD Webcam [Fixed]                  | 1         | 2.63%   |
| IMC Networks USB2.0 VGA UVC WebCam            | 1         | 2.63%   |
| IMC Networks HD Camera                        | 1         | 2.63%   |
| Chicony XiaoMi USB 2.0 Webcam                 | 1         | 2.63%   |
| Chicony VGA WebCam                            | 1         | 2.63%   |
| Chicony TOSHIBA Web Camera - HD               | 1         | 2.63%   |
| Chicony Lenovo EasyCamera                     | 1         | 2.63%   |
| Chicony 1.3M UVC Webcam                       | 1         | 2.63%   |
| Arkmicro Webcam Carrefour                     | 1         | 2.63%   |
| Alcor Micro Acer Integrated Webcam            | 1         | 2.63%   |
| Acer Integrated Camera                        | 1         | 2.63%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./All/images/pie_chart_bsd/fingerprint_vendor.svg)


| Vendor           | Computers | Percent |
|------------------|-----------|---------|
| Validity Sensors | 3         | 50%     |
| Synaptics        | 1         | 16.67%  |
| Broadcom         | 1         | 16.67%  |
| AuthenTec        | 1         | 16.67%  |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./All/images/pie_chart_bsd/fingerprint_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Validity Sensors VFS495 Fingerprint Reader                                   | 2         | 33.33%  |
| Validity Sensors Synaptics WBDI                                              | 1         | 16.67%  |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 1         | 16.67%  |
| AuthenTec AES1600                                                            | 1         | 16.67%  |
| Unknown                                                                      | 1         | 16.67%  |

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

![Unsupported Devices](./All/images/pie_chart_bsd/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 30        | 38.46%  |
| 0     | 20        | 25.64%  |
| 2     | 16        | 20.51%  |
| 3     | 9         | 11.54%  |
| 4     | 2         | 2.56%   |
| 5     | 1         | 1.28%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart_bsd/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Communication controller | 43        | 43.88%  |
| Bluetooth                | 24        | 24.49%  |
| Net/wireless             | 12        | 12.24%  |
| Card reader              | 8         | 8.16%   |
| Fingerprint reader       | 6         | 6.12%   |
| Sound                    | 2         | 2.04%   |
| Network                  | 2         | 2.04%   |
| Storage                  | 1         | 1.02%   |

