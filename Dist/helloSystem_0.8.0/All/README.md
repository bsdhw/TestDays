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

Total: 105

| Vendor        | Model                       | Form-Factor | Probe                                                     | Date         |
|---------------|-----------------------------|-------------|-----------------------------------------------------------|--------------|
| Toshiba       | TECRA Z40-C-12Z             | Notebook    | [149e5c3de3](https://bsd-hardware.info/?probe=149e5c3de3) | Nov 28, 2022 |
| ASUSTek       | PRIME Z390M-PLUS            | Desktop     | [7329e04c22](https://bsd-hardware.info/?probe=7329e04c22) | Nov 27, 2022 |
| Dell          | 0M017G A00                  | Desktop     | [3acaad9a7d](https://bsd-hardware.info/?probe=3acaad9a7d) | Nov 26, 2022 |
| Dell          | 009Y81 A01                  | All in one  | [75132e6886](https://bsd-hardware.info/?probe=75132e6886) | Nov 25, 2022 |
| Gigabyte      | P61-USB3-B3                 | Desktop     | [1ec1683acd](https://bsd-hardware.info/?probe=1ec1683acd) | Nov 21, 2022 |
| Gigabyte      | P61-USB3-B3                 | Desktop     | [5f442f0c65](https://bsd-hardware.info/?probe=5f442f0c65) | Nov 21, 2022 |
| Gigabyte      | H61M-S1                     | Desktop     | [2b851dbbc1](https://bsd-hardware.info/?probe=2b851dbbc1) | Nov 21, 2022 |
| Gigabyte      | 970A-D3P                    | Desktop     | [cced487ec5](https://bsd-hardware.info/?probe=cced487ec5) | Nov 21, 2022 |
| Gigabyte      | 970A-D3P                    | Desktop     | [c28a22ecb5](https://bsd-hardware.info/?probe=c28a22ecb5) | Nov 21, 2022 |
| ASUSTek       | P5KPL-VM-TWPC               | Desktop     | [6a5ff282a7](https://bsd-hardware.info/?probe=6a5ff282a7) | Nov 21, 2022 |
| Acer          | Aspire 5251                 | Notebook    | [046bc722cb](https://bsd-hardware.info/?probe=046bc722cb) | Nov 16, 2022 |
| HP            | 1998                        | Desktop     | [9239fe7437](https://bsd-hardware.info/?probe=9239fe7437) | Nov 15, 2022 |
| Dell          | Inspiron 3421               | Notebook    | [5c37012f33](https://bsd-hardware.info/?probe=5c37012f33) | Nov 10, 2022 |
| Gigabyte      | H270M-DS3H-CF               | Desktop     | [5784d8bed6](https://bsd-hardware.info/?probe=5784d8bed6) | Nov 04, 2022 |
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

![Arch](./images/pie_chart_bsd/os_arch.svg)


| Name  | Computers | Percent |
|-------|-----------|---------|
| amd64 | 90        | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart_bsd/os_de.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| helloDesktop | 86        | 95.56%  |
| GNOME        | 2         | 2.22%   |
| Window Maker | 1         | 1.11%   |
| Cinnamon     | 1         | 1.11%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart_bsd/os_display_server.svg)


| Name | Computers | Percent |
|------|-----------|---------|
| X11  | 90        | 100%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart_bsd/os_display_manager.svg)


| Name | Computers | Percent |
|------|-----------|---------|
| SLiM | 89        | 98.89%  |
| GDM  | 1         | 1.11%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart_bsd/os_lang.svg)


| Lang  | Computers | Percent |
|-------|-----------|---------|
| en_US | 87        | 96.67%  |
| ru_RU | 1         | 1.11%   |
| es_ES | 1         | 1.11%   |
| de_DE | 1         | 1.11%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart_bsd/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 89        | 98.89%  |
| BIOS | 1         | 1.11%   |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart_bsd/os_filesystem.svg)


| Type   | Computers | Percent |
|--------|-----------|---------|
| Cd9660 | 61        | 67.03%  |
| Zfs    | 30        | 32.97%  |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart_bsd/os_part_scheme.svg)


| Type | Computers | Percent |
|------|-----------|---------|
| GPT  | 89        | 98.89%  |
| MBR  | 1         | 1.11%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart_bsd/node_vendor.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| Dell                | 15        | 16.67%  |
| Hewlett-Packard     | 12        | 13.33%  |
| Lenovo              | 11        | 12.22%  |
| ASUSTek Computer    | 10        | 11.11%  |
| MSI                 | 4         | 4.44%   |
| Intel               | 4         | 4.44%   |
| Gigabyte Technology | 4         | 4.44%   |
| Apple               | 4         | 4.44%   |
| Acer                | 4         | 4.44%   |
| ASRock              | 3         | 3.33%   |
| TUXEDO              | 2         | 2.22%   |
| Toshiba             | 2         | 2.22%   |
| Timi                | 2         | 2.22%   |
| Sony                | 2         | 2.22%   |
| Pegatron            | 2         | 2.22%   |
| PCSTICK             | 1         | 1.11%   |
| Packard Bell        | 1         | 1.11%   |
| MACHINIST           | 1         | 1.11%   |
| Kraftway            | 1         | 1.11%   |
| HUAWEI              | 1         | 1.11%   |
| Google              | 1         | 1.11%   |
| Gateway             | 1         | 1.11%   |
| Biostar             | 1         | 1.11%   |
| AMD                 | 1         | 1.11%   |

Model
-----

Motherboard model

![Model](./images/pie_chart_bsd/node_model.svg)


| Name                                  | Computers | Percent |
|---------------------------------------|-----------|---------|
| MSI MS-7A38                           | 2         | 2.22%   |
| HP 250 G6 Notebook PC                 | 2         | 2.22%   |
| Apple MacBook5,2                      | 2         | 2.22%   |
| Unknown                               | 2         | 2.22%   |
| TUXEDO Pulse 14 Gen1                  | 1         | 1.11%   |
| TUXEDO Aura 15 Gen1                   | 1         | 1.11%   |
| Toshiba TECRA Z40-C-12Z               | 1         | 1.11%   |
| Toshiba Satellite S55t-B              | 1         | 1.11%   |
| Timi TM1701                           | 1         | 1.11%   |
| Timi RedmiBook Pro 15                 | 1         | 1.11%   |
| Sony VPCEB1J1E                        | 1         | 1.11%   |
| Sony VGN-AW21S_B                      | 1         | 1.11%   |
| Pegatron IPPPV-D3G                    | 1         | 1.11%   |
| Pegatron IPM41-D3                     | 1         | 1.11%   |
| Packard Bell EasyNote_MX52-B-071      | 1         | 1.11%   |
| MSI PS63 Modern 8M                    | 1         | 1.11%   |
| MSI MS-7C37                           | 1         | 1.11%   |
| MACHINIST X99-k9 V2.0                 | 1         | 1.11%   |
| Lenovo ThinkPad X270 W10DG 20K5S0BB00 | 1         | 1.11%   |
| Lenovo ThinkPad X250 20CLS23500       | 1         | 1.11%   |
| Lenovo ThinkPad X250 20CLS1WP01       | 1         | 1.11%   |
| Lenovo ThinkPad T440 20B7A0B7MS       | 1         | 1.11%   |
| Lenovo ThinkPad T420 4178A72          | 1         | 1.11%   |
| Lenovo ThinkCentre M93p 10AAA0WGUK    | 1         | 1.11%   |
| Lenovo ThinkCentre M910s 10MK0039US   | 1         | 1.11%   |
| Lenovo ThinkCentre M700 10GS          | 1         | 1.11%   |
| Lenovo Legion 5 15ARH05 82B5          | 1         | 1.11%   |
| Lenovo IdeaPad 3 15IGL05 82BU         | 1         | 1.11%   |
| Lenovo G480 20149                     | 1         | 1.11%   |
| Kraftway KW10T                        | 1         | 1.11%   |
| Intel NUC8i7BEK                       | 1         | 1.11%   |
| Intel NUC8i7BEH                       | 1         | 1.11%   |
| Intel MAHOBAY                         | 1         | 1.11%   |
| Intel DN2800MT AAG23738-600           | 1         | 1.11%   |
| HUAWEI BOD-WXX9                       | 1         | 1.11%   |
| HP Slim Desktop S01-aF1xxx            | 1         | 1.11%   |
| HP Pavilion g6                        | 1         | 1.11%   |
| HP Pavilion Desktop 590-p0xxx         | 1         | 1.11%   |
| HP OMEN by Laptop                     | 1         | 1.11%   |
| HP EliteDesk 800 G1 SFF               | 1         | 1.11%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart_bsd/node_model_family.svg)


| Name                  | Computers | Percent |
|-----------------------|-----------|---------|
| Lenovo ThinkPad       | 5         | 5.56%   |
| Dell Latitude         | 5         | 5.56%   |
| Dell Inspiron         | 5         | 5.56%   |
| Acer Aspire           | 4         | 4.44%   |
| Lenovo ThinkCentre    | 3         | 3.33%   |
| MSI MS-7A38           | 2         | 2.22%   |
| HP Pavilion           | 2         | 2.22%   |
| HP EliteDesk          | 2         | 2.22%   |
| HP EliteBook          | 2         | 2.22%   |
| HP 250                | 2         | 2.22%   |
| Dell Studio           | 2         | 2.22%   |
| Dell OptiPlex         | 2         | 2.22%   |
| Apple MacBook5        | 2         | 2.22%   |
| Unknown               | 2         | 2.22%   |
| TUXEDO Pulse          | 1         | 1.11%   |
| TUXEDO Aura           | 1         | 1.11%   |
| Toshiba TECRA         | 1         | 1.11%   |
| Toshiba Satellite     | 1         | 1.11%   |
| Timi TM1701           | 1         | 1.11%   |
| Timi RedmiBook        | 1         | 1.11%   |
| Sony VPCEB1J1E        | 1         | 1.11%   |
| Sony VGN-AW21S        | 1         | 1.11%   |
| Pegatron IPPPV-D3G    | 1         | 1.11%   |
| Pegatron IPM41-D3     | 1         | 1.11%   |
| Packard Bell EasyNote | 1         | 1.11%   |
| MSI PS63              | 1         | 1.11%   |
| MSI MS-7C37           | 1         | 1.11%   |
| MACHINIST X99-k9      | 1         | 1.11%   |
| Lenovo Legion         | 1         | 1.11%   |
| Lenovo IdeaPad        | 1         | 1.11%   |
| Lenovo G480           | 1         | 1.11%   |
| Kraftway KW10T        | 1         | 1.11%   |
| Intel NUC8i7BEK       | 1         | 1.11%   |
| Intel NUC8i7BEH       | 1         | 1.11%   |
| Intel MAHOBAY         | 1         | 1.11%   |
| Intel DN2800MT        | 1         | 1.11%   |
| HUAWEI BOD-WXX9       | 1         | 1.11%   |
| HP Slim               | 1         | 1.11%   |
| HP OMEN               | 1         | 1.11%   |
| HP Desktop            | 1         | 1.11%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart_bsd/node_year.svg)


| Year | Computers | Percent |
|------|-----------|---------|
| 2019 | 10        | 11.11%  |
| 2020 | 9         | 10%     |
| 2021 | 8         | 8.89%   |
| 2009 | 7         | 7.78%   |
| 2018 | 6         | 6.67%   |
| 2015 | 6         | 6.67%   |
| 2014 | 6         | 6.67%   |
| 2013 | 6         | 6.67%   |
| 2012 | 6         | 6.67%   |
| 2010 | 6         | 6.67%   |
| 2022 | 5         | 5.56%   |
| 2016 | 4         | 4.44%   |
| 2011 | 4         | 4.44%   |
| 2017 | 3         | 3.33%   |
| 2008 | 3         | 3.33%   |
| 2007 | 1         | 1.11%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart_bsd/node_formfactor.svg)


| Name       | Computers | Percent |
|------------|-----------|---------|
| Notebook   | 50        | 55.56%  |
| Desktop    | 36        | 40%     |
| Mini pc    | 2         | 2.22%   |
| All in one | 2         | 2.22%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart_bsd/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 89        | 98.89%  |
| Yes  | 1         | 1.11%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart_bsd/node_ram_total.svg)


| Size in GB  | Computers | Percent |
|-------------|-----------|---------|
| 8.01-16.0   | 29        | 32.22%  |
| 4.01-8.0    | 27        | 30%     |
| 16.01-24.0  | 22        | 24.44%  |
| 2.01-3.0    | 6         | 6.67%   |
| 32.01-64.0  | 3         | 3.33%   |
| 3.01-4.0    | 1         | 1.11%   |
| 24.01-32.0  | 1         | 1.11%   |
| 64.01-256.0 | 1         | 1.11%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart_bsd/node_ram_used.svg)


| Used GB  | Computers | Percent |
|----------|-----------|---------|
| 0.01-0.5 | 52        | 57.78%  |
| 0.51-1.0 | 26        | 28.89%  |
| 1.01-2.0 | 10        | 11.11%  |
| 4.01-8.0 | 1         | 1.11%   |
| 2.01-3.0 | 1         | 1.11%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart_bsd/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 59        | 64.84%  |
| 2      | 19        | 20.88%  |
| 0      | 6         | 6.59%   |
| 3      | 3         | 3.3%    |
| 5      | 2         | 2.2%    |
| 6      | 1         | 1.1%    |
| 4      | 1         | 1.1%    |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart_bsd/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 59        | 65.56%  |
| Yes       | 31        | 34.44%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart_bsd/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 79        | 87.78%  |
| No        | 11        | 12.22%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart_bsd/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 64        | 70.33%  |
| No        | 27        | 29.67%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart_bsd/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 46        | 51.11%  |
| No        | 44        | 48.89%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart_bsd/node_location.svg)


| Country      | Computers | Percent |
|--------------|-----------|---------|
| USA          | 10        | 11.11%  |
| Russia       | 10        | 11.11%  |
| Germany      | 8         | 8.89%   |
| Brazil       | 7         | 7.78%   |
| Taiwan       | 5         | 5.56%   |
| Spain        | 5         | 5.56%   |
| China        | 5         | 5.56%   |
| Ukraine      | 3         | 3.33%   |
| UK           | 3         | 3.33%   |
| Mexico       | 3         | 3.33%   |
| Italy        | 3         | 3.33%   |
| France       | 3         | 3.33%   |
| Canada       | 3         | 3.33%   |
| Poland       | 2         | 2.22%   |
| Norway       | 2         | 2.22%   |
| Hungary      | 2         | 2.22%   |
| Venezuela    | 1         | 1.11%   |
| UAE          | 1         | 1.11%   |
| Sweden       | 1         | 1.11%   |
| South Africa | 1         | 1.11%   |
| Slovenia     | 1         | 1.11%   |
| Slovakia     | 1         | 1.11%   |
| Serbia       | 1         | 1.11%   |
| Romania      | 1         | 1.11%   |
| Peru         | 1         | 1.11%   |
| Panama       | 1         | 1.11%   |
| India        | 1         | 1.11%   |
| Greece       | 1         | 1.11%   |
| Georgia      | 1         | 1.11%   |
| Belarus      | 1         | 1.11%   |
| Argentina    | 1         | 1.11%   |
| Albania      | 1         | 1.11%   |

City
----

Geographic location (city)

![City](./images/pie_chart_bsd/node_city.svg)


| City                 | Computers | Percent |
|----------------------|-----------|---------|
| Aquan                | 4         | 4.4%    |
| Moscow               | 3         | 3.3%    |
| Volgograd            | 2         | 2.2%    |
| Temple               | 2         | 2.2%    |
| Munich               | 2         | 2.2%    |
| LogroÃ±o           | 2         | 2.2%    |
| Zhengzhou            | 1         | 1.1%    |
| Yunlin               | 1         | 1.1%    |
| Willingboro          | 1         | 1.1%    |
| Weifang              | 1         | 1.1%    |
| Warendorf            | 1         | 1.1%    |
| Voronezh             | 1         | 1.1%    |
| Vladivostok          | 1         | 1.1%    |
| Vancouver            | 1         | 1.1%    |
| Ufa                  | 1         | 1.1%    |
| Trieste              | 1         | 1.1%    |
| Szeged               | 1         | 1.1%    |
| Surrey               | 1         | 1.1%    |
| Southminster         | 1         | 1.1%    |
| Seville              | 1         | 1.1%    |
| Sao Paulo            | 1         | 1.1%    |
| San Carlos del Zulia | 1         | 1.1%    |
| Salisbury            | 1         | 1.1%    |
| Rosignano Marittimo  | 1         | 1.1%    |
| Rio das Ostras       | 1         | 1.1%    |
| Rho                  | 1         | 1.1%    |
| Reinsvoll            | 1         | 1.1%    |
| Redondela            | 1         | 1.1%    |
| Perm                 | 1         | 1.1%    |
| Panama City          | 1         | 1.1%    |
| Ottawa               | 1         | 1.1%    |
| Orizaba              | 1         | 1.1%    |
| Odessa               | 1         | 1.1%    |
| Oakdale              | 1         | 1.1%    |
| Nesttun              | 1         | 1.1%    |
| Nanticoke            | 1         | 1.1%    |
| Monterrey            | 1         | 1.1%    |
| Mirepeix             | 1         | 1.1%    |
| Minsk                | 1         | 1.1%    |
| Mexico City          | 1         | 1.1%    |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart_bsd/drive_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 20        | 23     | 16.95%  |
| WDC                 | 16        | 18     | 13.56%  |
| Samsung Electronics | 16        | 18     | 13.56%  |
| Toshiba             | 10        | 10     | 8.47%   |
| Kingston            | 9         | 9      | 7.63%   |
| Hitachi             | 9         | 9      | 7.63%   |
| Intel               | 5         | 5      | 4.24%   |
| A-DATA Technology   | 3         | 3      | 2.54%   |
| SPCC                | 2         | 2      | 1.69%   |
| SK hynix            | 2         | 2      | 1.69%   |
| SanDisk             | 2         | 3      | 1.69%   |
| PNY                 | 2         | 2      | 1.69%   |
| OCZ                 | 2         | 2      | 1.69%   |
| KIOXIA              | 2         | 2      | 1.69%   |
| KingSpec            | 2         | 2      | 1.69%   |
| Fujitsu             | 2         | 2      | 1.69%   |
| Crucial             | 2         | 2      | 1.69%   |
| Transcend           | 1         | 1      | 0.85%   |
| SSSTC               | 1         | 1      | 0.85%   |
| Patriot             | 1         | 1      | 0.85%   |
| Lexar               | 1         | 2      | 0.85%   |
| LDLC                | 1         | 1      | 0.85%   |
| Intenso             | 1         | 1      | 0.85%   |
| Hewlett-Packard     | 1         | 1      | 0.85%   |
| GOODRAM             | 1         | 1      | 0.85%   |
| Gigabyte Technology | 1         | 1      | 0.85%   |
| FORESEE             | 1         | 1      | 0.85%   |
| Emtec               | 1         | 1      | 0.85%   |
| Corsair             | 1         | 1      | 0.85%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart_bsd/drive_model.svg)


| Model                                     | Computers | Percent |
|-------------------------------------------|-----------|---------|
| Seagate ST1000LM035-1RK172 1TB            | 3         | 2.38%   |
| Toshiba MQ01ABF050 500GB                  | 2         | 1.59%   |
| Toshiba MQ01ABD050 500GB                  | 2         | 1.59%   |
| Seagate ST1000LM024 HN-M101MBB 1TB        | 2         | 1.59%   |
| Samsung SSD 860 PRO 512GB                 | 2         | 1.59%   |
| Kingston SV300S37A120G 120GB              | 2         | 1.59%   |
| Kingston SA400S37120G 120GB               | 2         | 1.59%   |
| WDC WDS500G2X0C-00L350 500GB              | 1         | 0.79%   |
| WDC WDS500G2B0A 500GB                     | 1         | 0.79%   |
| WDC WDS500G1B0C-00S6U0 500GB              | 1         | 0.79%   |
| WDC WDS240G2G0B-00EPW0 240GB              | 1         | 0.79%   |
| WDC WDS100T2B0A-00SM50 1TB                | 1         | 0.79%   |
| WDC WDBNCE5000PNC 500GB                   | 1         | 0.79%   |
| WDC WD5000LPLX-08ZNTT0 500GB              | 1         | 0.79%   |
| WDC WD5000LPCX-60VHAT0 500GB              | 1         | 0.79%   |
| WDC WD5000AZLX-60K2TA1 500GB              | 1         | 0.79%   |
| WDC WD5000AVVS-63H0B1 500GB               | 1         | 0.79%   |
| WDC WD5000AAKS-00YGA0 500GB               | 1         | 0.79%   |
| WDC WD40NPZZ-00A9JT0 4TB                  | 1         | 0.79%   |
| WDC WD3003FZEX-00Z4SA0 3TB                | 1         | 0.79%   |
| WDC WD2500BEVT-75A23T0 250GB              | 1         | 0.79%   |
| WDC WD20EFRX-68EUZN0 2TB                  | 1         | 0.79%   |
| WDC WD10JPVX-75JC3T0 1TB                  | 1         | 0.79%   |
| WDC WD10JPVX-22JC3T0 1TB                  | 1         | 0.79%   |
| WDC PC SN530 SDBPNPZ-512G-1027 512GB      | 1         | 0.79%   |
| Transcend TS120GMTS420S 120GB             | 1         | 0.79%   |
| Toshiba TR200 480GB                       | 1         | 0.79%   |
| Toshiba Q300 240GB                        | 1         | 0.79%   |
| Toshiba MQ01ABD100 1TB                    | 1         | 0.79%   |
| Toshiba MK8034GSX 80GB                    | 1         | 0.79%   |
| Toshiba KSG60ZMV256G 256GB                | 1         | 0.79%   |
| Toshiba DT01ACA100 1TB                    | 1         | 0.79%   |
| SSSTC CL1-4D128 128GB                     | 1         | 0.79%   |
| SPCC Solid State Disk 56GB                | 1         | 0.79%   |
| SPCC Solid State Disk 512GB               | 1         | 0.79%   |
| SK hynix SKHynix_HFM512GDHTNI-87A0B 512GB | 1         | 0.79%   |
| SK hynix BC711 NVMe 256GB                 | 1         | 0.79%   |
| Seagate ST9500420AS 500GB                 | 1         | 0.79%   |
| Seagate ST9160821AS 160GB                 | 1         | 0.79%   |
| Seagate ST9120821AS 118GB                 | 1         | 0.79%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart_bsd/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 20        | 23     | 39.22%  |
| WDC                 | 11        | 11     | 21.57%  |
| Hitachi             | 9         | 9      | 17.65%  |
| Toshiba             | 7         | 7      | 13.73%  |
| Samsung Electronics | 2         | 2      | 3.92%   |
| Hewlett-Packard     | 1         | 1      | 1.96%   |
| Fujitsu             | 1         | 1      | 1.96%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart_bsd/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 10        | 10     | 20%     |
| Kingston            | 7         | 7      | 14%     |
| WDC                 | 4         | 4      | 8%      |
| Intel               | 4         | 4      | 8%      |
| Toshiba             | 3         | 3      | 6%      |
| SPCC                | 2         | 2      | 4%      |
| SanDisk             | 2         | 3      | 4%      |
| PNY                 | 2         | 2      | 4%      |
| OCZ                 | 2         | 2      | 4%      |
| KingSpec            | 2         | 2      | 4%      |
| A-DATA Technology   | 2         | 2      | 4%      |
| Transcend           | 1         | 1      | 2%      |
| Patriot             | 1         | 1      | 2%      |
| Lexar               | 1         | 1      | 2%      |
| Intenso             | 1         | 1      | 2%      |
| GOODRAM             | 1         | 1      | 2%      |
| Gigabyte Technology | 1         | 1      | 2%      |
| Fujitsu             | 1         | 1      | 2%      |
| FORESEE             | 1         | 1      | 2%      |
| Emtec               | 1         | 1      | 2%      |
| Crucial             | 1         | 1      | 2%      |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart_bsd/drive_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SSD  | 42        | 51     | 40.38%  |
| HDD  | 41        | 54     | 39.42%  |
| NVMe | 21        | 22     | 20.19%  |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart_bsd/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 75        | 105    | 78.13%  |
| NVMe | 21        | 22     | 21.88%  |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart_bsd/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 58        | 78     | 70.73%  |
| 0.51-1.0   | 16        | 18     | 19.51%  |
| 1.01-2.0   | 5         | 5      | 6.1%    |
| 3.01-4.0   | 2         | 2      | 2.44%   |
| 2.01-3.0   | 1         | 2      | 1.22%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart_bsd/drive_space_total.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| 1-20       | 54        | 60%     |
| 101-250    | 14        | 15.56%  |
| 251-500    | 12        | 13.33%  |
| 501-1000   | 5         | 5.56%   |
| 1001-2000  | 2         | 2.22%   |
| 21-50      | 1         | 1.11%   |
| 51-100     | 1         | 1.11%   |
| Unknown    | 1         | 1.11%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart_bsd/drive_space_used.svg)


| Used GB  | Computers | Percent |
|----------|-----------|---------|
| 1-20     | 85        | 94.44%  |
| 101-250  | 2         | 2.22%   |
| 501-1000 | 1         | 1.11%   |
| 51-100   | 1         | 1.11%   |
| Unknown  | 1         | 1.11%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart_bsd/drive_malfunc.svg)


