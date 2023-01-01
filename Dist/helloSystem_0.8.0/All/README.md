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

Total: 110

| Vendor        | Model                       | Form-Factor | Probe                                                     | Date         |
|---------------|-----------------------------|-------------|-----------------------------------------------------------|--------------|
| Apple         | MacBookAir5,1               | Notebook    | [0d398d5c59](https://bsd-hardware.info/?probe=0d398d5c59) | Dec 27, 2022 |
| Gigabyte      | X399 AORUS Gaming 7         | Desktop     | [1769da5143](https://bsd-hardware.info/?probe=1769da5143) | Dec 25, 2022 |
| Lenovo        | ThinkPad X1 Extreme Gen ... | Notebook    | [d19db2828c](https://bsd-hardware.info/?probe=d19db2828c) | Dec 16, 2022 |
| ASUSTek       | CM1530                      | Desktop     | [902c77b5dc](https://bsd-hardware.info/?probe=902c77b5dc) | Dec 06, 2022 |
| Dell          | Latitude 5590               | Notebook    | [0a17f04eba](https://bsd-hardware.info/?probe=0a17f04eba) | Dec 02, 2022 |
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
| amd64 | 95        | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart_bsd/os_de.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| helloDesktop | 91        | 95.79%  |
| GNOME        | 2         | 2.11%   |
| Window Maker | 1         | 1.05%   |
| Cinnamon     | 1         | 1.05%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart_bsd/os_display_server.svg)


| Name | Computers | Percent |
|------|-----------|---------|
| X11  | 95        | 100%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart_bsd/os_display_manager.svg)


| Name | Computers | Percent |
|------|-----------|---------|
| SLiM | 94        | 98.95%  |
| GDM  | 1         | 1.05%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart_bsd/os_lang.svg)


| Lang  | Computers | Percent |
|-------|-----------|---------|
| en_US | 88        | 92.63%  |
| zh_TW | 1         | 1.05%   |
| ru_RU | 1         | 1.05%   |
| fr    | 1         | 1.05%   |
| es_ES | 1         | 1.05%   |
| en    | 1         | 1.05%   |
| de_DE | 1         | 1.05%   |
| de    | 1         | 1.05%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart_bsd/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 94        | 98.95%  |
| BIOS | 1         | 1.05%   |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart_bsd/os_filesystem.svg)


| Type   | Computers | Percent |
|--------|-----------|---------|
| Cd9660 | 66        | 68.75%  |
| Zfs    | 30        | 31.25%  |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart_bsd/os_part_scheme.svg)


| Type | Computers | Percent |
|------|-----------|---------|
| GPT  | 94        | 98.95%  |
| MBR  | 1         | 1.05%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart_bsd/node_vendor.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| Dell                | 16        | 16.84%  |
| Lenovo              | 12        | 12.63%  |
| Hewlett-Packard     | 12        | 12.63%  |
| ASUSTek Computer    | 11        | 11.58%  |
| Gigabyte Technology | 5         | 5.26%   |
| Apple               | 5         | 5.26%   |
| MSI                 | 4         | 4.21%   |
| Intel               | 4         | 4.21%   |
| Acer                | 4         | 4.21%   |
| ASRock              | 3         | 3.16%   |
| TUXEDO              | 2         | 2.11%   |
| Toshiba             | 2         | 2.11%   |
| Timi                | 2         | 2.11%   |
| Sony                | 2         | 2.11%   |
| Pegatron            | 2         | 2.11%   |
| PCSTICK             | 1         | 1.05%   |
| Packard Bell        | 1         | 1.05%   |
| MACHINIST           | 1         | 1.05%   |
| Kraftway            | 1         | 1.05%   |
| HUAWEI              | 1         | 1.05%   |
| Google              | 1         | 1.05%   |
| Gateway             | 1         | 1.05%   |
| Biostar             | 1         | 1.05%   |
| AMD                 | 1         | 1.05%   |

Model
-----

Motherboard model

![Model](./images/pie_chart_bsd/node_model.svg)


| Name                                         | Computers | Percent |
|----------------------------------------------|-----------|---------|
| MSI MS-7A38                                  | 2         | 2.11%   |
| HP 250 G6 Notebook PC                        | 2         | 2.11%   |
| Apple MacBook5,2                             | 2         | 2.11%   |
| Unknown                                      | 2         | 2.11%   |
| TUXEDO Pulse 14 Gen1                         | 1         | 1.05%   |
| TUXEDO Aura 15 Gen1                          | 1         | 1.05%   |
| Toshiba TECRA Z40-C-12Z                      | 1         | 1.05%   |
| Toshiba Satellite S55t-B                     | 1         | 1.05%   |
| Timi TM1701                                  | 1         | 1.05%   |
| Timi RedmiBook Pro 15                        | 1         | 1.05%   |
| Sony VPCEB1J1E                               | 1         | 1.05%   |
| Sony VGN-AW21S_B                             | 1         | 1.05%   |
| Pegatron IPPPV-D3G                           | 1         | 1.05%   |
| Pegatron IPM41-D3                            | 1         | 1.05%   |
| Packard Bell EasyNote_MX52-B-071             | 1         | 1.05%   |
| MSI PS63 Modern 8M                           | 1         | 1.05%   |
| MSI MS-7C37                                  | 1         | 1.05%   |
| MACHINIST X99-k9 V2.0                        | 1         | 1.05%   |
| Lenovo ThinkPad X270 W10DG 20K5S0BB00        | 1         | 1.05%   |
| Lenovo ThinkPad X250 20CLS23500              | 1         | 1.05%   |
| Lenovo ThinkPad X250 20CLS1WP01              | 1         | 1.05%   |
| Lenovo ThinkPad X1 Extreme Gen 4i 20Y5001DMX | 1         | 1.05%   |
| Lenovo ThinkPad T440 20B7A0B7MS              | 1         | 1.05%   |
| Lenovo ThinkPad T420 4178A72                 | 1         | 1.05%   |
| Lenovo ThinkCentre M93p 10AAA0WGUK           | 1         | 1.05%   |
| Lenovo ThinkCentre M910s 10MK0039US          | 1         | 1.05%   |
| Lenovo ThinkCentre M700 10GS                 | 1         | 1.05%   |
| Lenovo Legion 5 15ARH05 82B5                 | 1         | 1.05%   |
| Lenovo IdeaPad 3 15IGL05 82BU                | 1         | 1.05%   |
| Lenovo G480 20149                            | 1         | 1.05%   |
| Kraftway KW10T                               | 1         | 1.05%   |
| Intel NUC8i7BEK                              | 1         | 1.05%   |
| Intel NUC8i7BEH                              | 1         | 1.05%   |
| Intel MAHOBAY                                | 1         | 1.05%   |
| Intel DN2800MT AAG23738-600                  | 1         | 1.05%   |
| HUAWEI BOD-WXX9                              | 1         | 1.05%   |
| HP Slim Desktop S01-aF1xxx                   | 1         | 1.05%   |
| HP Pavilion g6                               | 1         | 1.05%   |
| HP Pavilion Desktop 590-p0xxx                | 1         | 1.05%   |
| HP OMEN by Laptop                            | 1         | 1.05%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart_bsd/node_model_family.svg)


| Name                  | Computers | Percent |
|-----------------------|-----------|---------|
| Lenovo ThinkPad       | 6         | 6.32%   |
| Dell Latitude         | 6         | 6.32%   |
| Dell Inspiron         | 5         | 5.26%   |
| Acer Aspire           | 4         | 4.21%   |
| Lenovo ThinkCentre    | 3         | 3.16%   |
| MSI MS-7A38           | 2         | 2.11%   |
| HP Pavilion           | 2         | 2.11%   |
| HP EliteDesk          | 2         | 2.11%   |
| HP EliteBook          | 2         | 2.11%   |
| HP 250                | 2         | 2.11%   |
| Dell Studio           | 2         | 2.11%   |
| Dell OptiPlex         | 2         | 2.11%   |
| Apple MacBook5        | 2         | 2.11%   |
| Unknown               | 2         | 2.11%   |
| TUXEDO Pulse          | 1         | 1.05%   |
| TUXEDO Aura           | 1         | 1.05%   |
| Toshiba TECRA         | 1         | 1.05%   |
| Toshiba Satellite     | 1         | 1.05%   |
| Timi TM1701           | 1         | 1.05%   |
| Timi RedmiBook        | 1         | 1.05%   |
| Sony VPCEB1J1E        | 1         | 1.05%   |
| Sony VGN-AW21S        | 1         | 1.05%   |
| Pegatron IPPPV-D3G    | 1         | 1.05%   |
| Pegatron IPM41-D3     | 1         | 1.05%   |
| Packard Bell EasyNote | 1         | 1.05%   |
| MSI PS63              | 1         | 1.05%   |
| MSI MS-7C37           | 1         | 1.05%   |
| MACHINIST X99-k9      | 1         | 1.05%   |
| Lenovo Legion         | 1         | 1.05%   |
| Lenovo IdeaPad        | 1         | 1.05%   |
| Lenovo G480           | 1         | 1.05%   |
| Kraftway KW10T        | 1         | 1.05%   |
| Intel NUC8i7BEK       | 1         | 1.05%   |
| Intel NUC8i7BEH       | 1         | 1.05%   |
| Intel MAHOBAY         | 1         | 1.05%   |
| Intel DN2800MT        | 1         | 1.05%   |
| HUAWEI BOD-WXX9       | 1         | 1.05%   |
| HP Slim               | 1         | 1.05%   |
| HP OMEN               | 1         | 1.05%   |
| HP Desktop            | 1         | 1.05%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart_bsd/node_year.svg)