| Model                                        | Computers | Drives | Percent |
|----------------------------------------------|-----------|--------|---------|
| WDC WD5000LPCX-60VHAT0 500GB                 | 1         | 1      | 5.26%   |
| WDC WD5000AVVS-63H0B1 500GB                  | 1         | 1      | 5.26%   |
| Toshiba MQ01ABF050 500GB                     | 1         | 1      | 5.26%   |
| Toshiba MQ01ABD100 1TB                       | 1         | 1      | 5.26%   |
| Toshiba MK8034GSX 80GB                       | 1         | 1      | 5.26%   |
| Seagate ST9160821AS 160GB                    | 1         | 1      | 5.26%   |
| Seagate ST500LT012-9WS142 500GB              | 1         | 1      | 5.26%   |
| Seagate ST500DM002-1BD142 500GB              | 1         | 1      | 5.26%   |
| Seagate ST320LT014-9YK142 320GB              | 1         | 1      | 5.26%   |
| Seagate ST1000LM024 HN-M101MBB 1TB           | 1         | 1      | 5.26%   |
| Samsung Electronics MZMPA128HMFU-000H1 128GB | 1         | 1      | 5.26%   |
| Samsung Electronics HD501LJ 500GB            | 1         | 1      | 5.26%   |
| OCZ VERTEX3 240GB                            | 1         | 1      | 5.26%   |
| Hitachi HTS727550A9E364 500GB                | 1         | 1      | 5.26%   |
| Hitachi HTS545050A7E380 500GB                | 1         | 1      | 5.26%   |
| Hitachi HTS545025B9SA02 250GB                | 1         | 1      | 5.26%   |
| Hitachi HTS541680J9SA00 80GB                 | 1         | 1      | 5.26%   |
| Hitachi HTS541612J9SA00 120GB                | 1         | 1      | 5.26%   |
| Fujitsu MHZ2160BH FFS G1 160GB               | 1         | 1      | 5.26%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart_bsd/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 5         | 5      | 26.32%  |
| Hitachi             | 5         | 5      | 26.32%  |
| Toshiba             | 3         | 3      | 15.79%  |
| WDC                 | 2         | 2      | 10.53%  |
| Samsung Electronics | 2         | 2      | 10.53%  |
| OCZ                 | 1         | 1      | 5.26%   |
| Fujitsu             | 1         | 1      | 5.26%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart_bsd/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 5         | 5      | 29.41%  |
| Hitachi             | 5         | 5      | 29.41%  |
| Toshiba             | 3         | 3      | 17.65%  |
| WDC                 | 2         | 2      | 11.76%  |
| Samsung Electronics | 1         | 1      | 5.88%   |
| Fujitsu             | 1         | 1      | 5.88%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart_bsd/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 15        | 17     | 88.24%  |
| SSD  | 2         | 2      | 11.76%  |

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
| Works    | 71        | 102    | 79.78%  |
| Malfunc  | 15        | 19     | 16.85%  |
| Detected | 3         | 6      | 3.37%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart_bsd/storage_vendor.svg)