| Year | Computers | Percent |
|------|-----------|---------|
| 2019 | 11        | 11.58%  |
| 2020 | 10        | 10.53%  |
| 2021 | 8         | 8.42%   |
| 2022 | 7         | 7.37%   |
| 2009 | 7         | 7.37%   |
| 2018 | 6         | 6.32%   |
| 2015 | 6         | 6.32%   |
| 2014 | 6         | 6.32%   |
| 2013 | 6         | 6.32%   |
| 2012 | 6         | 6.32%   |
| 2010 | 6         | 6.32%   |
| 2011 | 5         | 5.26%   |
| 2016 | 4         | 4.21%   |
| 2017 | 3         | 3.16%   |
| 2008 | 3         | 3.16%   |
| 2007 | 1         | 1.05%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart_bsd/node_formfactor.svg)


| Name       | Computers | Percent |
|------------|-----------|---------|
| Notebook   | 53        | 55.79%  |
| Desktop    | 38        | 40%     |
| Mini pc    | 2         | 2.11%   |
| All in one | 2         | 2.11%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart_bsd/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 94        | 98.95%  |
| Yes  | 1         | 1.05%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart_bsd/node_ram_total.svg)


| Size in GB  | Computers | Percent |
|-------------|-----------|---------|
| 8.01-16.0   | 30        | 31.58%  |
| 4.01-8.0    | 28        | 29.47%  |
| 16.01-24.0  | 22        | 23.16%  |
| 32.01-64.0  | 6         | 6.32%   |
| 2.01-3.0    | 6         | 6.32%   |
| 3.01-4.0    | 1         | 1.05%   |
| 24.01-32.0  | 1         | 1.05%   |
| 64.01-256.0 | 1         | 1.05%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart_bsd/node_ram_used.svg)


| Used GB  | Computers | Percent |
|----------|-----------|---------|
| 0.01-0.5 | 53        | 55.79%  |
| 0.51-1.0 | 27        | 28.42%  |
| 1.01-2.0 | 13        | 13.68%  |
| 4.01-8.0 | 1         | 1.05%   |
| 2.01-3.0 | 1         | 1.05%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart_bsd/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 62        | 64.58%  |
| 2      | 20        | 20.83%  |
| 0      | 6         | 6.25%   |
| 3      | 4         | 4.17%   |
| 5      | 2         | 2.08%   |
| 6      | 1         | 1.04%   |
| 4      | 1         | 1.04%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart_bsd/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 64        | 67.37%  |
| Yes       | 31        | 32.63%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart_bsd/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 83        | 87.37%  |
| No        | 12        | 12.63%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart_bsd/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 68        | 70.83%  |
| No        | 28        | 29.17%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart_bsd/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 50        | 52.63%  |
| No        | 45        | 47.37%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart_bsd/node_location.svg)


| Country      | Computers | Percent |
|--------------|-----------|---------|
| USA          | 12        | 12.63%  |
| Russia       | 10        | 10.53%  |
| Germany      | 9         | 9.47%   |
| Brazil       | 7         | 7.37%   |
| Taiwan       | 6         | 6.32%   |
| Spain        | 5         | 5.26%   |
| China        | 5         | 5.26%   |
| Italy        | 4         | 4.21%   |
| Ukraine      | 3         | 3.16%   |
| UK           | 3         | 3.16%   |
| Mexico       | 3         | 3.16%   |
| France       | 3         | 3.16%   |
| Canada       | 3         | 3.16%   |
| Poland       | 2         | 2.11%   |
| Norway       | 2         | 2.11%   |
| Hungary      | 2         | 2.11%   |
| Venezuela    | 1         | 1.05%   |
| UAE          | 1         | 1.05%   |
| Sweden       | 1         | 1.05%   |
| South Africa | 1         | 1.05%   |
| Slovenia     | 1         | 1.05%   |
| Slovakia     | 1         | 1.05%   |
| Serbia       | 1         | 1.05%   |
| Romania      | 1         | 1.05%   |
| Peru         | 1         | 1.05%   |
| Panama       | 1         | 1.05%   |
| India        | 1         | 1.05%   |
| Greece       | 1         | 1.05%   |
| Georgia      | 1         | 1.05%   |
| Belarus      | 1         | 1.05%   |
| Argentina    | 1         | 1.05%   |
| Albania      | 1         | 1.05%   |

City
----

Geographic location (city)

![City](./images/pie_chart_bsd/node_city.svg)


| City                 | Computers | Percent |
|----------------------|-----------|---------|
| Aquan                | 4         | 4.17%   |
| Moscow               | 3         | 3.13%   |
| Volgograd            | 2         | 2.08%   |
| Temple               | 2         | 2.08%   |
| Munich               | 2         | 2.08%   |
| LogroÃ±o           | 2         | 2.08%   |
| Zhengzhou            | 1         | 1.04%   |
| Yunlin               | 1         | 1.04%   |
| Willingboro          | 1         | 1.04%   |
| Weifang              | 1         | 1.04%   |
| Warendorf            | 1         | 1.04%   |
| Voronezh             | 1         | 1.04%   |
| Vladivostok          | 1         | 1.04%   |
| Vancouver            | 1         | 1.04%   |
| Ufa                  | 1         | 1.04%   |
| Trieste              | 1         | 1.04%   |
| Szeged               | 1         | 1.04%   |
| Surrey               | 1         | 1.04%   |
| Southminster         | 1         | 1.04%   |
| Seville              | 1         | 1.04%   |
| Sao Paulo            | 1         | 1.04%   |
| San Carlos del Zulia | 1         | 1.04%   |
| Salisbury            | 1         | 1.04%   |
| Rosignano Marittimo  | 1         | 1.04%   |
| Rio das Ostras       | 1         | 1.04%   |
| Rho                  | 1         | 1.04%   |
| Reinsvoll            | 1         | 1.04%   |
| Redondela            | 1         | 1.04%   |
| Perm                 | 1         | 1.04%   |
| Panama City          | 1         | 1.04%   |
| Ottawa               | 1         | 1.04%   |
| Orizaba              | 1         | 1.04%   |
| Odessa               | 1         | 1.04%   |
| Oakdale              | 1         | 1.04%   |
| Nesttun              | 1         | 1.04%   |
| Nanticoke            | 1         | 1.04%   |
| Monterrey            | 1         | 1.04%   |
| Mirepeix             | 1         | 1.04%   |
| Minsk                | 1         | 1.04%   |
| Mexico City          | 1         | 1.04%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart_bsd/drive_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 21        | 24     | 16.8%   |
| Samsung Electronics | 17        | 20     | 13.6%   |
| WDC                 | 16        | 18     | 12.8%   |
| Toshiba             | 10        | 10     | 8%      |
| Kingston            | 10        | 10     | 8%      |
| Hitachi             | 10        | 10     | 8%      |
| Intel               | 5         | 5      | 4%      |
| SK hynix            | 3         | 3      | 2.4%    |
| PNY                 | 3         | 3      | 2.4%    |
| A-DATA Technology   | 3         | 3      | 2.4%    |
| SPCC                | 2         | 2      | 1.6%    |
| SanDisk             | 2         | 3      | 1.6%    |
| OCZ                 | 2         | 2      | 1.6%    |
| KIOXIA              | 2         | 2      | 1.6%    |
| KingSpec            | 2         | 2      | 1.6%    |
| Fujitsu             | 2         | 2      | 1.6%    |
| Crucial             | 2         | 2      | 1.6%    |
| Transcend           | 1         | 1      | 0.8%    |
| SSSTC               | 1         | 1      | 0.8%    |
| Patriot             | 1         | 1      | 0.8%    |
| Lexar               | 1         | 2      | 0.8%    |
| LDLC                | 1         | 1      | 0.8%    |
| Intenso             | 1         | 1      | 0.8%    |
| Hewlett-Packard     | 1         | 1      | 0.8%    |
| GOODRAM             | 1         | 1      | 0.8%    |
| Gigabyte Technology | 1         | 1      | 0.8%    |
| FORESEE             | 1         | 1      | 0.8%    |
| Emtec               | 1         | 1      | 0.8%    |
| Corsair             | 1         | 1      | 0.8%    |
| Apple               | 1         | 1      | 0.8%    |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart_bsd/drive_model.svg)