| Vendor                         | Computers | Percent |
|--------------------------------|-----------|---------|
| Intel                          | 65        | 59.63%  |
| AMD                            | 14        | 12.84%  |
| Samsung Electronics            | 6         | 5.5%    |
| Nvidia                         | 4         | 3.67%   |
| SanDisk                        | 3         | 2.75%   |
| JMicron Technology             | 3         | 2.75%   |
| SK hynix                       | 2         | 1.83%   |
| Kingston Technology Company    | 2         | 1.83%   |
| Toshiba                        | 1         | 0.92%   |
| Solid State Storage Technology | 1         | 0.92%   |
| Silicon Motion                 | 1         | 0.92%   |
| Shenzhen Longsys Electronics   | 1         | 0.92%   |
| Realtek Semiconductor          | 1         | 0.92%   |
| Phison Electronics             | 1         | 0.92%   |
| Micron/Crucial Technology      | 1         | 0.92%   |
| Marvell Technology Group       | 1         | 0.92%   |
| KIOXIA                         | 1         | 0.92%   |
| ASMedia Technology             | 1         | 0.92%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart_bsd/storage_model.svg)


| Model                                                                                   | Computers | Percent |
|-----------------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 9         | 7.32%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                      | 6         | 4.88%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                                      | 5         | 4.07%   |
| Nvidia MCP79 AHCI Controller                                                            | 4         | 3.25%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 4         | 3.25%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                                      | 4         | 3.25%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 4         | 3.25%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller            | 4         | 3.25%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                                  | 3         | 2.44%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                       | 3         | 2.44%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 3         | 2.44%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                        | 3         | 2.44%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 3         | 2.44%   |
| Unknown                                                                                 | 3         | 2.44%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 2         | 1.63%   |
| Samsung NVMe SSD Controller 980                                                         | 2         | 1.63%   |
| JMicron JMB368 IDE controller                                                           | 2         | 1.63%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 2         | 1.63%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                                  | 2         | 1.63%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]                   | 2         | 1.63%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                          | 2         | 1.63%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                            | 2         | 1.63%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 2         | 1.63%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 2         | 1.63%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 2         | 1.63%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                                    | 2         | 1.63%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 2         | 1.63%   |
| Toshiba XG6 NVMe SSD Controller                                                         | 1         | 0.81%   |
| SK hynix Gold P31/PC711 NVMe Solid State Drive                                          | 1         | 0.81%   |
| SK hynix BC511                                                                          | 1         | 0.81%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                         | 1         | 0.81%   |
| Shenzhen Longsys SM2263EN/SM2263XT-based OEM SSD                                        | 1         | 0.81%   |
| SanDisk WD Blue SN550 NVMe SSD                                                          | 1         | 0.81%   |
| SanDisk WD Blue SN500 / PC SN520 NVMe SSD                                               | 1         | 0.81%   |
| SanDisk WD Black 2018/SN750 / PC SN720 NVMe SSD                                         | 1         | 0.81%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                           | 1         | 0.81%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                          | 1         | 0.81%   |
| Phison E12 NVMe Controller                                                              | 1         | 0.81%   |
| Micron/Crucial P2 NVMe PCIe SSD                                                         | 1         | 0.81%   |
| Marvell Group 88SE9235 PCIe 2.0 x2 4-port SATA 6 Gb/s Controller                        | 1         | 0.81%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart_bsd/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 69        | 63.3%   |
| NVMe | 21        | 19.27%  |
| IDE  | 16        | 14.68%  |
| RAID | 3         | 2.75%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart_bsd/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 75        | 83.33%  |
| AMD    | 15        | 16.67%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart_bsd/cpu_model.svg)


| Model                                       | Computers | Percent |
|---------------------------------------------|-----------|---------|
| Intel Core i7-8559U CPU @ 2.70GHz           | 2         | 2.22%   |
| Intel Core i7-6600U CPU @ 2.60GHz           | 2         | 2.22%   |
| Intel Core i5-6200U CPU @ 2.30GHz           | 2         | 2.22%   |
| Intel Core i5-5300U CPU @ 2.30GHz           | 2         | 2.22%   |
| Intel Core i5-5200U CPU @ 2.20GHz           | 2         | 2.22%   |
| Intel Core i5-3470 CPU @ 3.20GHz            | 2         | 2.22%   |
| Intel Core 2 Duo CPU P7450 @ 2.13GHz        | 2         | 2.22%   |
| AMD Ryzen 7 4800H with Radeon Graphics      | 2         | 2.22%   |
| Intel Xeon CPU E5-2630L v4 @ 1.80GHz        | 1         | 1.11%   |
| Intel Pentium Silver N5000 CPU @ 1.10GHz    | 1         | 1.11%   |
| Intel Pentium Silver J5040 CPU @ 2.00GHz    | 1         | 1.11%   |
| Intel Pentium Dual-Core CPU E6700 @ 3.20GHz | 1         | 1.11%   |
| Intel Pentium Dual-Core CPU E5700 @ 3.00GHz | 1         | 1.11%   |
| Intel Pentium Dual-Core CPU E5400 @ 2.70GHz | 1         | 1.11%   |
| Intel Pentium Dual-Core CPU E5200 @ 2.50GHz | 1         | 1.11%   |
| Intel Pentium CPU N3700 @ 1.60GHz           | 1         | 1.11%   |
| Intel Pentium CPU G4400 @ 3.30GHz           | 1         | 1.11%   |
| Intel Pentium CPU 4417U @ 2.30GHz           | 1         | 1.11%   |
| Intel CPU Version                           | 1         | 1.11%   |
| Intel Core i7-9700 CPU @ 3.00GHz            | 1         | 1.11%   |
| Intel Core i7-8565U CPU @ 1.80GHz           | 1         | 1.11%   |
| Intel Core i7-8550U CPU @ 1.80GHz           | 1         | 1.11%   |
| Intel Core i7-7700 CPU @ 3.60GHz            | 1         | 1.11%   |
| Intel Core i7-5500U CPU @ 2.40GHz           | 1         | 1.11%   |
| Intel Core i7-4810MQ CPU @ 2.80GHz          | 1         | 1.11%   |
| Intel Core i7-4790 CPU @ 3.60GHz            | 1         | 1.11%   |
| Intel Core i7-2677M CPU @ 1.80GHz           | 1         | 1.11%   |
| Intel Core i7-2620M CPU @ 2.70GHz           | 1         | 1.11%   |
| Intel Core i5-9400 CPU @ 2.90GHz            | 1         | 1.11%   |
| Intel Core i5-7200U CPU @ 2.50GHz           | 1         | 1.11%   |
| Intel Core i5-6500 CPU @ 3.20GHz            | 1         | 1.11%   |
| Intel Core i5-6440HQ CPU @ 2.60GHz          | 1         | 1.11%   |
| Intel Core i5-6300U CPU @ 2.40GHz           | 1         | 1.11%   |
| Intel Core i5-6300HQ CPU @ 2.30GHz          | 1         | 1.11%   |
| Intel Core i5-4590 CPU @ 3.30GHz            | 1         | 1.11%   |
| Intel Core i5-4570T CPU @ 2.90GHz           | 1         | 1.11%   |
| Intel Core i5-4310U CPU @ 2.00GHz           | 1         | 1.11%   |
| Intel Core i5-4300U CPU @ 1.90GHz           | 1         | 1.11%   |
| Intel Core i5-2540M CPU @ 2.60GHz           | 1         | 1.11%   |
| Intel Core i5-2520M CPU @ 2.50GHz           | 1         | 1.11%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart_bsd/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 21        | 23.33%  |
| Intel Core i7           | 13        | 14.44%  |
| Intel Core i3           | 9         | 10%     |
| Intel Core 2 Duo        | 7         | 7.78%   |
| Other                   | 5         | 5.56%   |
| Intel Atom              | 5         | 5.56%   |
| Intel Pentium Dual-Core | 4         | 4.44%   |
| Intel Celeron           | 4         | 4.44%   |
| AMD Ryzen 5             | 4         | 4.44%   |
| Intel Pentium           | 3         | 3.33%   |
| AMD Ryzen 7             | 3         | 3.33%   |
| Intel Pentium Silver    | 2         | 2.22%   |
| Intel Xeon              | 1         | 1.11%   |
| Intel Core 2 Quad       | 1         | 1.11%   |
| Intel Core 2            | 1         | 1.11%   |
| AMD V120                | 1         | 1.11%   |
| AMD Ryzen 9             | 1         | 1.11%   |
| AMD Ryzen 5 PRO         | 1         | 1.11%   |
| AMD Phenom II X4        | 1         | 1.11%   |
| AMD FX                  | 1         | 1.11%   |
| AMD Athlon 64 X2        | 1         | 1.11%   |
| AMD A8                  | 1         | 1.11%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart_bsd/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 38        | 42.22%  |
| 4       | 27        | 30%     |
| Unknown | 7         | 7.78%   |
| 8       | 5         | 5.56%   |
| 12      | 3         | 3.33%   |
| 6       | 3         | 3.33%   |
| 1       | 3         | 3.33%   |
| 16      | 2         | 2.22%   |
| 24      | 1         | 1.11%   |
| 10      | 1         | 1.11%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart_bsd/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 86        | 95.56%  |
| 2      | 4         | 4.44%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart_bsd/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 42        | 46.67%  |
| 1       | 41        | 45.56%  |
| Unknown | 7         | 7.78%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart_bsd/cpu_microarch.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| Penryn        | 11        | 12.22%  |
| KabyLake      | 11        | 12.22%  |
| Skylake       | 9         | 10%     |
| SandyBridge   | 7         | 7.78%   |
| Broadwell     | 7         | 7.78%   |
| Haswell       | 6         | 6.67%   |
| Zen 2         | 5         | 5.56%   |
| Silvermont    | 5         | 5.56%   |
| IvyBridge     | 4         | 4.44%   |
| Goldmont plus | 3         | 3.33%   |
| Bonnell       | 3         | 3.33%   |
| Zen+          | 2         | 2.22%   |
| TigerLake     | 2         | 2.22%   |
| K10           | 2         | 2.22%   |
| Core          | 2         | 2.22%   |
| CometLake     | 2         | 2.22%   |
| Unknown       | 2         | 2.22%   |
| Zen 3         | 1         | 1.11%   |
| Zen           | 1         | 1.11%   |
| Westmere      | 1         | 1.11%   |
| Piledriver    | 1         | 1.11%   |
| Nehalem       | 1         | 1.11%   |
| K8 Hammer     | 1         | 1.11%   |
| Excavator     | 1         | 1.11%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart_bsd/gpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 57        | 55.34%  |
| Nvidia | 29        | 28.16%  |
| AMD    | 17        | 16.5%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart_bsd/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel HD Graphics 5500                                                                   | 6         | 5.83%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 6         | 5.83%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 5         | 4.85%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 3         | 2.91%   |
| Intel HD Graphics 530                                                                    | 3         | 2.91%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 3         | 2.91%   |
| AMD Renoir                                                                               | 3         | 2.91%   |
| Nvidia TU116 [GeForce GTX 1660]                                                          | 2         | 1.94%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 2         | 1.94%   |
| Nvidia C79 [GeForce 9400M G]                                                             | 2         | 1.94%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 2         | 1.94%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 2         | 1.94%   |
| Intel HD Graphics 620                                                                    | 2         | 1.94%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 2         | 1.94%   |
| Intel GeminiLake [UHD Graphics 605]                                                      | 2         | 1.94%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                                 | 2         | 1.94%   |
| Intel CoffeeLake-U GT3e [Iris Plus Graphics 655]                                         | 2         | 1.94%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 2         | 1.94%   |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller                  | 2         | 1.94%   |
| Nvidia TU117M [GeForce MX450]                                                            | 1         | 0.97%   |
| Nvidia TU117M                                                                            | 1         | 0.97%   |
| Nvidia TU116 [GeForce GTX 1660 Ti]                                                       | 1         | 0.97%   |
| Nvidia TU116 [GeForce GTX 1660 SUPER]                                                    | 1         | 0.97%   |
| Nvidia GT218 [GeForce 210]                                                               | 1         | 0.97%   |
| Nvidia GT215 [GeForce GT 240]                                                            | 1         | 0.97%   |
| Nvidia GP108M [GeForce MX150]                                                            | 1         | 0.97%   |
| Nvidia GP108 [GeForce GT 1030]                                                           | 1         | 0.97%   |
| Nvidia GM206 [GeForce GTX 950]                                                           | 1         | 0.97%   |
| Nvidia GM108M [GeForce MX110]                                                            | 1         | 0.97%   |
| Nvidia GM107M [GeForce GTX 950M]                                                         | 1         | 0.97%   |
| Nvidia GK104 [GeForce GTX 760]                                                           | 1         | 0.97%   |
| Nvidia GF119M [Quadro NVS 4200M]                                                         | 1         | 0.97%   |
| Nvidia GF119 [GeForce GT 620 OEM]                                                        | 1         | 0.97%   |
| Nvidia GF108M [GeForce 610M]                                                             | 1         | 0.97%   |
| Nvidia GF108 [GeForce GT 630]                                                            | 1         | 0.97%   |
| Nvidia GF108 [GeForce GT 440]                                                            | 1         | 0.97%   |
| Nvidia G96CM [GeForce 9600M GT]                                                          | 1         | 0.97%   |
| Nvidia G96C [GeForce 9500 GT]                                                            | 1         | 0.97%   |
| Nvidia G84 [GeForce 8600 GTS]                                                            | 1         | 0.97%   |
| Nvidia G73 [GeForce 7600 GS]                                                             | 1         | 0.97%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart_bsd/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 42        | 46.67%  |
| 1 x Nvidia     | 20        | 22.22%  |
| 1 x AMD        | 12        | 13.33%  |
| Intel + Nvidia | 8         | 8.89%   |
| Intel + AMD    | 4         | 4.44%   |
| 2 x Intel      | 3         | 3.33%   |
| AMD + Nvidia   | 1         | 1.11%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart_bsd/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 67        | 74.44%  |
| Proprietary | 17        | 18.89%  |
| Unknown     | 6         | 6.67%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart_bsd/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 66        | 73.33%  |
| 0.01-0.5   | 9         | 10%     |
| 1.01-2.0   | 5         | 5.56%   |
| 5.01-6.0   | 4         | 4.44%   |
| 0.51-1.0   | 3         | 3.33%   |
| 3.01-4.0   | 2         | 2.22%   |
| 7.01-8.0   | 1         | 1.11%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart_bsd/mon_vendor.svg)