| Model                                     | Computers | Percent |
|-------------------------------------------|-----------|---------|
| Seagate ST1000LM035-1RK172 1TB            | 3         | 2.24%   |
| Toshiba MQ01ABF050 500GB                  | 2         | 1.49%   |
| Toshiba MQ01ABD050 500GB                  | 2         | 1.49%   |
| Seagate ST1000LM024 HN-M101MBB 1TB        | 2         | 1.49%   |
| Samsung SSD 970 EVO 250GB                 | 2         | 1.49%   |
| Samsung SSD 860 PRO 512GB                 | 2         | 1.49%   |
| Kingston SV300S37A120G 120GB              | 2         | 1.49%   |
| Kingston SA400S37120G 120GB               | 2         | 1.49%   |
| Hitachi HDS721616PLA380 160GB             | 2         | 1.49%   |
| WDC WDS500G2X0C-00L350 500GB              | 1         | 0.75%   |
| WDC WDS500G2B0A 500GB                     | 1         | 0.75%   |
| WDC WDS500G1B0C-00S6U0 500GB              | 1         | 0.75%   |
| WDC WDS240G2G0B-00EPW0 240GB              | 1         | 0.75%   |
| WDC WDS100T2B0A-00SM50 1TB                | 1         | 0.75%   |
| WDC WDBNCE5000PNC 500GB                   | 1         | 0.75%   |
| WDC WD5000LPLX-08ZNTT0 500GB              | 1         | 0.75%   |
| WDC WD5000LPCX-60VHAT0 500GB              | 1         | 0.75%   |
| WDC WD5000AZLX-60K2TA1 500GB              | 1         | 0.75%   |
| WDC WD5000AVVS-63H0B1 500GB               | 1         | 0.75%   |
| WDC WD5000AAKS-00YGA0 500GB               | 1         | 0.75%   |
| WDC WD40NPZZ-00A9JT0 4TB                  | 1         | 0.75%   |
| WDC WD3003FZEX-00Z4SA0 3TB                | 1         | 0.75%   |
| WDC WD2500BEVT-75A23T0 250GB              | 1         | 0.75%   |
| WDC WD20EFRX-68EUZN0 2TB                  | 1         | 0.75%   |
| WDC WD10JPVX-75JC3T0 1TB                  | 1         | 0.75%   |
| WDC WD10JPVX-22JC3T0 1TB                  | 1         | 0.75%   |
| WDC PC SN530 SDBPNPZ-512G-1027 512GB      | 1         | 0.75%   |
| Transcend TS120GMTS420S 120GB             | 1         | 0.75%   |
| Toshiba TR200 480GB                       | 1         | 0.75%   |
| Toshiba Q300 240GB                        | 1         | 0.75%   |
| Toshiba MQ01ABD100 1TB                    | 1         | 0.75%   |
| Toshiba MK8034GSX 80GB                    | 1         | 0.75%   |
| Toshiba KSG60ZMV256G 256GB                | 1         | 0.75%   |
| Toshiba DT01ACA100 1TB                    | 1         | 0.75%   |
| SSSTC CL1-4D128 128GB                     | 1         | 0.75%   |
| SPCC Solid State Disk 56GB                | 1         | 0.75%   |
| SPCC Solid State Disk 512GB               | 1         | 0.75%   |
| SK hynix SKHynix_HFM512GDHTNI-87A0B 512GB | 1         | 0.75%   |
| SK hynix BC711 NVMe 512GB                 | 1         | 0.75%   |
| SK hynix BC711 NVMe 256GB                 | 1         | 0.75%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart_bsd/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 21        | 24     | 39.62%  |
| WDC                 | 11        | 11     | 20.75%  |
| Hitachi             | 10        | 10     | 18.87%  |
| Toshiba             | 7         | 7      | 13.21%  |
| Samsung Electronics | 2         | 2      | 3.77%   |
| Hewlett-Packard     | 1         | 1      | 1.89%   |
| Fujitsu             | 1         | 1      | 1.89%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart_bsd/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 10        | 10     | 19.23%  |
| Kingston            | 7         | 7      | 13.46%  |
| WDC                 | 4         | 4      | 7.69%   |
| Intel               | 4         | 4      | 7.69%   |
| Toshiba             | 3         | 3      | 5.77%   |
| PNY                 | 3         | 3      | 5.77%   |
| SPCC                | 2         | 2      | 3.85%   |
| SanDisk             | 2         | 3      | 3.85%   |
| OCZ                 | 2         | 2      | 3.85%   |
| KingSpec            | 2         | 2      | 3.85%   |
| A-DATA Technology   | 2         | 2      | 3.85%   |
| Transcend           | 1         | 1      | 1.92%   |
| Patriot             | 1         | 1      | 1.92%   |
| Lexar               | 1         | 1      | 1.92%   |
| Intenso             | 1         | 1      | 1.92%   |
| GOODRAM             | 1         | 1      | 1.92%   |
| Gigabyte Technology | 1         | 1      | 1.92%   |
| Fujitsu             | 1         | 1      | 1.92%   |
| FORESEE             | 1         | 1      | 1.92%   |
| Emtec               | 1         | 1      | 1.92%   |
| Crucial             | 1         | 1      | 1.92%   |
| Apple               | 1         | 1      | 1.92%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart_bsd/drive_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SSD  | 44        | 53     | 39.64%  |
| HDD  | 43        | 56     | 38.74%  |
| NVMe | 24        | 26     | 21.62%  |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart_bsd/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 79        | 109    | 76.7%   |
| NVMe | 24        | 26     | 23.3%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart_bsd/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 61        | 81     | 70.93%  |
| 0.51-1.0   | 16        | 18     | 18.6%   |
| 1.01-2.0   | 6         | 6      | 6.98%   |
| 3.01-4.0   | 2         | 2      | 2.33%   |
| 2.01-3.0   | 1         | 2      | 1.16%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart_bsd/drive_space_total.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| 1-20       | 59        | 62.11%  |
| 101-250    | 14        | 14.74%  |
| 251-500    | 12        | 12.63%  |
| 501-1000   | 5         | 5.26%   |
| 1001-2000  | 2         | 2.11%   |
| 21-50      | 1         | 1.05%   |
| 51-100     | 1         | 1.05%   |
| Unknown    | 1         | 1.05%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart_bsd/drive_space_used.svg)


| Used GB  | Computers | Percent |
|----------|-----------|---------|
| 1-20     | 90        | 94.74%  |
| 101-250  | 2         | 2.11%   |
| 501-1000 | 1         | 1.05%   |
| 51-100   | 1         | 1.05%   |
| Unknown  | 1         | 1.05%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart_bsd/drive_malfunc.svg)


| Model                                        | Computers | Drives | Percent |
|----------------------------------------------|-----------|--------|---------|
| WDC WD5000LPCX-60VHAT0 500GB                 | 1         | 1      | 5%      |
| WDC WD5000AVVS-63H0B1 500GB                  | 1         | 1      | 5%      |
| Toshiba MQ01ABF050 500GB                     | 1         | 1      | 5%      |
| Toshiba MQ01ABD100 1TB                       | 1         | 1      | 5%      |
| Toshiba MK8034GSX 80GB                       | 1         | 1      | 5%      |
| Seagate ST9160821AS 160GB                    | 1         | 1      | 5%      |
| Seagate ST500LT012-9WS142 500GB              | 1         | 1      | 5%      |
| Seagate ST500DM002-1BD142 500GB              | 1         | 1      | 5%      |
| Seagate ST320LT014-9YK142 320GB              | 1         | 1      | 5%      |
| Seagate ST1000LM024 HN-M101MBB 1TB           | 1         | 1      | 5%      |
| Samsung Electronics MZMPA128HMFU-000H1 128GB | 1         | 1      | 5%      |
| Samsung Electronics HD501LJ 500GB            | 1         | 1      | 5%      |
| OCZ VERTEX3 240GB                            | 1         | 1      | 5%      |
| Hitachi HTS727550A9E364 500GB                | 1         | 1      | 5%      |
| Hitachi HTS545050A7E380 500GB                | 1         | 1      | 5%      |
| Hitachi HTS545025B9SA02 250GB                | 1         | 1      | 5%      |
| Hitachi HTS541680J9SA00 80GB                 | 1         | 1      | 5%      |
| Hitachi HTS541612J9SA00 120GB                | 1         | 1      | 5%      |
| Hitachi HDS721616PLA380 160GB                | 1         | 1      | 5%      |
| Fujitsu MHZ2160BH FFS G1 160GB               | 1         | 1      | 5%      |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart_bsd/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Hitachi             | 6         | 6      | 30%     |
| Seagate             | 5         | 5      | 25%     |
| Toshiba             | 3         | 3      | 15%     |
| WDC                 | 2         | 2      | 10%     |
| Samsung Electronics | 2         | 2      | 10%     |
| OCZ                 | 1         | 1      | 5%      |
| Fujitsu             | 1         | 1      | 5%      |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart_bsd/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Hitachi             | 6         | 6      | 33.33%  |
| Seagate             | 5         | 5      | 27.78%  |
| Toshiba             | 3         | 3      | 16.67%  |
| WDC                 | 2         | 2      | 11.11%  |
| Samsung Electronics | 1         | 1      | 5.56%   |
| Fujitsu             | 1         | 1      | 5.56%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart_bsd/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 16        | 18     | 88.89%  |
| SSD  | 2         | 2      | 11.11%  |

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
| Works    | 75        | 109    | 79.79%  |
| Malfunc  | 16        | 20     | 17.02%  |
| Detected | 3         | 6      | 3.19%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart_bsd/storage_vendor.svg)


| Vendor                         | Computers | Percent |
|--------------------------------|-----------|---------|
| Intel                          | 67        | 57.76%  |
| AMD                            | 16        | 13.79%  |
| Samsung Electronics            | 7         | 6.03%   |
| Nvidia                         | 4         | 3.45%   |
| SK hynix                       | 3         | 2.59%   |
| SanDisk                        | 3         | 2.59%   |
| Kingston Technology Company    | 3         | 2.59%   |
| JMicron Technology             | 3         | 2.59%   |
| Toshiba                        | 1         | 0.86%   |
| Solid State Storage Technology | 1         | 0.86%   |
| Silicon Motion                 | 1         | 0.86%   |
| Shenzhen Longsys Electronics   | 1         | 0.86%   |
| Realtek Semiconductor          | 1         | 0.86%   |
| Phison Electronics             | 1         | 0.86%   |
| Micron/Crucial Technology      | 1         | 0.86%   |
| Marvell Technology Group       | 1         | 0.86%   |
| KIOXIA                         | 1         | 0.86%   |
| ASMedia Technology             | 1         | 0.86%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart_bsd/storage_model.svg)