| Vendor               | Computers | Percent |
|----------------------|-----------|---------|
| LG Display           | 12        | 15.38%  |
| AU Optronics         | 9         | 11.54%  |
| Dell                 | 6         | 7.69%   |
| Chimei Innolux       | 6         | 7.69%   |
| Samsung Electronics  | 5         | 6.41%   |
| BOE                  | 5         | 6.41%   |
| Apple                | 5         | 6.41%   |
| Goldstar             | 4         | 5.13%   |
| MSI                  | 3         | 3.85%   |
| Hewlett-Packard      | 3         | 3.85%   |
| Acer                 | 3         | 3.85%   |
| Philips              | 2         | 2.56%   |
| BenQ                 | 2         | 2.56%   |
| AOC                  | 2         | 2.56%   |
| Vizio                | 1         | 1.28%   |
| Toshiba              | 1         | 1.28%   |
| TMX                  | 1         | 1.28%   |
| Nvidia               | 1         | 1.28%   |
| LG Philips           | 1         | 1.28%   |
| Insignia             | 1         | 1.28%   |
| Iiyama               | 1         | 1.28%   |
| HannStar             | 1         | 1.28%   |
| Fujitsu Siemens      | 1         | 1.28%   |
| CPT                  | 1         | 1.28%   |
| Ancor Communications | 1         | 1.28%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart_bsd/mon_model.svg)


| Model                                                                 | Computers | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| MSI G32C4 MSI3DA6 1920x1080 700x390mm 31.5-inch                       | 2         | 2.53%   |
| LG Display LCD Monitor LGD0484 1366x768 340x190mm 15.3-inch           | 2         | 2.53%   |
| Apple Color LCD APP9C5C 1280x800 290x180mm 13.4-inch                  | 2         | 2.53%   |
| Acer G227HQL ACR03DE 1920x1080 480x270mm 21.7-inch                    | 2         | 2.53%   |
| Vizio D43-D2 VIZ1004 1920x1080 930x520mm 41.9-inch                    | 1         | 1.27%   |
| Toshiba TV TSB0110 1920x1080 1110x620mm 50.1-inch                     | 1         | 1.27%   |
| TMX LCD Monitor TMX1560 3200x2000 340x210mm 15.7-inch                 | 1         | 1.27%   |
| Samsung Electronics SyncMaster SAM0601 1600x900                       | 1         | 1.27%   |
| Samsung Electronics SyncMaster SAM05FF 1600x900 440x250mm 19.9-inch   | 1         | 1.27%   |
| Samsung Electronics SyncMaster SAM05C5 1920x1080                      | 1         | 1.27%   |
| Samsung Electronics SMS23A550H SAM07C9 1920x1080 510x290mm 23.1-inch  | 1         | 1.27%   |
| Samsung Electronics LCD Monitor SEC4149 1366x768 280x170mm 12.9-inch  | 1         | 1.27%   |
| Samsung Electronics LCD Monitor SDC4C48 1920x1080 340x190mm 15.3-inch | 1         | 1.27%   |
| Philips PHL 223V5 PHLC0CF 1920x1080 480x270mm 21.7-inch               | 1         | 1.27%   |
| Philips 237EQPH PHLC091 1920x1080 510x290mm 23.1-inch                 | 1         | 1.27%   |
| Nvidia LCD Monitor NVD0200 1920x1080 320x180mm 14.5-inch              | 1         | 1.27%   |
| MSI MAG342CQRV MSI3DB6 3440x1440 790x330mm 33.7-inch                  | 1         | 1.27%   |
| LG Philips LCD Monitor LPLE300 1280x800 330x210mm 15.4-inch           | 1         | 1.27%   |
| LG Display LCD Monitor LGD0569 1920x1080 310x170mm 13.9-inch          | 1         | 1.27%   |
| LG Display LCD Monitor LGD0532 1920x1080 340x190mm 15.3-inch          | 1         | 1.27%   |
| LG Display LCD Monitor LGD0470 1920x1080 350x190mm 15.7-inch          | 1         | 1.27%   |
| LG Display LCD Monitor LGD046F 1920x1080 340x190mm 15.3-inch          | 1         | 1.27%   |
| LG Display LCD Monitor LGD0435 1600x900 310x170mm 13.9-inch           | 1         | 1.27%   |
| LG Display LCD Monitor LGD03EE 1366x768 280x160mm 12.7-inch           | 1         | 1.27%   |
| LG Display LCD Monitor LGD03B7 1366x768 310x170mm 13.9-inch           | 1         | 1.27%   |
| LG Display LCD Monitor LGD0384 1366x768 340x190mm 15.3-inch           | 1         | 1.27%   |
| LG Display LCD Monitor LGD02DC 1366x768 340x190mm 15.3-inch           | 1         | 1.27%   |
| LG Display LCD Monitor LGD021D 1600x900 380x210mm 17.1-inch           | 1         | 1.27%   |
| Insignia 32DR310NA17 BBY3253 1680x1050 700x390mm 31.5-inch            | 1         | 1.27%   |
| Iiyama PLE2407HDS IVM560D 1920x1080 520x300mm 23.6-inch               | 1         | 1.27%   |
| Hewlett-Packard LCD Monitor HWP26A4 1440x900 410x260mm 19.1-inch      | 1         | 1.27%   |
| Hewlett-Packard LCD Monitor HPN351A 1920x1080 700x390mm 31.5-inch     | 1         | 1.27%   |
| Hewlett-Packard 27xi HWP3038 1920x1080 600x340mm 27.2-inch            | 1         | 1.27%   |
| HannStar LCD Monitor HSD03E9 1024x600 220x130mm 10.1-inch             | 1         | 1.27%   |
| Goldstar LG ULTRAWIDE GSM5AE2 3440x1440 800x340mm 34.2-inch           | 1         | 1.27%   |
| Goldstar L1918S GSM4B31 1280x1024 380x300mm 19.1-inch                 | 1         | 1.27%   |
| Goldstar 2D FHD LG TV GSM59C6 1920x1080 510x290mm 23.1-inch           | 1         | 1.27%   |
| Goldstar 22MP55 GSM5A24 1920x1080 480x270mm 21.7-inch                 | 1         | 1.27%   |
| Fujitsu Siemens XE17-4 FUS0674 1280x1024 340x270mm 17.1-inch          | 1         | 1.27%   |
| Dell S2316H DELD07E 1920x1080 510x290mm 23.1-inch                     | 1         | 1.27%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart_bsd/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 36        | 46.75%  |
| 1366x768 (WXGA)    | 17        | 22.08%  |
| 1680x1050 (WSXGA+) | 5         | 6.49%   |
| 1600x900 (HD+)     | 5         | 6.49%   |
| 1280x800 (WXGA)    | 5         | 6.49%   |
| 3440x1440          | 2         | 2.6%    |
| 1280x1024 (SXGA)   | 2         | 2.6%    |
| 3200x2000          | 1         | 1.3%    |
| 2560x1440 (QHD)    | 1         | 1.3%    |
| 1920x1200 (WUXGA)  | 1         | 1.3%    |
| 1440x900 (WXGA+)   | 1         | 1.3%    |
| 1024x600           | 1         | 1.3%    |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart_bsd/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 21        | 26.58%  |
| 13      | 14        | 17.72%  |
| 23      | 6         | 7.59%   |
| 21      | 5         | 6.33%   |
| 12      | 5         | 6.33%   |
| 31      | 4         | 5.06%   |
| 24      | 4         | 5.06%   |
| 19      | 3         | 3.8%    |
| 22      | 2         | 2.53%   |
| 20      | 2         | 2.53%   |
| 17      | 2         | 2.53%   |
| 10      | 2         | 2.53%   |
| Unknown | 2         | 2.53%   |
| 50      | 1         | 1.27%   |
| 41      | 1         | 1.27%   |
| 34      | 1         | 1.27%   |
| 33      | 1         | 1.27%   |
| 27      | 1         | 1.27%   |
| 18      | 1         | 1.27%   |
| 14      | 1         | 1.27%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart_bsd/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 31        | 39.24%  |
| 201-300     | 13        | 16.46%  |
| 401-500     | 12        | 15.19%  |
| 501-600     | 11        | 13.92%  |
| 601-700     | 4         | 5.06%   |
| 701-800     | 2         | 2.53%   |
| 351-400     | 2         | 2.53%   |
| Unknown     | 2         | 2.53%   |
| 1001-1500   | 1         | 1.27%   |
| 901-1000    | 1         | 1.27%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart_bsd/mon_ratio.svg)


| Ratio | Computers | Percent |
|-------|-----------|---------|
| 16/9  | 60        | 77.92%  |
| 16/10 | 13        | 16.88%  |
| 5/4   | 2         | 2.6%    |
| 21/9  | 2         | 2.6%    |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart_bsd/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 91-100         | 17        | 21.52%  |
| 201-250        | 16        | 20.25%  |
| 81-90          | 13        | 16.46%  |
| 351-500        | 6         | 7.59%   |
| 151-200        | 5         | 6.33%   |
| 61-70          | 4         | 5.06%   |
| 71-80          | 3         | 3.8%    |
| 101-110        | 3         | 3.8%    |
| 41-50          | 2         | 2.53%   |
| 141-150        | 2         | 2.53%   |
| Unknown        | 2         | 2.53%   |
| More than 1000 | 1         | 1.27%   |
| 301-350        | 1         | 1.27%   |
| 251-300        | 1         | 1.27%   |
| 121-130        | 1         | 1.27%   |
| 111-120        | 1         | 1.27%   |
| 501-1000       | 1         | 1.27%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart_bsd/mon_density.svg)


| Density | Computers | Percent |
|---------|-----------|---------|
| 101-120 | 27        | 34.18%  |
| 51-100  | 25        | 31.65%  |
| 121-160 | 20        | 25.32%  |
| 161-240 | 4         | 5.06%   |
| Unknown | 2         | 2.53%   |
| 1-50    | 1         | 1.27%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart_bsd/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 77        | 85.56%  |
| 0     | 10        | 11.11%  |
| 2     | 3         | 3.33%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart_bsd/net_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Intel                    | 47        | 36.43%  |
| Realtek Semiconductor    | 41        | 31.78%  |
| Qualcomm Atheros         | 16        | 12.4%   |
| Broadcom                 | 9         | 6.98%   |
| Nvidia                   | 4         | 3.1%    |
| Ralink Technology        | 2         | 1.55%   |
| Marvell Technology Group | 2         | 1.55%   |
| Sierra Wireless          | 1         | 0.78%   |
| Samsung Electronics      | 1         | 0.78%   |
| Ralink                   | 1         | 0.78%   |
| IMC Networks             | 1         | 0.78%   |
| Huawei Technologies      | 1         | 0.78%   |
| Edimax Technology        | 1         | 0.78%   |
| D-Link System            | 1         | 0.78%   |
| ASUSTek Computer         | 1         | 0.78%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart_bsd/net_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 34        | 22.82%  |
| Intel Wireless 7265                                               | 7         | 4.7%    |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 6         | 4.03%   |
| Intel Wi-Fi 6 AX200                                               | 5         | 3.36%   |
| Nvidia MCP79 Ethernet                                             | 4         | 2.68%   |
| Intel Wireless 8265 / 8275                                        | 4         | 2.68%   |
| Intel Ethernet Connection I217-LM                                 | 4         | 2.68%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 3         | 2.01%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 3         | 2.01%   |
| Intel Wireless 8260                                               | 3         | 2.01%   |
| Intel Ethernet Connection (3) I218-LM                             | 3         | 2.01%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 3         | 2.01%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller            | 3         | 2.01%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                           | 2         | 1.34%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 2         | 1.34%   |
| Qualcomm Atheros AR8132 Fast Ethernet                             | 2         | 1.34%   |
| Intel Wireless 3160                                               | 2         | 1.34%   |
| Intel WiFi Link 5100                                              | 2         | 1.34%   |
| Intel Wi-Fi 6 AX201                                               | 2         | 1.34%   |
| Intel Ethernet Connection I219-LM                                 | 2         | 1.34%   |
| Intel Ethernet Connection I218-LM                                 | 2         | 1.34%   |
| Intel Ethernet Connection (6) I219-V                              | 2         | 1.34%   |
| Intel Ethernet Connection (2) I219-LM                             | 2         | 1.34%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 2         | 1.34%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 2         | 1.34%   |
| Intel 82574L Gigabit Network Connection                           | 2         | 1.34%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 2         | 1.34%   |
| Sierra Wireless EM7455                                            | 1         | 0.67%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)       | 1         | 0.67%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 1         | 0.67%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                        | 1         | 0.67%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 1         | 0.67%   |
| Ralink RT5370 Wireless Adapter                                    | 1         | 0.67%   |
| Ralink RT2870/RT3070 Wireless Adapter                             | 1         | 0.67%   |
| Ralink RT5390 Wireless 802.11n 1T/1R PCIe                         | 1         | 0.67%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 1         | 0.67%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 1         | 0.67%   |
| Qualcomm Atheros Attansic L1 Gigabit Ethernet                     | 1         | 0.67%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)    | 1         | 0.67%   |
| Qualcomm Atheros AR8162 Fast Ethernet                             | 1         | 0.67%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart_bsd/net_wireless_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Intel                 | 34        | 50%     |
| Qualcomm Atheros      | 13        | 19.12%  |
| Realtek Semiconductor | 7         | 10.29%  |
| Broadcom              | 6         | 8.82%   |
| Ralink Technology     | 2         | 2.94%   |
| Sierra Wireless       | 1         | 1.47%   |
| Ralink                | 1         | 1.47%   |
| IMC Networks          | 1         | 1.47%   |
| Edimax Technology     | 1         | 1.47%   |
| D-Link System         | 1         | 1.47%   |
| ASUSTek Computer      | 1         | 1.47%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart_bsd/net_wireless_model.svg)