| Model                                                                                   | Computers | Percent |
|-----------------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 10        | 7.58%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                      | 7         | 5.3%    |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                                      | 5         | 3.79%   |
| Nvidia MCP79 AHCI Controller                                                            | 4         | 3.03%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 4         | 3.03%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                                      | 4         | 3.03%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 4         | 3.03%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                        | 4         | 3.03%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller            | 4         | 3.03%   |
| Unknown                                                                                 | 4         | 3.03%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 3         | 2.27%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                                  | 3         | 2.27%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                       | 3         | 2.27%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 3         | 2.27%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 3         | 2.27%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 3         | 2.27%   |
| SK hynix Gold P31/PC711 NVMe Solid State Drive                                          | 2         | 1.52%   |
| Samsung NVMe SSD Controller 980                                                         | 2         | 1.52%   |
| JMicron JMB368 IDE controller                                                           | 2         | 1.52%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 2         | 1.52%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                                  | 2         | 1.52%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]                   | 2         | 1.52%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                          | 2         | 1.52%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                            | 2         | 1.52%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 2         | 1.52%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 2         | 1.52%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 2         | 1.52%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                                    | 2         | 1.52%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 2         | 1.52%   |
| Toshiba XG6 NVMe SSD Controller                                                         | 1         | 0.76%   |
| SK hynix BC511                                                                          | 1         | 0.76%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                         | 1         | 0.76%   |
| Shenzhen Longsys SM2263EN/SM2263XT-based OEM SSD                                        | 1         | 0.76%   |
| SanDisk WD Blue SN550 NVMe SSD                                                          | 1         | 0.76%   |
| SanDisk WD Blue SN500 / PC SN520 NVMe SSD                                               | 1         | 0.76%   |
| SanDisk WD Black 2018/SN750 / PC SN720 NVMe SSD                                         | 1         | 0.76%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                           | 1         | 0.76%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                          | 1         | 0.76%   |
| Phison E12 NVMe Controller                                                              | 1         | 0.76%   |
| Micron/Crucial P2 NVMe PCIe SSD                                                         | 1         | 0.76%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart_bsd/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 72        | 62.07%  |
| NVMe | 24        | 20.69%  |
| IDE  | 17        | 14.66%  |
| RAID | 3         | 2.59%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart_bsd/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 78        | 82.11%  |
| AMD    | 17        | 17.89%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart_bsd/cpu_model.svg)


| Model                                       | Computers | Percent |
|---------------------------------------------|-----------|---------|
| Intel Core i7-8559U CPU @ 2.70GHz           | 2         | 2.11%   |
| Intel Core i7-6600U CPU @ 2.60GHz           | 2         | 2.11%   |
| Intel Core i5-6200U CPU @ 2.30GHz           | 2         | 2.11%   |
| Intel Core i5-5300U CPU @ 2.30GHz           | 2         | 2.11%   |
| Intel Core i5-5200U CPU @ 2.20GHz           | 2         | 2.11%   |
| Intel Core i5-3470 CPU @ 3.20GHz            | 2         | 2.11%   |
| Intel Core 2 Duo CPU P7450 @ 2.13GHz        | 2         | 2.11%   |
| AMD Ryzen 7 4800H with Radeon Graphics      | 2         | 2.11%   |
| Intel Xeon CPU E5-2630L v4 @ 1.80GHz        | 1         | 1.05%   |
| Intel Pentium Silver N5000 CPU @ 1.10GHz    | 1         | 1.05%   |
| Intel Pentium Silver J5040 CPU @ 2.00GHz    | 1         | 1.05%   |
| Intel Pentium Dual-Core CPU E6700 @ 3.20GHz | 1         | 1.05%   |
| Intel Pentium Dual-Core CPU E5700 @ 3.00GHz | 1         | 1.05%   |
| Intel Pentium Dual-Core CPU E5400 @ 2.70GHz | 1         | 1.05%   |
| Intel Pentium Dual-Core CPU E5200 @ 2.50GHz | 1         | 1.05%   |
| Intel Pentium CPU N3700 @ 1.60GHz           | 1         | 1.05%   |
| Intel Pentium CPU G4400 @ 3.30GHz           | 1         | 1.05%   |
| Intel Pentium CPU 4417U @ 2.30GHz           | 1         | 1.05%   |
| Intel CPU Version                           | 1         | 1.05%   |
| Intel Core i7-9700 CPU @ 3.00GHz            | 1         | 1.05%   |
| Intel Core i7-8650U CPU @ 1.90GHz           | 1         | 1.05%   |
| Intel Core i7-8565U CPU @ 1.80GHz           | 1         | 1.05%   |
| Intel Core i7-8550U CPU @ 1.80GHz           | 1         | 1.05%   |
| Intel Core i7-7700 CPU @ 3.60GHz            | 1         | 1.05%   |
| Intel Core i7-5500U CPU @ 2.40GHz           | 1         | 1.05%   |
| Intel Core i7-4810MQ CPU @ 2.80GHz          | 1         | 1.05%   |
| Intel Core i7-4790 CPU @ 3.60GHz            | 1         | 1.05%   |
| Intel Core i7-2677M CPU @ 1.80GHz           | 1         | 1.05%   |
| Intel Core i7-2620M CPU @ 2.70GHz           | 1         | 1.05%   |
| Intel Core i5-9400 CPU @ 2.90GHz            | 1         | 1.05%   |
| Intel Core i5-7200U CPU @ 2.50GHz           | 1         | 1.05%   |
| Intel Core i5-6500 CPU @ 3.20GHz            | 1         | 1.05%   |
| Intel Core i5-6440HQ CPU @ 2.60GHz          | 1         | 1.05%   |
| Intel Core i5-6300U CPU @ 2.40GHz           | 1         | 1.05%   |
| Intel Core i5-6300HQ CPU @ 2.30GHz          | 1         | 1.05%   |
| Intel Core i5-4590 CPU @ 3.30GHz            | 1         | 1.05%   |
| Intel Core i5-4570T CPU @ 2.90GHz           | 1         | 1.05%   |
| Intel Core i5-4310U CPU @ 2.00GHz           | 1         | 1.05%   |
| Intel Core i5-4300U CPU @ 1.90GHz           | 1         | 1.05%   |
| Intel Core i5-3317U CPU @ 1.70GHz           | 1         | 1.05%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart_bsd/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 22        | 23.16%  |
| Intel Core i7           | 14        | 14.74%  |
| Intel Core i3           | 9         | 9.47%   |
| Intel Core 2 Duo        | 7         | 7.37%   |
| Other                   | 6         | 6.32%   |
| Intel Atom              | 5         | 5.26%   |
| Intel Pentium Dual-Core | 4         | 4.21%   |
| Intel Celeron           | 4         | 4.21%   |
| AMD Ryzen 5             | 4         | 4.21%   |
| Intel Pentium           | 3         | 3.16%   |
| AMD Ryzen 7             | 3         | 3.16%   |
| Intel Pentium Silver    | 2         | 2.11%   |
| Intel Xeon              | 1         | 1.05%   |
| Intel Core 2 Quad       | 1         | 1.05%   |
| Intel Core 2            | 1         | 1.05%   |
| AMD V120                | 1         | 1.05%   |
| AMD Ryzen Threadripper  | 1         | 1.05%   |
| AMD Ryzen 9             | 1         | 1.05%   |
| AMD Ryzen 5 PRO         | 1         | 1.05%   |
| AMD Phenom II X4        | 1         | 1.05%   |
| AMD FX                  | 1         | 1.05%   |
| AMD Athlon II X4        | 1         | 1.05%   |
| AMD Athlon 64 X2        | 1         | 1.05%   |
| AMD A8                  | 1         | 1.05%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart_bsd/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 39        | 41.05%  |
| 4       | 29        | 30.53%  |
| Unknown | 7         | 7.37%   |
| 8       | 6         | 6.32%   |
| 16      | 3         | 3.16%   |
| 12      | 3         | 3.16%   |
| 6       | 3         | 3.16%   |
| 1       | 3         | 3.16%   |
| 24      | 1         | 1.05%   |
| 10      | 1         | 1.05%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart_bsd/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 91        | 95.79%  |
| 2      | 4         | 4.21%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart_bsd/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 45        | 47.37%  |
| 1       | 43        | 45.26%  |
| Unknown | 7         | 7.37%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart_bsd/cpu_microarch.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| KabyLake      | 12        | 12.63%  |
| Penryn        | 11        | 11.58%  |
| Skylake       | 9         | 9.47%   |
| SandyBridge   | 7         | 7.37%   |
| Broadwell     | 7         | 7.37%   |
| Haswell       | 6         | 6.32%   |
| Zen 2         | 5         | 5.26%   |
| Silvermont    | 5         | 5.26%   |
| IvyBridge     | 5         | 5.26%   |
| K10           | 3         | 3.16%   |
| Goldmont plus | 3         | 3.16%   |
| Bonnell       | 3         | 3.16%   |
| Unknown       | 3         | 3.16%   |
| Zen+          | 2         | 2.11%   |
| Zen           | 2         | 2.11%   |
| TigerLake     | 2         | 2.11%   |
| Core          | 2         | 2.11%   |
| CometLake     | 2         | 2.11%   |
| Zen 3         | 1         | 1.05%   |
| Westmere      | 1         | 1.05%   |
| Piledriver    | 1         | 1.05%   |
| Nehalem       | 1         | 1.05%   |
| K8 Hammer     | 1         | 1.05%   |
| Excavator     | 1         | 1.05%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart_bsd/gpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 60        | 55.05%  |
| Nvidia | 31        | 28.44%  |
| AMD    | 18        | 16.51%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart_bsd/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel HD Graphics 5500                                                                   | 6         | 5.5%    |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 6         | 5.5%    |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 5         | 4.59%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 3         | 2.75%   |
| Intel HD Graphics 530                                                                    | 3         | 2.75%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 3         | 2.75%   |
| AMD Renoir                                                                               | 3         | 2.75%   |
| Nvidia TU116 [GeForce GTX 1660]                                                          | 2         | 1.83%   |
| Nvidia TU116 [GeForce GTX 1660 Ti]                                                       | 2         | 1.83%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 2         | 1.83%   |
| Nvidia C79 [GeForce 9400M G]                                                             | 2         | 1.83%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 2         | 1.83%   |
| Intel UHD Graphics 620                                                                   | 2         | 1.83%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 2         | 1.83%   |
| Intel HD Graphics 620                                                                    | 2         | 1.83%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 2         | 1.83%   |
| Intel GeminiLake [UHD Graphics 605]                                                      | 2         | 1.83%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                                 | 2         | 1.83%   |
| Intel CoffeeLake-U GT3e [Iris Plus Graphics 655]                                         | 2         | 1.83%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 2         | 1.83%   |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller                  | 2         | 1.83%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 2         | 1.83%   |
| Nvidia TU117M [GeForce MX450]                                                            | 1         | 0.92%   |
| Nvidia TU117M                                                                            | 1         | 0.92%   |
| Nvidia TU116 [GeForce GTX 1660 SUPER]                                                    | 1         | 0.92%   |
| Nvidia GT218 [GeForce 210]                                                               | 1         | 0.92%   |
| Nvidia GT215 [GeForce GT 240]                                                            | 1         | 0.92%   |
| Nvidia GP108M [GeForce MX150]                                                            | 1         | 0.92%   |
| Nvidia GP108 [GeForce GT 1030]                                                           | 1         | 0.92%   |
| Nvidia GM206 [GeForce GTX 950]                                                           | 1         | 0.92%   |
| Nvidia GM108M [GeForce MX110]                                                            | 1         | 0.92%   |
| Nvidia GM107M [GeForce GTX 950M]                                                         | 1         | 0.92%   |
| Nvidia GK104 [GeForce GTX 760]                                                           | 1         | 0.92%   |
| Nvidia GF119M [Quadro NVS 4200M]                                                         | 1         | 0.92%   |
| Nvidia GF119 [GeForce GT 620 OEM]                                                        | 1         | 0.92%   |
| Nvidia GF108M [GeForce 610M]                                                             | 1         | 0.92%   |
| Nvidia GF108 [GeForce GT 630]                                                            | 1         | 0.92%   |
| Nvidia GF108 [GeForce GT 440]                                                            | 1         | 0.92%   |
| Nvidia GA107M [GeForce RTX 3050 Ti Mobile]                                               | 1         | 0.92%   |
| Nvidia G96CM [GeForce 9600M GT]                                                          | 1         | 0.92%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart_bsd/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 44        | 46.32%  |
| 1 x Nvidia     | 21        | 22.11%  |
| 1 x AMD        | 13        | 13.68%  |
| Intel + Nvidia | 9         | 9.47%   |
| Intel + AMD    | 4         | 4.21%   |
| 2 x Intel      | 3         | 3.16%   |
| AMD + Nvidia   | 1         | 1.05%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart_bsd/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 71        | 74.74%  |
| Proprietary | 18        | 18.95%  |
| Unknown     | 6         | 6.32%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart_bsd/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 69        | 72.63%  |
| 0.01-0.5   | 10        | 10.53%  |
| 5.01-6.0   | 5         | 5.26%   |
| 1.01-2.0   | 5         | 5.26%   |
| 0.51-1.0   | 3         | 3.16%   |
| 3.01-4.0   | 2         | 2.11%   |
| 7.01-8.0   | 1         | 1.05%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart_bsd/mon_vendor.svg)


| Vendor               | Computers | Percent |
|----------------------|-----------|---------|
| LG Display           | 13        | 15.66%  |
| AU Optronics         | 10        | 12.05%  |
| Samsung Electronics  | 6         | 7.23%   |
| Dell                 | 6         | 7.23%   |
| Chimei Innolux       | 6         | 7.23%   |
| Apple                | 6         | 7.23%   |
| BOE                  | 5         | 6.02%   |
| Goldstar             | 4         | 4.82%   |
| Acer                 | 4         | 4.82%   |
| MSI                  | 3         | 3.61%   |
| Hewlett-Packard      | 3         | 3.61%   |
| Philips              | 2         | 2.41%   |
| BenQ                 | 2         | 2.41%   |
| AOC                  | 2         | 2.41%   |
| Vizio                | 1         | 1.2%    |
| Toshiba              | 1         | 1.2%    |
| TMX                  | 1         | 1.2%    |
| Nvidia               | 1         | 1.2%    |
| LG Philips           | 1         | 1.2%    |
| Insignia             | 1         | 1.2%    |
| Iiyama               | 1         | 1.2%    |
| HannStar             | 1         | 1.2%    |
| Fujitsu Siemens      | 1         | 1.2%    |
| CPT                  | 1         | 1.2%    |
| Ancor Communications | 1         | 1.2%    |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart_bsd/mon_model.svg)


| Model                                                                 | Computers | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| MSI G32C4 MSI3DA6 1920x1080 700x390mm 31.5-inch                       | 2         | 2.38%   |
| LG Display LCD Monitor LGD0484 1366x768 340x190mm 15.3-inch           | 2         | 2.38%   |
| Apple Color LCD APP9C5C 1280x800 290x180mm 13.4-inch                  | 2         | 2.38%   |
| Acer G227HQL ACR03DE 1920x1080 480x270mm 21.7-inch                    | 2         | 2.38%   |
| Vizio D43-D2 VIZ1004 1920x1080 930x520mm 41.9-inch                    | 1         | 1.19%   |
| Toshiba TV TSB0110 1920x1080 1110x620mm 50.1-inch                     | 1         | 1.19%   |
| TMX LCD Monitor TMX1560 3200x2000 340x210mm 15.7-inch                 | 1         | 1.19%   |
| Samsung Electronics SyncMaster SAM0601 1600x900                       | 1         | 1.19%   |
| Samsung Electronics SyncMaster SAM05FF 1600x900 440x250mm 19.9-inch   | 1         | 1.19%   |
| Samsung Electronics SyncMaster SAM05C5 1920x1080                      | 1         | 1.19%   |
| Samsung Electronics SMS23A550H SAM07C9 1920x1080 510x290mm 23.1-inch  | 1         | 1.19%   |
| Samsung Electronics LCD Monitor SEC4149 1366x768 280x170mm 12.9-inch  | 1         | 1.19%   |
| Samsung Electronics LCD Monitor SDC4C48 1920x1080 340x190mm 15.3-inch | 1         | 1.19%   |
| Samsung Electronics LCD Monitor SAM0C26 1920x1080 700x390mm 31.5-inch | 1         | 1.19%   |
| Philips PHL 223V5 PHLC0CF 1920x1080 480x270mm 21.7-inch               | 1         | 1.19%   |
| Philips 237EQPH PHLC091 1920x1080 510x290mm 23.1-inch                 | 1         | 1.19%   |
| Nvidia LCD Monitor NVD0200 1920x1080 320x180mm 14.5-inch              | 1         | 1.19%   |
| MSI MAG342CQRV MSI3DB6 3440x1440 790x330mm 33.7-inch                  | 1         | 1.19%   |
| LG Philips LCD Monitor LPLE300 1280x800 330x210mm 15.4-inch           | 1         | 1.19%   |
| LG Display LCD Monitor LGD06AA 3840x2400 340x210mm 15.7-inch          | 1         | 1.19%   |
| LG Display LCD Monitor LGD0569 1920x1080 310x170mm 13.9-inch          | 1         | 1.19%   |
| LG Display LCD Monitor LGD0532 1920x1080 340x190mm 15.3-inch          | 1         | 1.19%   |
| LG Display LCD Monitor LGD0470 1920x1080 350x190mm 15.7-inch          | 1         | 1.19%   |
| LG Display LCD Monitor LGD046F 1920x1080 340x190mm 15.3-inch          | 1         | 1.19%   |
| LG Display LCD Monitor LGD0435 1600x900 310x170mm 13.9-inch           | 1         | 1.19%   |
| LG Display LCD Monitor LGD03EE 1366x768 280x160mm 12.7-inch           | 1         | 1.19%   |
| LG Display LCD Monitor LGD03B7 1366x768 310x170mm 13.9-inch           | 1         | 1.19%   |
| LG Display LCD Monitor LGD0384 1366x768 340x190mm 15.3-inch           | 1         | 1.19%   |
| LG Display LCD Monitor LGD02DC 1366x768 340x190mm 15.3-inch           | 1         | 1.19%   |
| LG Display LCD Monitor LGD021D 1600x900 380x210mm 17.1-inch           | 1         | 1.19%   |
| Insignia 32DR310NA17 BBY3253 1680x1050 700x390mm 31.5-inch            | 1         | 1.19%   |
| Iiyama PLE2407HDS IVM560D 1920x1080 520x300mm 23.6-inch               | 1         | 1.19%   |
| Hewlett-Packard LCD Monitor HWP26A4 1440x900 410x260mm 19.1-inch      | 1         | 1.19%   |
| Hewlett-Packard LCD Monitor HPN351A 1920x1080 700x390mm 31.5-inch     | 1         | 1.19%   |
| Hewlett-Packard 27xi HWP3038 1920x1080 600x340mm 27.2-inch            | 1         | 1.19%   |
| HannStar LCD Monitor HSD03E9 1024x600 220x130mm 10.1-inch             | 1         | 1.19%   |
| Goldstar LG ULTRAWIDE GSM5AE2 3440x1440 800x340mm 34.2-inch           | 1         | 1.19%   |
| Goldstar L1918S GSM4B31 1280x1024 380x300mm 19.1-inch                 | 1         | 1.19%   |
| Goldstar 2D FHD LG TV GSM59C6 1920x1080 510x290mm 23.1-inch           | 1         | 1.19%   |
| Goldstar 22MP55 GSM5A24 1920x1080 480x270mm 21.7-inch                 | 1         | 1.19%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart_bsd/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 38        | 46.91%  |
| 1366x768 (WXGA)    | 18        | 22.22%  |
| 1680x1050 (WSXGA+) | 5         | 6.17%   |
| 1600x900 (HD+)     | 5         | 6.17%   |
| 1280x800 (WXGA)    | 5         | 6.17%   |
| 3440x1440          | 2         | 2.47%   |
| 1280x1024 (SXGA)   | 2         | 2.47%   |
| 3840x2400          | 1         | 1.23%   |
| 3200x2000          | 1         | 1.23%   |
| 2560x1440 (QHD)    | 1         | 1.23%   |
| 1920x1200 (WUXGA)  | 1         | 1.23%   |
| 1440x900 (WXGA+)   | 1         | 1.23%   |
| 1024x600           | 1         | 1.23%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart_bsd/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 23        | 27.38%  |
| 13      | 14        | 16.67%  |
| 23      | 6         | 7.14%   |
| 31      | 5         | 5.95%   |
| 21      | 5         | 5.95%   |
| 12      | 5         | 5.95%   |
| 24      | 4         | 4.76%   |
| 19      | 3         | 3.57%   |
| 27      | 2         | 2.38%   |
| 22      | 2         | 2.38%   |
| 20      | 2         | 2.38%   |
| 17      | 2         | 2.38%   |
| 10      | 2         | 2.38%   |
| Unknown | 2         | 2.38%   |
| 50      | 1         | 1.19%   |
| 41      | 1         | 1.19%   |
| 34      | 1         | 1.19%   |
| 33      | 1         | 1.19%   |
| 18      | 1         | 1.19%   |
| 14      | 1         | 1.19%   |
| 11      | 1         | 1.19%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart_bsd/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 33        | 39.29%  |
| 201-300     | 14        | 16.67%  |
| 501-600     | 12        | 14.29%  |
| 401-500     | 12        | 14.29%  |
| 601-700     | 5         | 5.95%   |
| 701-800     | 2         | 2.38%   |
| 351-400     | 2         | 2.38%   |
| Unknown     | 2         | 2.38%   |
| 1001-1500   | 1         | 1.19%   |
| 901-1000    | 1         | 1.19%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart_bsd/mon_ratio.svg)