| Model                                                                       | Computers | Percent |
|-----------------------------------------------------------------------------|-----------|---------|
| Intel Wireless 7265                                                         | 7         | 10.29%  |
| Qualcomm Atheros AR9485 Wireless Network Adapter                            | 6         | 8.82%   |
| Intel Wi-Fi 6 AX200                                                         | 5         | 7.35%   |
| Intel Wireless 8265 / 8275                                                  | 4         | 5.88%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                    | 3         | 4.41%   |
| Intel Wireless 8260                                                         | 3         | 4.41%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller                      | 3         | 4.41%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                                     | 2         | 2.94%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)              | 2         | 2.94%   |
| Intel Wireless 3160                                                         | 2         | 2.94%   |
| Intel WiFi Link 5100                                                        | 2         | 2.94%   |
| Intel Wi-Fi 6 AX201                                                         | 2         | 2.94%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                            | 2         | 2.94%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                    | 2         | 2.94%   |
| Sierra Wireless EM7455                                                      | 1         | 1.47%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                             | 1         | 1.47%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                                  | 1         | 1.47%   |
| Ralink RT5370 Wireless Adapter                                              | 1         | 1.47%   |
| Ralink RT2870/RT3070 Wireless Adapter                                       | 1         | 1.47%   |
| Ralink RT5390 Wireless 802.11n 1T/1R PCIe                                   | 1         | 1.47%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                  | 1         | 1.47%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                  | 1         | 1.47%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)              | 1         | 1.47%   |
| Qualcomm Atheros AR5212 802.11abg NIC                                       | 1         | 1.47%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express)     | 1         | 1.47%   |
| Intel Wireless 7260                                                         | 1         | 1.47%   |
| Intel Tiger Lake PCH CNVi WiFi                                              | 1         | 1.47%   |
| Intel Gemini Lake PCH CNVi WiFi                                             | 1         | 1.47%   |
| Intel Centrino Ultimate-N 6300                                              | 1         | 1.47%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                                | 1         | 1.47%   |
| IMC Networks Realtek RTL8191SU Wireless LAN 802.11n USB 2.0 Network Adapter | 1         | 1.47%   |
| Edimax EW-7612UAn V2 802.11n Wireless Adapter [Realtek RTL8192CU]           | 1         | 1.47%   |
| D-Link System DWA-125 Wireless N 150 Adapter(rev.A1) [Ralink RT3070]        | 1         | 1.47%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                          | 1         | 1.47%   |
| Broadcom BCM43224 802.11a/b/g/n                                             | 1         | 1.47%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                         | 1         | 1.47%   |
| ASUS N10 Nano 802.11n Network Adapter [Realtek RTL8192CU]                   | 1         | 1.47%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart_bsd/net_ethernet_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 38        | 48.1%   |
| Intel                    | 26        | 32.91%  |
| Qualcomm Atheros         | 5         | 6.33%   |
| Nvidia                   | 4         | 5.06%   |
| Broadcom                 | 3         | 3.8%    |
| Marvell Technology Group | 2         | 2.53%   |
| Samsung Electronics      | 1         | 1.27%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart_bsd/net_ethernet_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller              | 34        | 42.5%   |
| Nvidia MCP79 Ethernet                                                          | 4         | 5%      |
| Intel Ethernet Connection I217-LM                                              | 4         | 5%      |
| Realtek RTL810xE PCI Express Fast Ethernet controller                          | 3         | 3.75%   |
| Intel Ethernet Connection (3) I218-LM                                          | 3         | 3.75%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                          | 3         | 3.75%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                          | 2         | 2.5%    |
| Intel Ethernet Connection I219-LM                                              | 2         | 2.5%    |
| Intel Ethernet Connection I218-LM                                              | 2         | 2.5%    |
| Intel Ethernet Connection (6) I219-V                                           | 2         | 2.5%    |
| Intel Ethernet Connection (2) I219-LM                                          | 2         | 2.5%    |
| Intel 82574L Gigabit Network Connection                                        | 2         | 2.5%    |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                                | 2         | 2.5%    |
| Samsung GT-I9070 (network tethering, USB debugging enabled)                    | 1         | 1.25%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                          | 1         | 1.25%   |
| Qualcomm Atheros Attansic L1 Gigabit Ethernet                                  | 1         | 1.25%   |
| Qualcomm Atheros AR8162 Fast Ethernet                                          | 1         | 1.25%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                                     | 1         | 1.25%   |
| Marvell Group Yukon Optima 88E8059 [PCIe Gigabit Ethernet Controller with AVB] | 1         | 1.25%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller                        | 1         | 1.25%   |
| Intel Ethernet Controller I225-V                                               | 1         | 1.25%   |
| Intel Ethernet Connection I219-V                                               | 1         | 1.25%   |
| Intel Ethernet Connection (7) I219-V                                           | 1         | 1.25%   |
| Intel Ethernet Connection (4) I219-LM                                          | 1         | 1.25%   |
| Intel Ethernet Connection (2) I219-V                                           | 1         | 1.25%   |
| Intel Ethernet Connection (14) I219-LM                                         | 1         | 1.25%   |
| Intel Ethernet Connection (11) I219-LM                                         | 1         | 1.25%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                                | 1         | 1.25%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart_bsd/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 79        | 55.24%  |
| WiFi     | 63        | 44.06%  |
| Modem    | 1         | 0.7%    |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart_bsd/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 59        | 62.11%  |
| WiFi     | 36        | 37.89%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart_bsd/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 49        | 54.44%  |
| 1     | 40        | 44.44%  |
| 0     | 1         | 1.11%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart_bsd/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 84        | 93.33%  |
| Yes  | 6         | 6.67%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart_bsd/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 26        | 55.32%  |
| Apple                           | 5         | 10.64%  |
| Realtek Semiconductor           | 3         | 6.38%   |
| Lite-On Technology              | 2         | 4.26%   |
| IMC Networks                    | 2         | 4.26%   |
| Cambridge Silicon Radio         | 2         | 4.26%   |
| Qualcomm Atheros Communications | 1         | 2.13%   |
| Integrated System Solution      | 1         | 2.13%   |
| Hewlett-Packard                 | 1         | 2.13%   |
| Broadcom                        | 1         | 2.13%   |
| Bluetooth Device                | 1         | 2.13%   |
| ASUSTek Computer                | 1         | 2.13%   |
| Alps Electric                   | 1         | 2.13%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart_bsd/bt_model.svg)


| Model                                                    | Computers | Percent |
|----------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                       | 14        | 28.57%  |
| Intel AX200 Bluetooth                                    | 4         | 8.16%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)           | 3         | 6.12%   |
| Intel AX201 Bluetooth                                    | 3         | 6.12%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                     | 3         | 6.12%   |
| Realtek  Bluetooth 4.2 Adapter                           | 2         | 4.08%   |
| Intel Wireless-AC 3168 Bluetooth                         | 2         | 4.08%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)      | 2         | 4.08%   |
| Apple Built-in iSight (no firmware loaded)               | 2         | 4.08%   |
| Realtek Dell Wireless 1801 Bluetooth 4.0 LE              | 1         | 2.04%   |
| Qualcomm Atheros Dell Wireless 1703 Bluetooth            | 1         | 2.04%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth               | 1         | 2.04%   |
| Lite-On Atheros AR3012 Bluetooth                         | 1         | 2.04%   |
| Integrated System Solution Bluetooth Device              | 1         | 2.04%   |
| IMC Networks Realtek Bluetooth Adapter                   | 1         | 2.04%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter        | 1         | 2.04%   |
| HP Broadcom 2070 Bluetooth Combo                         | 1         | 2.04%   |
| Broadcom BCM2045B (BDC-2.1)                              | 1         | 2.04%   |
| Bluetooth Device Silicon Wave Bluetooth Wireless Adapter | 1         | 2.04%   |
| ASUS BT-253 Bluetooth Adapter                            | 1         | 2.04%   |
| Apple Bluetooth Host Controller                          | 1         | 2.04%   |
| Apple Apple Broadcom Built-in Bluetooth                  | 1         | 2.04%   |
| Alps Electric BCM2046 Bluetooth Device                   | 1         | 2.04%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart_bsd/snd_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Intel               | 69        | 60%     |
| AMD                 | 18        | 15.65%  |
| Nvidia              | 17        | 14.78%  |
| C-Media Electronics | 4         | 3.48%   |
| Google              | 2         | 1.74%   |
| Yamaha              | 1         | 0.87%   |
| XMOS                | 1         | 0.87%   |
| Logitech            | 1         | 0.87%   |
| GN Netcom           | 1         | 0.87%   |
| Creative Technology | 1         | 0.87%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart_bsd/snd_model.svg)


| Model                                                                                             | Computers | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                                                   | 9         | 6.62%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 8         | 5.88%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 8         | 5.88%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 6         | 4.41%   |
| Intel Broadwell-U Audio Controller                                                                | 6         | 4.41%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 6         | 4.41%   |
| Nvidia TU116 High Definition Audio Controller                                                     | 4         | 2.94%   |
| Nvidia MCP79 High Definition Audio                                                                | 4         | 2.94%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 4         | 2.94%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 4         | 2.94%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 3         | 2.21%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 3         | 2.21%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 3         | 2.21%   |
| Intel 200 Series PCH HD Audio                                                                     | 3         | 2.21%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 3         | 2.21%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 3         | 2.21%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 3         | 2.21%   |
| Nvidia High Definition Audio Controller                                                           | 2         | 1.47%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 2         | 1.47%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 2         | 1.47%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 2         | 1.47%   |
| Intel Cannon Lake PCH cAVS                                                                        | 2         | 1.47%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 2         | 1.47%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 2         | 1.47%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                                  | 2         | 1.47%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 2         | 1.47%   |
| Intel 8 Series HD Audio Controller                                                                | 2         | 1.47%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 2         | 1.47%   |
| Google Pixel earbuds                                                                              | 2         | 1.47%   |
| C-Media Electronics Audio Adapter (Unitek Y-247A)                                                 | 2         | 1.47%   |
| AMD Starship/Matisse HD Audio Controller                                                          | 2         | 1.47%   |
| AMD FCH Azalia Controller                                                                         | 2         | 1.47%   |
| Unknown                                                                                           | 2         | 1.47%   |
| Yamaha Steinberg UR22mkII                                                                         | 1         | 0.74%   |
| XMOS iFi (by AMR) HD USB Audio                                                                    | 1         | 0.74%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 1         | 0.74%   |
| Nvidia GP108 High Definition Audio Controller                                                     | 1         | 0.74%   |
| Nvidia GM206 High Definition Audio Controller                                                     | 1         | 0.74%   |
| Nvidia GK104 HDMI Audio Controller                                                                | 1         | 0.74%   |
| Nvidia GF119 HDMI Audio Controller                                                                | 1         | 0.74%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart_bsd/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| SK hynix            | 21        | 18.92%  |
| Samsung Electronics | 17        | 15.32%  |
| Unknown             | 16        | 14.41%  |
| Kingston            | 15        | 13.51%  |
| Micron Technology   | 11        | 9.91%   |
| Crucial             | 5         | 4.5%    |
| Transcend           | 3         | 2.7%    |
| Nanya Technology    | 3         | 2.7%    |
| A-DATA Technology   | 3         | 2.7%    |
| Unknown             | 3         | 2.7%    |
| Smart               | 2         | 1.8%    |
| Ramaxel Technology  | 2         | 1.8%    |
| Corsair             | 2         | 1.8%    |
| Teikon              | 1         | 0.9%    |
| Team                | 1         | 0.9%    |
| Smart Brazil        | 1         | 0.9%    |
| Patriot             | 1         | 0.9%    |
| GLOWAY              | 1         | 0.9%    |
| GeIL                | 1         | 0.9%    |
| G.Skill             | 1         | 0.9%    |
| Elpida              | 1         | 0.9%    |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart_bsd/memory_model.svg)