| Ratio | Computers | Percent |
|-------|-----------|---------|
| 16/9  | 63        | 77.78%  |
| 16/10 | 14        | 17.28%  |
| 5/4   | 2         | 2.47%   |
| 21/9  | 2         | 2.47%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart_bsd/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 91-100         | 18        | 21.43%  |
| 201-250        | 16        | 19.05%  |
| 81-90          | 13        | 15.48%  |
| 351-500        | 7         | 8.33%   |
| 151-200        | 5         | 5.95%   |
| 61-70          | 4         | 4.76%   |
| 71-80          | 3         | 3.57%   |
| 101-110        | 3         | 3.57%   |
| 41-50          | 2         | 2.38%   |
| 301-350        | 2         | 2.38%   |
| 141-150        | 2         | 2.38%   |
| 111-120        | 2         | 2.38%   |
| Unknown        | 2         | 2.38%   |
| More than 1000 | 1         | 1.19%   |
| 51-60          | 1         | 1.19%   |
| 251-300        | 1         | 1.19%   |
| 121-130        | 1         | 1.19%   |
| 501-1000       | 1         | 1.19%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart_bsd/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 101-120       | 27        | 32.53%  |
| 51-100        | 26        | 31.33%  |
| 121-160       | 22        | 26.51%  |
| 161-240       | 4         | 4.82%   |
| Unknown       | 2         | 2.41%   |
| More than 240 | 1         | 1.2%    |
| 1-50          | 1         | 1.2%    |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart_bsd/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 81        | 85.26%  |
| 0     | 10        | 10.53%  |
| 2     | 4         | 4.21%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart_bsd/net_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Intel                    | 50        | 36.76%  |
| Realtek Semiconductor    | 42        | 30.88%  |
| Qualcomm Atheros         | 17        | 12.5%   |
| Broadcom                 | 10        | 7.35%   |
| Nvidia                   | 4         | 2.94%   |
| Ralink Technology        | 2         | 1.47%   |
| Marvell Technology Group | 2         | 1.47%   |
| Sierra Wireless          | 1         | 0.74%   |
| Samsung Electronics      | 1         | 0.74%   |
| Ralink                   | 1         | 0.74%   |
| IMC Networks             | 1         | 0.74%   |
| Huawei Technologies      | 1         | 0.74%   |
| Google                   | 1         | 0.74%   |
| Edimax Technology        | 1         | 0.74%   |
| D-Link System            | 1         | 0.74%   |
| ASUSTek Computer         | 1         | 0.74%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart_bsd/net_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 35        | 22.29%  |
| Intel Wireless 7265                                               | 7         | 4.46%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 6         | 3.82%   |
| Intel Wireless 8265 / 8275                                        | 6         | 3.82%   |
| Intel Wi-Fi 6 AX200                                               | 5         | 3.18%   |
| Nvidia MCP79 Ethernet                                             | 4         | 2.55%   |
| Intel Ethernet Connection I217-LM                                 | 4         | 2.55%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 3         | 1.91%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 3         | 1.91%   |
| Intel Wireless 8260                                               | 3         | 1.91%   |
| Intel Ethernet Connection (3) I218-LM                             | 3         | 1.91%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 3         | 1.91%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller            | 3         | 1.91%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                           | 2         | 1.27%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 2         | 1.27%   |
| Qualcomm Atheros AR8132 Fast Ethernet                             | 2         | 1.27%   |
| Intel Wireless 3160                                               | 2         | 1.27%   |
| Intel WiFi Link 5100                                              | 2         | 1.27%   |
| Intel Wi-Fi 6 AX201                                               | 2         | 1.27%   |
| Intel Ethernet Connection I219-LM                                 | 2         | 1.27%   |
| Intel Ethernet Connection I218-LM                                 | 2         | 1.27%   |
| Intel Ethernet Connection (6) I219-V                              | 2         | 1.27%   |
| Intel Ethernet Connection (4) I219-LM                             | 2         | 1.27%   |
| Intel Ethernet Connection (2) I219-LM                             | 2         | 1.27%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 2         | 1.27%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 2         | 1.27%   |
| Intel 82574L Gigabit Network Connection                           | 2         | 1.27%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 2         | 1.27%   |
| Broadcom BCM43224 802.11a/b/g/n                                   | 2         | 1.27%   |
| Sierra Wireless EM7455                                            | 1         | 0.64%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)       | 1         | 0.64%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 1         | 0.64%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                        | 1         | 0.64%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 1         | 0.64%   |
| Ralink RT5370 Wireless Adapter                                    | 1         | 0.64%   |
| Ralink RT2870/RT3070 Wireless Adapter                             | 1         | 0.64%   |
| Ralink RT5390 Wireless 802.11n 1T/1R PCIe                         | 1         | 0.64%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 1         | 0.64%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 1         | 0.64%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 1         | 0.64%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart_bsd/net_wireless_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Intel                 | 37        | 51.39%  |
| Qualcomm Atheros      | 13        | 18.06%  |
| Realtek Semiconductor | 7         | 9.72%   |
| Broadcom              | 7         | 9.72%   |
| Ralink Technology     | 2         | 2.78%   |
| Sierra Wireless       | 1         | 1.39%   |
| Ralink                | 1         | 1.39%   |
| IMC Networks          | 1         | 1.39%   |
| Edimax Technology     | 1         | 1.39%   |
| D-Link System         | 1         | 1.39%   |
| ASUSTek Computer      | 1         | 1.39%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart_bsd/net_wireless_model.svg)


| Model                                                                       | Computers | Percent |
|-----------------------------------------------------------------------------|-----------|---------|
| Intel Wireless 7265                                                         | 7         | 9.72%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                            | 6         | 8.33%   |
| Intel Wireless 8265 / 8275                                                  | 6         | 8.33%   |
| Intel Wi-Fi 6 AX200                                                         | 5         | 6.94%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                    | 3         | 4.17%   |
| Intel Wireless 8260                                                         | 3         | 4.17%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller                      | 3         | 4.17%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                                     | 2         | 2.78%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)              | 2         | 2.78%   |
| Intel Wireless 3160                                                         | 2         | 2.78%   |
| Intel WiFi Link 5100                                                        | 2         | 2.78%   |
| Intel Wi-Fi 6 AX201                                                         | 2         | 2.78%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                            | 2         | 2.78%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                    | 2         | 2.78%   |
| Broadcom BCM43224 802.11a/b/g/n                                             | 2         | 2.78%   |
| Sierra Wireless EM7455                                                      | 1         | 1.39%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                             | 1         | 1.39%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                                  | 1         | 1.39%   |
| Ralink RT5370 Wireless Adapter                                              | 1         | 1.39%   |
| Ralink RT2870/RT3070 Wireless Adapter                                       | 1         | 1.39%   |
| Ralink RT5390 Wireless 802.11n 1T/1R PCIe                                   | 1         | 1.39%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                  | 1         | 1.39%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                  | 1         | 1.39%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)              | 1         | 1.39%   |
| Qualcomm Atheros AR5212 802.11abg NIC                                       | 1         | 1.39%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express)     | 1         | 1.39%   |
| Intel Wireless 7260                                                         | 1         | 1.39%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                      | 1         | 1.39%   |
| Intel Tiger Lake PCH CNVi WiFi                                              | 1         | 1.39%   |
| Intel Gemini Lake PCH CNVi WiFi                                             | 1         | 1.39%   |
| Intel Centrino Ultimate-N 6300                                              | 1         | 1.39%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                                | 1         | 1.39%   |
| IMC Networks Realtek RTL8191SU Wireless LAN 802.11n USB 2.0 Network Adapter | 1         | 1.39%   |
| Edimax EW-7612UAn V2 802.11n Wireless Adapter [Realtek RTL8192CU]           | 1         | 1.39%   |
| D-Link System DWA-125 Wireless N 150 Adapter(rev.A1) [Ralink RT3070]        | 1         | 1.39%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                          | 1         | 1.39%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                         | 1         | 1.39%   |
| ASUS N10 Nano 802.11n Network Adapter [Realtek RTL8192CU]                   | 1         | 1.39%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart_bsd/net_ethernet_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 39        | 46.99%  |
| Intel                    | 27        | 32.53%  |
| Qualcomm Atheros         | 6         | 7.23%   |
| Nvidia                   | 4         | 4.82%   |
| Broadcom                 | 3         | 3.61%   |
| Marvell Technology Group | 2         | 2.41%   |
| Samsung Electronics      | 1         | 1.2%    |
| Google                   | 1         | 1.2%    |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart_bsd/net_ethernet_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller              | 35        | 41.67%  |
| Nvidia MCP79 Ethernet                                                          | 4         | 4.76%   |
| Intel Ethernet Connection I217-LM                                              | 4         | 4.76%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                          | 3         | 3.57%   |
| Intel Ethernet Connection (3) I218-LM                                          | 3         | 3.57%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                          | 3         | 3.57%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                          | 2         | 2.38%   |
| Intel Ethernet Connection I219-LM                                              | 2         | 2.38%   |
| Intel Ethernet Connection I218-LM                                              | 2         | 2.38%   |
| Intel Ethernet Connection (6) I219-V                                           | 2         | 2.38%   |
| Intel Ethernet Connection (4) I219-LM                                          | 2         | 2.38%   |
| Intel Ethernet Connection (2) I219-LM                                          | 2         | 2.38%   |
| Intel 82574L Gigabit Network Connection                                        | 2         | 2.38%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                                | 2         | 2.38%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)                    | 1         | 1.19%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                          | 1         | 1.19%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller                      | 1         | 1.19%   |
| Qualcomm Atheros Attansic L1 Gigabit Ethernet                                  | 1         | 1.19%   |
| Qualcomm Atheros AR8162 Fast Ethernet                                          | 1         | 1.19%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                                     | 1         | 1.19%   |
| Marvell Group Yukon Optima 88E8059 [PCIe Gigabit Ethernet Controller with AVB] | 1         | 1.19%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller                        | 1         | 1.19%   |
| Intel Ethernet Controller I225-V                                               | 1         | 1.19%   |
| Intel Ethernet Connection I219-V                                               | 1         | 1.19%   |
| Intel Ethernet Connection (7) I219-V                                           | 1         | 1.19%   |
| Intel Ethernet Connection (2) I219-V                                           | 1         | 1.19%   |
| Intel Ethernet Connection (14) I219-LM                                         | 1         | 1.19%   |
| Intel Ethernet Connection (11) I219-LM                                         | 1         | 1.19%   |
| Google Nexus/Pixel Device (tether)                                             | 1         | 1.19%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                                | 1         | 1.19%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart_bsd/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 83        | 54.97%  |
| WiFi     | 67        | 44.37%  |
| Modem    | 1         | 0.66%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart_bsd/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 61        | 62.24%  |
| WiFi     | 37        | 37.76%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart_bsd/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 51        | 53.68%  |
| 1     | 43        | 45.26%  |
| 0     | 1         | 1.05%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart_bsd/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 89        | 93.68%  |
| Yes  | 6         | 6.32%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart_bsd/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 29        | 56.86%  |
| Apple                           | 6         | 11.76%  |
| Realtek Semiconductor           | 3         | 5.88%   |
| Lite-On Technology              | 2         | 3.92%   |
| IMC Networks                    | 2         | 3.92%   |
| Cambridge Silicon Radio         | 2         | 3.92%   |
| Qualcomm Atheros Communications | 1         | 1.96%   |
| Integrated System Solution      | 1         | 1.96%   |
| Hewlett-Packard                 | 1         | 1.96%   |
| Broadcom                        | 1         | 1.96%   |
| Bluetooth Device                | 1         | 1.96%   |
| ASUSTek Computer                | 1         | 1.96%   |
| Alps Electric                   | 1         | 1.96%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart_bsd/bt_model.svg)


| Model                                                    | Computers | Percent |
|----------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                       | 16        | 30.19%  |
| Intel AX200 Bluetooth                                    | 4         | 7.55%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                     | 4         | 7.55%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)           | 3         | 5.66%   |
| Intel AX201 Bluetooth                                    | 3         | 5.66%   |
| Realtek  Bluetooth 4.2 Adapter                           | 2         | 3.77%   |
| Intel Wireless-AC 3168 Bluetooth                         | 2         | 3.77%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)      | 2         | 3.77%   |
| Apple Built-in iSight (no firmware loaded)               | 2         | 3.77%   |
| Realtek Dell Wireless 1801 Bluetooth 4.0 LE              | 1         | 1.89%   |
| Qualcomm Atheros Dell Wireless 1703 Bluetooth            | 1         | 1.89%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth               | 1         | 1.89%   |
| Lite-On Atheros AR3012 Bluetooth                         | 1         | 1.89%   |
| Intel AX210 Bluetooth                                    | 1         | 1.89%   |
| Integrated System Solution Bluetooth Device              | 1         | 1.89%   |
| IMC Networks Realtek Bluetooth Adapter                   | 1         | 1.89%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter        | 1         | 1.89%   |
| HP Broadcom 2070 Bluetooth Combo                         | 1         | 1.89%   |
| Broadcom BCM2045B (BDC-2.1)                              | 1         | 1.89%   |
| Bluetooth Device Silicon Wave Bluetooth Wireless Adapter | 1         | 1.89%   |
| ASUS BT-253 Bluetooth Adapter                            | 1         | 1.89%   |
| Apple Bluetooth Host Controller                          | 1         | 1.89%   |
| Apple Apple Broadcom Built-in Bluetooth                  | 1         | 1.89%   |
| Alps Electric BCM2046 Bluetooth Device                   | 1         | 1.89%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart_bsd/snd_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Intel               | 72        | 59.02%  |
| AMD                 | 20        | 16.39%  |
| Nvidia              | 19        | 15.57%  |
| C-Media Electronics | 4         | 3.28%   |
| Google              | 2         | 1.64%   |
| Yamaha              | 1         | 0.82%   |
| XMOS                | 1         | 0.82%   |
| Logitech            | 1         | 0.82%   |
| GN Netcom           | 1         | 0.82%   |
| Creative Technology | 1         | 0.82%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart_bsd/snd_model.svg)


| Model                                                                                             | Computers | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                                                   | 10        | 6.94%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 8         | 5.56%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 8         | 5.56%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 6         | 4.17%   |
| Intel Broadwell-U Audio Controller                                                                | 6         | 4.17%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 6         | 4.17%   |
| Nvidia TU116 High Definition Audio Controller                                                     | 5         | 3.47%   |
| Nvidia MCP79 High Definition Audio                                                                | 4         | 2.78%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 4         | 2.78%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 4         | 2.78%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 4         | 2.78%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 4         | 2.78%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 3         | 2.08%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 3         | 2.08%   |
| Intel 200 Series PCH HD Audio                                                                     | 3         | 2.08%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 3         | 2.08%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 3         | 2.08%   |
| Unknown                                                                                           | 3         | 2.08%   |
| Nvidia High Definition Audio Controller                                                           | 2         | 1.39%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 2         | 1.39%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 2         | 1.39%   |
| Intel Tiger Lake-H HD Audio Controller                                                            | 2         | 1.39%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 2         | 1.39%   |
| Intel Cannon Lake PCH cAVS                                                                        | 2         | 1.39%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 2         | 1.39%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 2         | 1.39%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                                  | 2         | 1.39%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 2         | 1.39%   |
| Intel 8 Series HD Audio Controller                                                                | 2         | 1.39%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 2         | 1.39%   |
| Google Pixel earbuds                                                                              | 2         | 1.39%   |
| C-Media Electronics Audio Adapter (Unitek Y-247A)                                                 | 2         | 1.39%   |
| AMD Starship/Matisse HD Audio Controller                                                          | 2         | 1.39%   |
| AMD FCH Azalia Controller                                                                         | 2         | 1.39%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                                               | 2         | 1.39%   |
| Yamaha Steinberg UR22mkII                                                                         | 1         | 0.69%   |
| XMOS iFi (by AMR) HD USB Audio                                                                    | 1         | 0.69%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 1         | 0.69%   |
| Nvidia GP108 High Definition Audio Controller                                                     | 1         | 0.69%   |
| Nvidia GM206 High Definition Audio Controller                                                     | 1         | 0.69%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart_bsd/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| SK hynix            | 22        | 18.97%  |
| Unknown             | 17        | 14.66%  |
| Samsung Electronics | 17        | 14.66%  |
| Kingston            | 15        | 12.93%  |
| Micron Technology   | 11        | 9.48%   |
| Crucial             | 6         | 5.17%   |
| Transcend           | 4         | 3.45%   |
| Nanya Technology    | 3         | 2.59%   |
| A-DATA Technology   | 3         | 2.59%   |
| Unknown             | 3         | 2.59%   |
| Smart               | 2         | 1.72%   |
| Ramaxel Technology  | 2         | 1.72%   |
| Corsair             | 2         | 1.72%   |
| Teikon              | 1         | 0.86%   |
| Team                | 1         | 0.86%   |
| Smart Brazil        | 1         | 0.86%   |
| PNY                 | 1         | 0.86%   |
| Patriot             | 1         | 0.86%   |
| GLOWAY              | 1         | 0.86%   |
| GeIL                | 1         | 0.86%   |
| G.Skill             | 1         | 0.86%   |
| Elpida              | 1         | 0.86%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart_bsd/memory_model.svg)