| Model                                                  | Computers | Percent |
|--------------------------------------------------------|-----------|---------|
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s | 3         | 2.46%   |
| Unknown                                                | 3         | 2.46%   |
| Unknown RAM Module 2GB DIMM DDR2 800MT/s               | 2         | 1.64%   |
| Unknown RAM Module 1GB DIMM SDRAM                      | 2         | 1.64%   |
| Transcend RAM JM1333KLN-4G 4GB DIMM DDR3 1333MT/s      | 2         | 1.64%   |
| SK hynix RAM HMT41GU6BFR8A-PB 8GB DIMM DDR3 1600MT/s   | 2         | 1.64%   |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2400MT/s | 2         | 1.64%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s  | 2         | 1.64%   |
| Kingston RAM 99U5702-095.A00G 8GB DIMM DDR4 3200MT/s   | 2         | 1.64%   |
| Unknown RAM Module 4GB SODIMM DDR3 1333MT/s            | 1         | 0.82%   |
| Unknown RAM Module 4GB DIMM SDRAM                      | 1         | 0.82%   |
| Unknown RAM Module 4GB DIMM DDR3 1067MT/s              | 1         | 0.82%   |
| Unknown RAM Module 4GB DIMM 1333MT/s                   | 1         | 0.82%   |
| Unknown RAM Module 2GB SODIMM DDR3 1333MT/s            | 1         | 0.82%   |
| Unknown RAM Module 2GB SODIMM DDR3 1067MT/s            | 1         | 0.82%   |
| Unknown RAM Module 2GB SODIMM DDR3                     | 1         | 0.82%   |
| Unknown RAM Module 2GB SODIMM DDR2 800MT/s             | 1         | 0.82%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s             | 1         | 0.82%   |
| Unknown RAM Module 2GB SODIMM DDR2                     | 1         | 0.82%   |
| Unknown RAM Module 2GB DIMM SDRAM                      | 1         | 0.82%   |
| Unknown RAM Module 2GB DIMM DDR3 1066MT/s              | 1         | 0.82%   |
| Unknown RAM Module 2GB DIMM DDR2                       | 1         | 0.82%   |
| Unknown RAM Module 2GB DIMM 1333MT/s                   | 1         | 0.82%   |
| Unknown RAM Module 1GB SODIMM DDR2 800MT/s             | 1         | 0.82%   |
| Transcend RAM TS256MSK64V3N 2GB SODIMM DDR3 1333MT/s   | 1         | 0.82%   |
| Transcend RAM JM1333KLH-8G 8GB DIMM DDR3 1333MT/s      | 1         | 0.82%   |
| Teikon RAM TML251S6EFR8A-PBHC 4GB SODIMM DDR3 1600MT/s | 1         | 0.82%   |
| Team RAM Elite-13 4GB DIMM DDR3 667MT/s                | 1         | 0.82%   |
| Team RAM Elite-1 2GB DIMM DDR3 667MT/s                 | 1         | 0.82%   |
| Smart RAM SH564568FH8NZPHSCR 2GB SODIMM DDR3 1334MT/s  | 1         | 0.82%   |
| Smart RAM SH564568FH8NWPHSFR 2GB SODIMM DDR3 1333MT/s  | 1         | 0.82%   |
| Smart RAM SH564128FJ8NWRNSQR 4GB SODIMM DDR3 1600MT/s  | 1         | 0.82%   |
| Smart Brazil RAM Module 4GB Row Of Chips DDR4 2400MT/s | 1         | 0.82%   |
| SK hynix RAM Module 4GB SODIMM DDR4 2400MT/s           | 1         | 0.82%   |
| SK hynix RAM Module 2GB SODIMM DDR3 1067MT/s           | 1         | 0.82%   |
| SK hynix RAM HMT451U6AFR8C-PB 4GB DIMM DDR3 1600MT/s   | 1         | 0.82%   |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s | 1         | 0.82%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s | 1         | 0.82%   |
| SK hynix RAM HMT351S6EFR8C-PB 4GB SODIMM DDR3 1600MT/s | 1         | 0.82%   |
| SK hynix RAM HMT351S6EFR8A-PB 4GB SODIMM DDR3 1600MT/s | 1         | 0.82%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart_bsd/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR3    | 39        | 43.33%  |
| DDR4    | 36        | 40%     |
| DDR2    | 10        | 11.11%  |
| SDRAM   | 3         | 3.33%   |
| LPDDR3  | 1         | 1.11%   |
| Unknown | 1         | 1.11%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart_bsd/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 52        | 57.78%  |
| DIMM         | 34        | 37.78%  |
| Row Of Chips | 3         | 3.33%   |
| Unknown      | 1         | 1.11%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart_bsd/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 4096  | 40        | 37.74%  |
| 8192  | 27        | 25.47%  |
| 2048  | 25        | 23.58%  |
| 16384 | 11        | 10.38%  |
| 1024  | 3         | 2.83%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart_bsd/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 24        | 24.49%  |
| 2400    | 14        | 14.29%  |
| 1333    | 12        | 12.24%  |
| 3200    | 9         | 9.18%   |
| 2667    | 8         | 8.16%   |
| 2133    | 6         | 6.12%   |
| 800     | 6         | 6.12%   |
| Unknown | 6         | 6.12%   |
| 1067    | 3         | 3.06%   |
| 667     | 3         | 3.06%   |
| 2666    | 2         | 2.04%   |
| 1334    | 2         | 2.04%   |
| 2933    | 1         | 1.02%   |
| 1066    | 1         | 1.02%   |
| 333     | 1         | 1.02%   |

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
| Chicony Electronics           | 11        | 25.58%  |
| Microdia                      | 7         | 16.28%  |
| Sunplus Innovation Technology | 5         | 11.63%  |
| Realtek Semiconductor         | 4         | 9.3%    |
| IMC Networks                  | 4         | 9.3%    |
| Syntek                        | 2         | 4.65%   |
| Suyin                         | 2         | 4.65%   |
| Z-Star Microelectronics       | 1         | 2.33%   |
| Luxvisions Innotech Limited   | 1         | 2.33%   |
| Logitech                      | 1         | 2.33%   |
| Lite-On Technology            | 1         | 2.33%   |
| Genesys Logic                 | 1         | 2.33%   |
| Arkmicro Technologies         | 1         | 2.33%   |
| Alcor Micro                   | 1         | 2.33%   |
| Acer                          | 1         | 2.33%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart_bsd/camera_model.svg)


| Model                                                       | Computers | Percent |
|-------------------------------------------------------------|-----------|---------|
| Chicony HD Webcam                                           | 3         | 6.98%   |
| Sunplus Integrated_Webcam_HD                                | 2         | 4.65%   |
| Realtek Realtek USB2.0 PC Camera                            | 2         | 4.65%   |
| IMC Networks USB2.0 UVC VGA WebCam                          | 2         | 4.65%   |
| Chicony integrated camera                                   | 2         | 4.65%   |
| Z-Star Venus USB2.0 Camera                                  | 1         | 2.33%   |
| Syntek Syntek 0.3MPixel USB 2.0 UVC PC Camera               | 1         | 2.33%   |
| Syntek Integrated Camera                                    | 1         | 2.33%   |
| Suyin Integrated_Webcam_HD                                  | 1         | 2.33%   |
| Suyin 1.3M WebCam (notebook emachines E730, Acer sub-brand) | 1         | 2.33%   |
| Sunplus XiaoMi USB 2.0 Webcam                               | 1         | 2.33%   |
| Sunplus Integrated_Webcam_FHD                               | 1         | 2.33%   |
| Sunplus HP HD Webcam [Fixed]                                | 1         | 2.33%   |
| Realtek Integrated_Webcam_HD                                | 1         | 2.33%   |
| Realtek HD WebCam                                           | 1         | 2.33%   |
| Microdia Webcam                                             | 1         | 2.33%   |
| Microdia Laptop_Integrated_Webcam_HD                        | 1         | 2.33%   |
| Microdia Laptop_Integrated_Webcam_2M                        | 1         | 2.33%   |
| Microdia Integrated_Webcam_HD                               | 1         | 2.33%   |
| Microdia Integrated Webcam HD                               | 1         | 2.33%   |
| Microdia Dell Laptop Integrated Webcam HD                   | 1         | 2.33%   |
| Microdia Camera                                             | 1         | 2.33%   |
| Luxvisions Innotech Limited Integrated Camera               | 1         | 2.33%   |
| Logitech HD Pro Webcam C920                                 | 1         | 2.33%   |
| Lite-On HP HD Webcam [Fixed]                                | 1         | 2.33%   |
| IMC Networks USB2.0 VGA UVC WebCam                          | 1         | 2.33%   |
| IMC Networks HD Camera                                      | 1         | 2.33%   |
| Genesys Logic Digital Microscope                            | 1         | 2.33%   |
| Chicony XiaoMi USB 2.0 Webcam                               | 1         | 2.33%   |
| Chicony VGA WebCam                                          | 1         | 2.33%   |
| Chicony TOSHIBA Web Camera - HD                             | 1         | 2.33%   |
| Chicony TOSHIBA Web Camera - FHD                            | 1         | 2.33%   |
| Chicony Lenovo EasyCamera                                   | 1         | 2.33%   |
| Chicony 1.3M UVC Webcam                                     | 1         | 2.33%   |
| Arkmicro Webcam Carrefour                                   | 1         | 2.33%   |
| Alcor Micro Acer Integrated Webcam                          | 1         | 2.33%   |
| Acer Integrated Camera                                      | 1         | 2.33%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart_bsd/fingerprint_vendor.svg)


| Vendor           | Computers | Percent |
|------------------|-----------|---------|
| Validity Sensors | 4         | 57.14%  |
| Synaptics        | 1         | 14.29%  |
| Broadcom         | 1         | 14.29%  |
| AuthenTec        | 1         | 14.29%  |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart_bsd/fingerprint_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Validity Sensors VFS495 Fingerprint Reader                                   | 2         | 28.57%  |
| Validity Sensors VFS Fingerprint sensor                                      | 1         | 14.29%  |
| Validity Sensors Synaptics WBDI                                              | 1         | 14.29%  |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 1         | 14.29%  |
| AuthenTec AES1600                                                            | 1         | 14.29%  |
| Unknown                                                                      | 1         | 14.29%  |

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
| 1     | 36        | 40%     |
| 0     | 24        | 26.67%  |
| 2     | 18        | 20%     |
| 3     | 9         | 10%     |
| 4     | 2         | 2.22%   |
| 5     | 1         | 1.11%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart_bsd/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Communication controller | 51        | 47.22%  |
| Bluetooth                | 24        | 22.22%  |
| Net/wireless             | 12        | 11.11%  |
| Card reader              | 9         | 8.33%   |
| Fingerprint reader       | 7         | 6.48%   |
| Sound                    | 2         | 1.85%   |
| Network                  | 2         | 1.85%   |
| Storage                  | 1         | 0.93%   |