| Model                                                  | Computers | Percent |
|--------------------------------------------------------|-----------|---------|
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s | 3         | 2.36%   |
| Unknown                                                | 3         | 2.36%   |
| Unknown RAM Module 2GB DIMM DDR2 800MT/s               | 2         | 1.57%   |
| Unknown RAM Module 1GB DIMM SDRAM                      | 2         | 1.57%   |
| Transcend RAM JM1333KLN-4G 4GB DIMM DDR3 1333MT/s      | 2         | 1.57%   |
| SK hynix RAM HMT41GU6BFR8A-PB 8GB DIMM DDR3 1600MT/s   | 2         | 1.57%   |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2400MT/s | 2         | 1.57%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s  | 2         | 1.57%   |
| Kingston RAM 99U5702-095.A00G 8GB DIMM DDR4 3200MT/s   | 2         | 1.57%   |
| Unknown RAM Module 4GB SODIMM DDR3 1333MT/s            | 1         | 0.79%   |
| Unknown RAM Module 4GB DIMM SDRAM                      | 1         | 0.79%   |
| Unknown RAM Module 4GB DIMM DDR3 1067MT/s              | 1         | 0.79%   |
| Unknown RAM Module 4GB DIMM 1600MT/s                   | 1         | 0.79%   |
| Unknown RAM Module 4GB DIMM 1333MT/s                   | 1         | 0.79%   |
| Unknown RAM Module 2GB SODIMM DDR3 1333MT/s            | 1         | 0.79%   |
| Unknown RAM Module 2GB SODIMM DDR3 1067MT/s            | 1         | 0.79%   |
| Unknown RAM Module 2GB SODIMM DDR3                     | 1         | 0.79%   |
| Unknown RAM Module 2GB SODIMM DDR2 800MT/s             | 1         | 0.79%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s             | 1         | 0.79%   |
| Unknown RAM Module 2GB SODIMM DDR2                     | 1         | 0.79%   |
| Unknown RAM Module 2GB DIMM SDRAM                      | 1         | 0.79%   |
| Unknown RAM Module 2GB DIMM DDR3 1066MT/s              | 1         | 0.79%   |
| Unknown RAM Module 2GB DIMM DDR2                       | 1         | 0.79%   |
| Unknown RAM Module 2GB DIMM 1333MT/s                   | 1         | 0.79%   |
| Unknown RAM Module 1GB SODIMM DDR2 800MT/s             | 1         | 0.79%   |
| Transcend RAM TS4GSH64V2E3 32GB SODIMM DDR4 3200MT/s   | 1         | 0.79%   |
| Transcend RAM TS256MSK64V3N 2GB SODIMM DDR3 1333MT/s   | 1         | 0.79%   |
| Transcend RAM JM1333KLH-8G 8GB DIMM DDR3 1333MT/s      | 1         | 0.79%   |
| Teikon RAM TML251S6EFR8A-PBHC 4GB SODIMM DDR3 1600MT/s | 1         | 0.79%   |
| Team RAM Elite-13 4GB DIMM DDR3 667MT/s                | 1         | 0.79%   |
| Team RAM Elite-1 2GB DIMM DDR3 667MT/s                 | 1         | 0.79%   |
| Smart RAM SH564568FH8NZPHSCR 2GB SODIMM DDR3 1334MT/s  | 1         | 0.79%   |
| Smart RAM SH564568FH8NWPHSFR 2GB SODIMM DDR3 1333MT/s  | 1         | 0.79%   |
| Smart RAM SH564128FJ8NWRNSQR 4GB SODIMM DDR3 1600MT/s  | 1         | 0.79%   |
| Smart Brazil RAM Module 4GB Row Of Chips DDR4 2400MT/s | 1         | 0.79%   |
| SK hynix RAM Module 4GB SODIMM DDR4 2400MT/s           | 1         | 0.79%   |
| SK hynix RAM Module 2GB SODIMM DDR3 1600MT/s           | 1         | 0.79%   |
| SK hynix RAM Module 2GB SODIMM DDR3 1067MT/s           | 1         | 0.79%   |
| SK hynix RAM HMT451U6AFR8C-PB 4GB DIMM DDR3 1600MT/s   | 1         | 0.79%   |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s | 1         | 0.79%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart_bsd/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR3    | 40        | 42.11%  |
| DDR4    | 39        | 41.05%  |
| DDR2    | 10        | 10.53%  |
| SDRAM   | 3         | 3.16%   |
| Unknown | 2         | 2.11%   |
| LPDDR3  | 1         | 1.05%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart_bsd/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 55        | 57.89%  |
| DIMM         | 36        | 37.89%  |
| Row Of Chips | 3         | 3.16%   |
| Unknown      | 1         | 1.05%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart_bsd/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 4096  | 41        | 36.94%  |
| 8192  | 27        | 24.32%  |
| 2048  | 26        | 23.42%  |
| 16384 | 13        | 11.71%  |
| 1024  | 3         | 2.7%    |
| 32768 | 1         | 0.9%    |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart_bsd/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 26        | 25.24%  |
| 2400    | 14        | 13.59%  |
| 1333    | 12        | 11.65%  |
| 3200    | 10        | 9.71%   |
| 2667    | 9         | 8.74%   |
| 2133    | 6         | 5.83%   |
| 800     | 6         | 5.83%   |
| Unknown | 6         | 5.83%   |
| 2666    | 3         | 2.91%   |
| 1067    | 3         | 2.91%   |
| 667     | 3         | 2.91%   |
| 1334    | 2         | 1.94%   |
| 2933    | 1         | 0.97%   |
| 1066    | 1         | 0.97%   |
| 333     | 1         | 0.97%   |

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
| Chicony Electronics           | 11        | 23.91%  |
| Microdia                      | 8         | 17.39%  |
| Sunplus Innovation Technology | 5         | 10.87%  |
| IMC Networks                  | 5         | 10.87%  |
| Realtek Semiconductor         | 4         | 8.7%    |
| Syntek                        | 2         | 4.35%   |
| Suyin                         | 2         | 4.35%   |
| Z-Star Microelectronics       | 1         | 2.17%   |
| Luxvisions Innotech Limited   | 1         | 2.17%   |
| Logitech                      | 1         | 2.17%   |
| Lite-On Technology            | 1         | 2.17%   |
| Genesys Logic                 | 1         | 2.17%   |
| Arkmicro Technologies         | 1         | 2.17%   |
| Apple                         | 1         | 2.17%   |
| Alcor Micro                   | 1         | 2.17%   |
| Acer                          | 1         | 2.17%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart_bsd/camera_model.svg)


| Model                                                       | Computers | Percent |
|-------------------------------------------------------------|-----------|---------|
| Chicony HD Webcam                                           | 3         | 6.52%   |
| Sunplus Integrated_Webcam_HD                                | 2         | 4.35%   |
| Realtek Realtek USB2.0 PC Camera                            | 2         | 4.35%   |
| Microdia Integrated_Webcam_HD                               | 2         | 4.35%   |
| IMC Networks USB2.0 UVC VGA WebCam                          | 2         | 4.35%   |
| Chicony integrated camera                                   | 2         | 4.35%   |
| Z-Star Venus USB2.0 Camera                                  | 1         | 2.17%   |
| Syntek Syntek 0.3MPixel USB 2.0 UVC PC Camera               | 1         | 2.17%   |
| Syntek Integrated Camera                                    | 1         | 2.17%   |
| Suyin Integrated_Webcam_HD                                  | 1         | 2.17%   |
| Suyin 1.3M WebCam (notebook emachines E730, Acer sub-brand) | 1         | 2.17%   |
| Sunplus XiaoMi USB 2.0 Webcam                               | 1         | 2.17%   |
| Sunplus Integrated_Webcam_FHD                               | 1         | 2.17%   |
| Sunplus HP HD Webcam [Fixed]                                | 1         | 2.17%   |
| Realtek Integrated_Webcam_HD                                | 1         | 2.17%   |
| Realtek HD WebCam                                           | 1         | 2.17%   |
| Microdia Webcam                                             | 1         | 2.17%   |
| Microdia Laptop_Integrated_Webcam_HD                        | 1         | 2.17%   |
| Microdia Laptop_Integrated_Webcam_2M                        | 1         | 2.17%   |
| Microdia Integrated Webcam HD                               | 1         | 2.17%   |
| Microdia Dell Laptop Integrated Webcam HD                   | 1         | 2.17%   |
| Microdia Camera                                             | 1         | 2.17%   |
| Luxvisions Innotech Limited Integrated Camera               | 1         | 2.17%   |
| Logitech HD Pro Webcam C920                                 | 1         | 2.17%   |
| Lite-On HP HD Webcam [Fixed]                                | 1         | 2.17%   |
| IMC Networks USB2.0 VGA UVC WebCam                          | 1         | 2.17%   |
| IMC Networks Integrated RGB Camera                          | 1         | 2.17%   |
| IMC Networks HD Camera                                      | 1         | 2.17%   |
| Genesys Logic Digital Microscope                            | 1         | 2.17%   |
| Chicony XiaoMi USB 2.0 Webcam                               | 1         | 2.17%   |
| Chicony VGA WebCam                                          | 1         | 2.17%   |
| Chicony TOSHIBA Web Camera - HD                             | 1         | 2.17%   |
| Chicony TOSHIBA Web Camera - FHD                            | 1         | 2.17%   |
| Chicony Lenovo EasyCamera                                   | 1         | 2.17%   |
| Chicony 1.3M UVC Webcam                                     | 1         | 2.17%   |
| Arkmicro Webcam Carrefour                                   | 1         | 2.17%   |
| Apple FaceTime HD Camera (Built-in)                         | 1         | 2.17%   |
| Alcor Micro Acer Integrated Webcam                          | 1         | 2.17%   |
| Acer Integrated Camera                                      | 1         | 2.17%   |

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
| 1     | 37        | 38.95%  |
| 0     | 27        | 28.42%  |
| 2     | 18        | 18.95%  |
| 3     | 10        | 10.53%  |
| 4     | 2         | 2.11%   |
| 5     | 1         | 1.05%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart_bsd/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Communication controller | 53        | 47.32%  |
| Bluetooth                | 25        | 22.32%  |
| Net/wireless             | 12        | 10.71%  |
| Card reader              | 9         | 8.04%   |
| Fingerprint reader       | 7         | 6.25%   |
| Sound                    | 3         | 2.68%   |
| Network                  | 2         | 1.79%   |
| Storage                  | 1         | 0.89%   |

